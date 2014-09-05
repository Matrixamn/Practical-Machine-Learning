Feedback — Quiz 3  </span>
  
  <a class="coursera-reporter-link" title="Click here if you're experiencing technical problems or found errors in the course materials." target="_blank" href="https://class.coursera.org/predmachlearn-005/help/quizzes?url=https%3A%2F%2Fclass.coursera.org%2Fpredmachlearn-005%2Fquiz%2Ffeedback%3Fsubmission_id%3D558">
     Help
  </a>
</h2>


<a data-coursera-admin-helpwidget-link="" rel="help" href="https://class.coursera.org/mooc/help/quiz" title="Quiz documentation" style="display:none;">Learn more</a>




                <div class="alert alert-success"> Thank you. Your submission for this quiz was received. </div>
    


<p class="course-quiz-feedback"> You submitted this quiz on <strong>Tue  2 Sep 2014  9:01 PM ART</strong>. You got a score of <strong>15.00</strong> out of <strong>15.00</strong>. </p>


            <form method="post" id="quiz_form" accept-charset="UTF-8">
    
    
    
    <div class="course-quiz-question-body">
<h3 class="course-quiz-question-number">Question 1</h3>
<div dir="auto" class="course-quiz-question-text">Load the cell segmentation data from the AppliedPredictiveModeling package using the commands: 
<pre>library(AppliedPredictiveModeling)
data(segmentationOriginal)
library(caret)
</pre>

1. Subset the data to a training set and testing set based on the Case variable in the data set. <br>
2. Set the seed to 125 and fit a CART model with the rpart method using all predictor variables and default caret settings. <br>
3. In the final model what would be the final model prediction for cases with the following variable values:<br>
a. TotalIntench2 = 23,000; FiberWidthCh1 = 10; PerimStatusCh1=2 <br>
b. TotalIntench2 = 50,000; FiberWidthCh1 = 10;VarIntenCh4 = 100 <br>
c. TotalIntench2 = 57,000; FiberWidthCh1 = 8;VarIntenCh4 = 100 <br>
d. FiberWidthCh1 = 8;VarIntenCh4 = 100; PerimStatusCh1=2 <br>
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
<input dir="auto" class="course-quiz-input" name="answer[6f5c05593f440bc0716455598da1ffcc][]" id="gensym_5409c5f4f393c" value="398070c52a11305c58dc30dd125f3e80" disabled="" type="radio">a. PS <br>
b. WS <br>
c. PS<br>
d. WS <br>
</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[6f5c05593f440bc0716455598da1ffcc][]" id="gensym_5409c5f50019e" value="c71bd9b00f29ac894faabe31c04edb9a" disabled="" type="radio">a. Not possible to predict <br>
b. WS <br>
c. PS<br>
d. PS <br>
</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[6f5c05593f440bc0716455598da1ffcc][]" id="gensym_5409c5f500b9c" value="0b8933a7fab437a2405f9d8ac56d2a05" disabled="" type="radio">a. PS <br>
b. Not possible to predict <br>
c. PS<br>
d. WS <br>
</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[6f5c05593f440bc0716455598da1ffcc][]" id="gensym_5409c5f50169b" value="e7114aca6c63148faabb0c1b086435ba" checked="" disabled="" type="radio">a. PS <br>
b. WS <br>
c. PS<br>
d. Not possible to predict <br>
</td>
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
<h3 class="course-quiz-question-number">Question 2</h3>
<div dir="auto" class="course-quiz-question-text">If K is small in a K-fold cross validation is the bias in the estimate of out-of-sample (test set) accuracy smaller or bigger? If K is small is the variance in the estimate of out-of-sample (test set) accuracy smaller or bigger. Is K large or small in leave one out cross validation? </div>
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
<input dir="auto" class="course-quiz-input" name="answer[e1dd1790449b45be430518262fe11909][]" id="gensym_5409c5f506435" value="63388029f03c2cca075a6d4972e1307f" disabled="" type="radio">The bias is larger and the variance is smaller. Under leave one out cross validation K is equal to one.</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[e1dd1790449b45be430518262fe11909][]" id="gensym_5409c5f506d14" value="9126fd4843376d51263f8cf91d8f6c2a" checked="" disabled="" type="radio">The bias is larger and the variance is smaller. Under leave one out cross validation K is equal to the sample size. </td>
<td><span class="course-quiz-answer-correct" title="Correct" alt="Correct"><span class="icon-ok" alt="Correct"><span class="accessible-text-for-reader">Correct</span></span></span></td>
<td>3.00</td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[e1dd1790449b45be430518262fe11909][]" id="gensym_5409c5f507a30" value="87f3e5418947c81a91536f60eced2eff" disabled="" type="radio">The bias is smaller and the variance is bigger. Under leave one out cross validation K is equal to one.</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[e1dd1790449b45be430518262fe11909][]" id="gensym_5409c5f508372" value="568f736c16611f5e665c6678a958b399" disabled="" type="radio">The bias is smaller and the variance is smaller. Under leave one out cross validation K is equal to the sample size. </td>
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
<div dir="auto" class="course-quiz-question-text">Load the olive oil data using the commands:

<pre><code>
library(pgmm)
data(olive)
olive = olive[,-1]
</code></pre>

(NOTE: If you have trouble installing the <b>pgmm</b> package, you can download the <code>olive</code> dataset here: <a href="https://d396qusza40orc.cloudfront.net/predmachlearn/data/olive_data.zip">olive_data.zip</a>. After unzipping the archive, you can load the file using the <code>load()</code> function in R.)

<p>These data contain information on 572 different Italian olive oils from multiple regions in Italy. Fit a classification tree where Area is the outcome variable. Then predict the value of area for the following data frame using the tree command with all defaults</p>

<pre><code>
newdata = as.data.frame(t(colMeans(olive)))
 </code></pre>

What is the resulting prediction? Is the resulting prediction strange? Why or why not?</div>
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
<input dir="auto" class="course-quiz-input" name="answer[d3eb4222f5f5d297ba5699b03a16caa8][]" id="gensym_5409c5f50bf5c" value="1f614e303a3186ea88f445cd52c09443" checked="" disabled="" type="radio">2.875. It is strange because Area should be a qualitative variable - but tree is reporting the average value of Area as a numeric variable in the leaf predicted for newdata</td>
<td><span class="course-quiz-answer-correct" title="Correct" alt="Correct"><span class="icon-ok" alt="Correct"><span class="accessible-text-for-reader">Correct</span></span></span></td>
<td>3.00</td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[d3eb4222f5f5d297ba5699b03a16caa8][]" id="gensym_5409c5f50cce8" value="1aa79b66a77588464cd8a9453927acdb" disabled="" type="radio">0.005291005 0 0.994709 0 0 0 0 0 0. There is no reason why the result is strange. </td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[d3eb4222f5f5d297ba5699b03a16caa8][]" id="gensym_5409c5f50d6ce" value="90b529f0cd82269b8d66d58f2dfc93ca" disabled="" type="radio">4.59965. There is no reason why the result is strange.</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[d3eb4222f5f5d297ba5699b03a16caa8][]" id="gensym_5409c5f50e033" value="78d0bd733368ff061a191da0e1573820" disabled="" type="radio">0.005291005 0 0.994709 0 0 0 0 0 0. The result is strange because Area is a numeric variable and we should get the average within each leaf. </td>
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
<div dir="auto" class="course-quiz-question-text">Load the South Africa Heart Disease Data and create training and test sets with the following code:

<pre><code>library(ElemStatLearn)
data(SAheart)
set.seed(8484)
train = sample(1:dim(SAheart)[1],size=dim(SAheart)[1]/2,replace=F)
trainSA = SAheart[train,]
testSA = SAheart[-train,]
 </code></pre>

Then set the seed to 13234 and fit a logistic regression model  (method="glm", be sure to specify family="binomial") with Coronary Heart Disease (chd) as the outcome and age at onset, current alcohol consumption, obesity levels, cumulative tabacco, type-A behavior, and low density lipoprotein cholesterol as predictors. Calculate the misclassification rate for your model using this function and a prediction on the "response" scale: 

<pre><code> 
missClass = function(values,prediction){sum(((prediction &gt; 0.5)*1) != values)/length(values)}
</code></pre> 

What is the misclassification rate on the training set? What is the misclassification rate on the test set? 
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
<input dir="auto" class="course-quiz-input" name="answer[44aeb4ca08b383a98a91fc1c18a19c27][]" id="gensym_5409c5f511a95" value="125b4bf8254db49b3522114cafb1e58d" disabled="" type="radio">Test Set Misclassification: 0.43 <br>
Training Set: 0.31</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[44aeb4ca08b383a98a91fc1c18a19c27][]" id="gensym_5409c5f512311" value="132fa24305576ccefb96cad7791f1625" disabled="" type="radio">Test Set Misclassification: 0.32 <br>
Training Set: 0.30</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[44aeb4ca08b383a98a91fc1c18a19c27][]" id="gensym_5409c5f512c38" value="46d62b04b6f7d11a68350e515e30408a" disabled="" type="radio">Test Set Misclassification: 0.35 <br>
Training Set: 0.31</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[44aeb4ca08b383a98a91fc1c18a19c27][]" id="gensym_5409c5f5134bf" value="f87bff5554bd8d75b1ce41e49559dc96" checked="" disabled="" type="radio">Test Set Misclassification: 0.31 <br>
Training Set: 0.27</td>
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
<h3 class="course-quiz-question-number">Question 5</h3>
<div dir="auto" class="course-quiz-question-text">Load the vowel.train and vowel.test data sets:

<pre><code>library(ElemStatLearn)
data(vowel.train)
data(vowel.test) 
</code></pre>

Set the variable y to be a factor variable in both the training and test set. Then set the seed to 33833. Fit a random forest predictor relating the factor variable y to the remaining variables. Read about variable importance in random forests here: <a href="http://www.stat.berkeley.edu/~breiman/RandomForests/cc_home.htm#ooberr"> http://www.stat.berkeley.edu/~breiman/RandomForests/cc_home.htm#ooberr</a> The caret package uses by defualt the Gini importance. 

 Calculate the variable importance using the varImp function in the caret package. What is the order of variable importance?</div>
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
<input dir="auto" class="course-quiz-input" name="answer[6154e834ebb33db777f1b4f57de8c2c3][]" id="gensym_5409c5f51755f" value="016146414f6e315cab0d12ffcbc4a2f7" checked="" disabled="" type="radio">The order of the variables is:<br>
x.2, x.1, x.5, x.6, x.8, x.4, x.9, x.3, x.7,x.10<br>
</td>
<td><span class="course-quiz-answer-correct" title="Correct" alt="Correct"><span class="icon-ok" alt="Correct"><span class="accessible-text-for-reader">Correct</span></span></span></td>
<td>3.00</td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[6154e834ebb33db777f1b4f57de8c2c3][]" id="gensym_5409c5f5183be" value="a409cd5be344d8d2010eb852151f6156" disabled="" type="radio">The order of the variables is:<br>
x.10, x.7, x.5, x.6, x.8, x.4, x.9, x.3, x.1,x.2<br>
</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[6154e834ebb33db777f1b4f57de8c2c3][]" id="gensym_5409c5f518cb4" value="a08abbc00c8600685f64dc987aa9d93a" disabled="" type="radio">The order of the variables is:<br>
x.1, x.2, x.3, x.8, x.6, x.4, x.5, x.9, x.7,x.10<br>
</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr data-randomizable-option="data-randomizable-option">
<td class="course-quiz-student-answer" dir="auto">
<input dir="auto" class="course-quiz-input" name="answer[6154e834ebb33db777f1b4f57de8c2c3][]" id="gensym_5409c5f519851" value="0c215d79bf374228efa4d6f76e1734f3" disabled="" type="radio">The order of the variables is:<br>
x.10, x.7, x.9, x.5, x.8, x.4, x.6, x.3, x.1,x.2<br>
</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>Total</td>
<td></td>
<td>3.00 / 3.00</td>
<td>
