Feedback — Quiz 4  </span>
  
  <a class="coursera-reporter-link" title="Click here if you're experiencing technical problems or found errors in the course materials." target="_blank" href="https://class.coursera.org/predmachlearn-005/help/quizzes?url=https%3A%2F%2Fclass.coursera.org%2Fpredmachlearn-005%2Fquiz%2Ffeedback%3Fsubmission_id%3D559">
     Help
  </a>
</h2>


<a data-coursera-admin-helpwidget-link="" rel="help" href="https://class.coursera.org/mooc/help/quiz" title="Quiz documentation" style="display:none;">Learn more</a>




                <div class="alert alert-success"> Thank you. Your submission for this quiz was received. </div>
    


<p class="course-quiz-feedback"> You submitted this quiz on <strong>Tue  2 Sep 2014  9:03 PM ART</strong>. You got a score of <strong>12.00</strong> out of <strong>15.00</strong>. You can <a href="https://class.coursera.org/predmachlearn-005/quiz/start?quiz_id=97">attempt again</a>, if you'd like.</p>


            <form method="post" id="quiz_form" accept-charset="UTF-8">
    
    
    
    <div class="course-quiz-question-body">
<h3 class="course-quiz-question-number">Question 1</h3>
<div dir="auto" class="course-quiz-question-text">Load the vowel.train and vowel.test data sets:

<pre><code>library(ElemStatLearn)
data(vowel.train)
data(vowel.test) 
</code></pre>

Set the variable y to be a factor variable in both the training and test set. Then set the seed to 33833. Fit (1) a random forest predictor relating the factor variable y to the remaining variables and (2) a boosted predictor using the "gbm" method. Fit these both with the train() command in the caret package. <br><br> 

What are the accuracies for the two approaches on the test data set? What is the accuracy among the test set samples where the two methods agree? </div>
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
<input dir="auto" class="course-quiz-input" name="answer[6e07c449e81d9512fffd2fce19eb8817][]" id="gensym_5409c60c88664" value="7a03a0d1dd5bdc162d790c331a720979" disabled="" type="radio">RF Accuracy =  0.6061 <br>
GBM Accuracy = 0.5325  <br>
Agreement Accuracy = 0.6518</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[6e07c449e81d9512fffd2fce19eb8817][]" id="gensym_5409c60c892dd" value="e8ffb4ddc6730305253d5f7b27d5b5ed" disabled="" type="radio">RF Accuracy =  0.9881 <br>
GBM Accuracy = 0.5325  <br>
Agreement Accuracy = 0.9973 </td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[6e07c449e81d9512fffd2fce19eb8817][]" id="gensym_5409c60c89ddf" value="5a77df86d45f405382718341349059ac" checked="" disabled="" type="radio">RF Accuracy =  0.6061 <br>
GBM Accuracy = 0.6518  <br>
Agreement Accuracy = 0.5325 </td>
<td><span class="course-quiz-answer-incorrect" title="Incorrect" alt="Incorrect"><span class="icon-remove" alt="Incorrect"><span class="accessible-text-for-reader">Inorrect</span></span></span></td>
<td>0.00</td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[6e07c449e81d9512fffd2fce19eb8817][]" id="gensym_5409c60c8ab21" value="e901f108f640f2f5f0256f1884e7614f" disabled="" type="radio">RF Accuracy =  0.6518 <br>
GBM Accuracy = 0.5325  <br>
Agreement Accuracy = 0.5325 </td>
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
<h3 class="course-quiz-question-number">Question 2</h3>
<div dir="auto" class="course-quiz-question-text">Load the Alzheimer's data using the following commands

<pre>library(caret)
library(gbm)
set.seed(3433)
library(AppliedPredictiveModeling)
data(AlzheimerDisease)
adData = data.frame(diagnosis,predictors)
inTrain = createDataPartition(adData$diagnosis, p = 3/4)[[1]]
training = adData[ inTrain,]
testing = adData[-inTrain,]
</pre>

Set the seed to 62433 and predict diagnosis with all the other variables using a random forest ("rf"), boosted trees ("gbm") and linear discriminant analysis ("lda") model. Stack the predictions together using random forests ("rf"). What is the resulting accuracy on the test set? Is it better or worse than each of the individual predictions? </div>
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
<input dir="auto" class="course-quiz-input" name="answer[b06e3eae9940aa0f97bd3b05cb4499cc][]" id="gensym_5409c60c8f1ef" value="079dd40545a8f551af0032fdc6996749" checked="" disabled="" type="radio">Stacked Accuracy: 0.79 is better than random forests and lda and the same as boosting. </td>
<td><span class="course-quiz-answer-correct" title="Correct" alt="Correct"><span class="icon-ok" alt="Correct"><span class="accessible-text-for-reader">Correct</span></span></span></td>
<td>3.00</td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[b06e3eae9940aa0f97bd3b05cb4499cc][]" id="gensym_5409c60c8ff35" value="5e1b1ea9555937ddcdc3cfaeede4ff36" disabled="" type="radio">Stacked Accuracy: 0.79 is worse than all the other methods.</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[b06e3eae9940aa0f97bd3b05cb4499cc][]" id="gensym_5409c60c9091c" value="977a7594b84f4cdb8a833ef0a6778b91" disabled="" type="radio">Stacked Accuracy: 0.88 is better than all three other methods</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[b06e3eae9940aa0f97bd3b05cb4499cc][]" id="gensym_5409c60c91280" value="1e19b75e117703cd31b0f05600b36424" disabled="" type="radio">Stacked Accuracy: 0.69 is better than all three other methods</td>
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
<div dir="auto" class="course-quiz-question-text">Load the concrete data with the commands:

<pre>set.seed(3523)
library(AppliedPredictiveModeling)
data(concrete)
inTrain = createDataPartition(concrete$CompressiveStrength, p = 3/4)[[1]]
training = concrete[ inTrain,]
testing = concrete[-inTrain,]
</pre>

Set the seed to 233 and fit a lasso model to predict Compressive Strength. Which variable is the last coefficient to be set to zero as the penalty increases? (Hint: it may be useful to look up ?plot.enet). </div>
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
<input dir="auto" class="course-quiz-input" name="answer[b69f2d0c422938319cb0b00c5b946f99][]" id="gensym_5409c60c95bcd" value="de62d0f56f0aeb4c652305300592fe0b" disabled="" type="radio">CoarseAggregate</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[b69f2d0c422938319cb0b00c5b946f99][]" id="gensym_5409c60c965a9" value="1e019016bf294a1d5ae7001e487db883" disabled="" type="radio">Water</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[b69f2d0c422938319cb0b00c5b946f99][]" id="gensym_5409c60c96dd7" value="a3adb9357e5e756aee6c74de34c423c3" checked="" disabled="" type="radio">Cement</td>
<td><span class="course-quiz-answer-correct" title="Correct" alt="Correct"><span class="icon-ok" alt="Correct"><span class="accessible-text-for-reader">Correct</span></span></span></td>
<td>3.00</td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[b69f2d0c422938319cb0b00c5b946f99][]" id="gensym_5409c60c97a8c" value="1e0e3cbc33e6d097aa518354a7bd6aed" disabled="" type="radio">BlastFurnaceSlag</td>
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
<h3 class="course-quiz-question-number">Question 4</h3>
<div dir="auto" class="course-quiz-question-text">
<p>Load the data on the number of visitors to the instructors blog from here: <br><a href="https://d396qusza40orc.cloudfront.net/predmachlearn/gaData.csv">https://d396qusza40orc.cloudfront.net/predmachlearn/gaData.csv</a></p>

<p>Using the commands:</p>

<pre>library(lubridate)  # For year() function below
dat = read.csv("~/Desktop/gaData.csv")
training = dat[year(dat$date) &lt; 2012,]
testing = dat[(year(dat$date)) &gt; 2011,]
tstrain = ts(training$visitsTumblr)
</pre>

Fit a model using the bats() function in the forecast package to the training time series. Then forecast this model for the remaining time points. For how many of the testing points is the true value within the 95% prediction interval bounds? </div>
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
<input dir="auto" class="course-quiz-input" name="answer[c5a378f6a03f5d96c212b2bd424615bc][]" id="gensym_5409c60c9b383" value="7eeb63729ef6bc1d4af2f3cbc9577b48" checked="" disabled="" type="radio">96%</td>
<td><span class="course-quiz-answer-correct" title="Correct" alt="Correct"><span class="icon-ok" alt="Correct"><span class="accessible-text-for-reader">Correct</span></span></span></td>
<td>3.00</td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[c5a378f6a03f5d96c212b2bd424615bc][]" id="gensym_5409c60c9c004" value="4e5aa97e692d944c683b323eebce4a48" disabled="" type="radio">95%</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[c5a378f6a03f5d96c212b2bd424615bc][]" id="gensym_5409c60c9c853" value="a3ba63c662882c838bad116915abd2e9" disabled="" type="radio">93%</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[c5a378f6a03f5d96c212b2bd424615bc][]" id="gensym_5409c60c9d06e" value="8c22c8218c4c1c809feba5f9a2cc8602" disabled="" type="radio">100%</td>
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
<h3 class="course-quiz-question-number">Question 5</h3>
<div dir="auto" class="course-quiz-question-text">Load the concrete data with the commands:

<pre>set.seed(3523)
library(AppliedPredictiveModeling)
data(concrete)
inTrain = createDataPartition(concrete$CompressiveStrength, p = 3/4)[[1]]
training = concrete[ inTrain,]
testing = concrete[-inTrain,]
</pre>

Set the seed to 325 and fit a support vector machine using the e1071 package to predict Compressive Strength using the default settings. Predict on the testing set. What is the RMSE? </div>
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
<input dir="auto" class="course-quiz-input" name="answer[de9664bfb00c2e5d35ca4c811f19acff][]" id="gensym_5409c60ca09c3" value="51b82b005fd6606a480c4c913a02523e" disabled="" type="radio">11543.39</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[de9664bfb00c2e5d35ca4c811f19acff][]" id="gensym_5409c60ca121d" value="a92efc299d7a02a03bf59e308e89aab3" disabled="" type="radio">45.09</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[de9664bfb00c2e5d35ca4c811f19acff][]" id="gensym_5409c60ca1a1c" value="4e4dc29e9eb12ac35b4134f42f363523" disabled="" type="radio">107.44</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[de9664bfb00c2e5d35ca4c811f19acff][]" id="gensym_5409c60ca2201" value="55f9e71e2f8800166a58b10f43efb6ac" checked="" disabled="" type="radio">6.72</td>
<td><span class="course-quiz-answer-correct" title="Correct" alt="Correct"><span class="icon-ok" alt="Correct"><span class="accessible-text-for-reader">Correct</span></span></span></td>
<td>3.00</td>
<td></td>
</tr>
<tr>
<td>Total</td>
<td></td>
<td>3.00 / 3.00</td>
<td>
