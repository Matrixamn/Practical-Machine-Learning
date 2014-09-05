Feedback — Quiz 2  </span>
  
  <a class="coursera-reporter-link" title="Click here if you're experiencing technical problems or found errors in the course materials." target="_blank" href="https://class.coursera.org/predmachlearn-005/help/quizzes?url=https%3A%2F%2Fclass.coursera.org%2Fpredmachlearn-005%2Fquiz%2Ffeedback%3Fsubmission_id%3D556">
     Help
  </a>
</h2>


<a data-coursera-admin-helpwidget-link="" rel="help" href="https://class.coursera.org/mooc/help/quiz" title="Quiz documentation" style="display:none;">Learn more</a>




                <div class="alert alert-success"> Thank you. Your submission for this quiz was received. </div>
    


<p class="course-quiz-feedback"> You submitted this quiz on <strong>Tue  2 Sep 2014  8:58 PM ART</strong>. You got a score of <strong>12.00</strong> out of <strong>15.00</strong>. You can <a href="https://class.coursera.org/predmachlearn-005/quiz/start?quiz_id=91">attempt again</a>, if you'd like.</p>


            <form method="post" id="quiz_form" accept-charset="UTF-8">
    
    
    
    <div class="course-quiz-question-body">
<h3 class="course-quiz-question-number">Question 1</h3>
<div dir="auto" class="course-quiz-question-text">Load the Alzheimer's disease data using the commands:

<pre>library(AppliedPredictiveModeling)
library(caret)
data(AlzheimerDisease)
</pre>

Which of the following commands will create training and test sets with about 50% of the observations assigned to each? </div>
<div dir="auto" class="course-quiz-options"></div>
<table class="table">
<tbody><tr>
<th>Your Answer</th>
<th></th>
<th>Score</th>
<th>Explanation</th>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[1405e039b78bce99bec2192ac2b40b9f][]" id="gensym_5409c5a73c698" value="e28b62b1c836a53360a483cb08fb67c6" checked="" disabled="" type="radio"><pre>adData = data.frame(diagnosis,predictors)
trainIndex = createDataPartition(diagnosis, p = 0.50,list=FALSE)
training = adData[trainIndex,]
testing = adData[-trainIndex,]
</pre>
</td>
<td><span class="course-quiz-answer-correct" title="Correct" alt="Correct"><span class="icon-ok" alt="Correct"><span class="accessible-text-for-reader">Correct</span></span></span></td>
<td>3.00</td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[1405e039b78bce99bec2192ac2b40b9f][]" id="gensym_5409c5a73d379" value="d50b7ebcb3a730f16f4b4a753696a375" disabled="" type="radio"><pre>adData = data.frame(diagnosis,predictors)
train = createDataPartition(diagnosis, p = 0.50,list=FALSE)
test = createDataPartition(diagnosis, p = 0.50,list=FALSE)
</pre>
</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[1405e039b78bce99bec2192ac2b40b9f][]" id="gensym_5409c5a73db76" value="204c2b282d007cceeba918f7770f1943" disabled="" type="radio"><pre>adData = data.frame(diagnosis,predictors)
trainIndex = createDataPartition(diagnosis,p=0.5,list=FALSE)
training = adData[trainIndex,]
testing = adData[trainIndex,]
</pre>
</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[1405e039b78bce99bec2192ac2b40b9f][]" id="gensym_5409c5a73e37f" value="4a25b506dd70004368ca27dc3ee9d310" disabled="" type="radio"><pre>adData = data.frame(predictors)
trainIndex = createDataPartition(diagnosis,p=0.5,list=FALSE)
training = adData[trainIndex,]
testing = adData[-trainIndex,]
</pre>
</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>Total</td>
<td></td>
<td>3.00 / 3.00</td>
<td></td>
</tr>
</tbody></table>
</div><div class="course-quiz-question-body">
<h3 class="course-quiz-question-number">Question 2</h3>
<div dir="auto" class="course-quiz-question-text">Load the cement data using the commands:

<pre>library(AppliedPredictiveModeling)
data(concrete)
library(caret)
set.seed(975)
inTrain = createDataPartition(mixtures$CompressiveStrength, p = 3/4)[[1]]
training = mixtures[ inTrain,]
testing = mixtures[-inTrain,]
</pre>

Make a plot of the outcome (CompressiveStrength) versus the index of the samples. Color by each of the variables in the data set (you may find the cut2() function in the Hmisc package useful for turning continuous covariates into factors). What do you notice in these plots? </div>
<div dir="auto" class="course-quiz-options"></div>
<table class="table">
<tbody><tr>
<th>Your Answer</th>
<th></th>
<th>Score</th>
<th>Explanation</th>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[84aeb6148704dddd6ba1ea6c730445e3][]" id="gensym_5409c5a741e1e" value="7e31996daa18a5100bb0f2ca17b2eb7c" disabled="" type="radio">There is a step-like pattern in the plot of outcome versus index in the training set.</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[84aeb6148704dddd6ba1ea6c730445e3][]" id="gensym_5409c5a742637" value="42bf4422f55d0efc53f90a9270a26e5f" disabled="" type="radio">The data show a step like pattern that is perfectly explained by the Age variable. </td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[84aeb6148704dddd6ba1ea6c730445e3][]" id="gensym_5409c5a742ed9" value="732c7a7356a5d5316e7f4ce9b312109f" checked="" disabled="" type="radio">There is a step-like pattern in the plot of outcome versus index in the training set that isn't explained by any of the predictor variables so there may be a variable missing.</td>
<td><span class="course-quiz-answer-correct" title="Correct" alt="Correct"><span class="icon-ok" alt="Correct"><span class="accessible-text-for-reader">Correct</span></span></span></td>
<td>3.00</td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[84aeb6148704dddd6ba1ea6c730445e3][]" id="gensym_5409c5a743c30" value="315b333751222e9124cbd69d70d592b0" disabled="" type="radio">The outcome variable is highly correlated with FlyAsh. </td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>Total</td>
<td></td>
<td>3.00 / 3.00</td>
<td></td>
</tr>
</tbody></table>
</div><div class="course-quiz-question-body">
<h3 class="course-quiz-question-number">Question 3</h3>
<div dir="auto" class="course-quiz-question-text">Load the cement data using the commands:

<pre>library(AppliedPredictiveModeling)
data(concrete)
library(caret)
set.seed(975)
inTrain = createDataPartition(mixtures$CompressiveStrength, p = 3/4)[[1]]
training = mixtures[ inTrain,]
testing = mixtures[-inTrain,]
</pre>

Make a histogram and confirm the SuperPlasticizer variable is skewed. Normally you might use the log transform to try to make the data more symmetric. Why would that be a poor choice for this variable?</div>
<div dir="auto" class="course-quiz-options"></div>
<table class="table">
<tbody><tr>
<th>Your Answer</th>
<th></th>
<th>Score</th>
<th>Explanation</th>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[a6b0efc3da47e85f0dbc8f46e7ba47c1][]" id="gensym_5409c5a747616" value="c53132007a7c00643a6a996c9584e031" disabled="" type="radio">The log transform produces negative values which can not be used by some classifiers.</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[a6b0efc3da47e85f0dbc8f46e7ba47c1][]" id="gensym_5409c5a747e1d" value="72dc2a58e492bccd411cc9015dde32d9" disabled="" type="radio">The SuperPlasticizer data include negative values so the log transform can not be performed. </td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[a6b0efc3da47e85f0dbc8f46e7ba47c1][]" id="gensym_5409c5a74878d" value="b5d57db5042d73c6e3ed9602c00414ce" disabled="" type="radio">The log transform does not reduce the skewness of the non-zero values of SuperPlasticizer</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[a6b0efc3da47e85f0dbc8f46e7ba47c1][]" id="gensym_5409c5a74921c" value="3372f9fa8e37626fe400c5a0b293b4a3" checked="" disabled="" type="radio">There are values of zero so when you take the log() transform those values will be -Inf.</td>
<td><span class="course-quiz-answer-correct" title="Correct" alt="Correct"><span class="icon-ok" alt="Correct"><span class="accessible-text-for-reader">Correct</span></span></span></td>
<td>3.00</td>
<td></td>
</tr>
<tr>
<td>Total</td>
<td></td>
<td>3.00 / 3.00</td>
<td></td>
</tr>
</tbody></table>
</div><div class="course-quiz-question-body">
<h3 class="course-quiz-question-number">Question 4</h3>
<div dir="auto" class="course-quiz-question-text">Load the Alzheimer's disease data using the commands:

<pre>library(caret)
library(AppliedPredictiveModeling)
set.seed(3433)
data(AlzheimerDisease)
adData = data.frame(diagnosis,predictors)
inTrain = createDataPartition(adData$diagnosis, p = 3/4)[[1]]
training = adData[ inTrain,]
testing = adData[-inTrain,]
</pre>

Find all the predictor variables in the training set that begin with IL. Perform principal components on these variables with the preProcess() function from the caret package. Calculate the number of principal components needed to capture 90% of the variance. How many are there?</div>
<div dir="auto" class="course-quiz-options"></div>
<table class="table">
<tbody><tr>
<th>Your Answer</th>
<th></th>
<th>Score</th>
<th>Explanation</th>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[e341a1c7e5fbba48c3a2ab9b99ee25b5][]" id="gensym_5409c5a74d18a" value="167edb1b4362591d1a116cf45da6cd48" disabled="" type="radio">11</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[e341a1c7e5fbba48c3a2ab9b99ee25b5][]" id="gensym_5409c5a74da69" value="a9149fa4afad276b1d1a1c8ab78c04ef" disabled="" type="radio">5</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[e341a1c7e5fbba48c3a2ab9b99ee25b5][]" id="gensym_5409c5a74e578" value="fd9bd33e4a74148f40dd0522f9a37c72" checked="" disabled="" type="radio">10</td>
<td><span class="course-quiz-answer-incorrect" title="Incorrect" alt="Incorrect"><span class="icon-remove" alt="Incorrect"><span class="accessible-text-for-reader">Inorrect</span></span></span></td>
<td>0.00</td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[e341a1c7e5fbba48c3a2ab9b99ee25b5][]" id="gensym_5409c5a74f29b" value="5a776c9772597b244e41481586f39d89" disabled="" type="radio">9</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>Total</td>
<td></td>
<td>0.00 / 3.00</td>
<td></td>
</tr>
</tbody></table>
</div><div class="course-quiz-question-body">
<h3 class="course-quiz-question-number">Question 5</h3>
<div dir="auto" class="course-quiz-question-text">Load the Alzheimer's disease data using the commands:
<pre>library(caret)
library(AppliedPredictiveModeling)
set.seed(3433)
data(AlzheimerDisease)
adData = data.frame(diagnosis,predictors)
inTrain = createDataPartition(adData$diagnosis, p = 3/4)[[1]]
training = adData[ inTrain,]
testing = adData[-inTrain,]
</pre>

Create a training data set consisting of only the predictors with variable names beginning with IL and the diagnosis. Build two predictive models, one using the predictors as they are and one using PCA with principal components explaining 80% of the variance in the predictors. Use method="glm" in the train function. 

What is the accuracy of each method in the test set? Which is more accurate?
</div>
<div dir="auto" class="course-quiz-options"></div>
<table class="table">
<tbody><tr>
<th>Your Answer</th>
<th></th>
<th>Score</th>
<th>Explanation</th>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[58ff553da3ec8d2931c29a51c0075f0d][]" id="gensym_5409c5a75292e" value="18ccd63a83af7f8443b97ba434951d02" checked="" disabled="" type="radio">Non-PCA Accuracy: 0.65 <br>
PCA Accuracy: 0.72
</td>
<td><span class="course-quiz-answer-correct" title="Correct" alt="Correct"><span class="icon-ok" alt="Correct"><span class="accessible-text-for-reader">Correct</span></span></span></td>
<td>3.00</td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[58ff553da3ec8d2931c29a51c0075f0d][]" id="gensym_5409c5a7535b0" value="3a9135a38df50cbc9bd9f85265606810" disabled="" type="radio">Non-PCA Accuracy: 0.72 <br>
PCA Accuracy: 0.71</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[58ff553da3ec8d2931c29a51c0075f0d][]" id="gensym_5409c5a753f46" value="f0ce2878c27012edd7cb7ac7bee3d0eb" disabled="" type="radio">Non-PCA Accuracy: 0.75 <br>
PCA Accuracy: 0.71</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[58ff553da3ec8d2931c29a51c0075f0d][]" id="gensym_5409c5a75477d" value="7518b79fceae36a41907fa8fe0d94ef9" disabled="" type="radio">Non-PCA Accuracy: 0.74 <br>
PCA Accuracy: 0.74</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>Total</td>
<td></td>
<td>3.00 / 3.00</td>
