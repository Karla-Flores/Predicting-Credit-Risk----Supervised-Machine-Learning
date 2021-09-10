<h1>Predicting Credit-Risk--Supervised Machine Learning</h1>
<hr>
<h2>Background</h2>
<p align = 'justify'>In this assignment, a machine learning model will be built that attempts to predict whether a loan from LendingClub will become high risk or not.</p>
<p align = 'justify'>LendingClub is a peer-to-peer lending services company that allows individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. LendingClub offers their previous data through an API.</p>
<p align = 'justify'>You will be using this data to create machine learning models to classify the risk level of given loans. Specifically, you will be comparing the Logistic Regression model and Random Forest Classifier.</p>
<h2>Logistic Regression Model</h2>
<p align = 'justify'>
Training Score: 0.6509031198686371<br>
Testing Score: 0.5165886856656742
</p>
<img src='https://github.com/Karla-Flores/Predicting-Credit-Risk--Supervised-Machine-Learning/blob/main/Screenshots/classification_report_lr.png'>
<h2>Random Forest Classifier Model</h2>
<p align = 'justify'>
Training Score: 1.0<br>
Testing Score: 0.6433432581880051
</p>
<img src='https://github.com/Karla-Flores/Predicting-Credit-Risk--Supervised-Machine-Learning/blob/main/Screenshots/classification_report_rf.png'>
<h2>Logistic Regression Model - scale the data</h2>
<p align = 'justify'>
Training Score: 0.7078817733990148<br>
Testing Score: 0.767333049766057
</p>
<img src='https://github.com/Karla-Flores/Predicting-Credit-Risk--Supervised-Machine-Learning/blob/main/Screenshots/classification_report_lrsd.png'>
<h2>Random Forest Classifier Model - scale the data</h2>
<p align = 'justify'>
Training Score: 1.0<br>
Testing Score: 0.6420672054444917
</p>
<img src='https://github.com/Karla-Flores/Predicting-Credit-Risk--Supervised-Machine-Learning/blob/main/Screenshots/classification_report_rfsd.png'>
<h2>Summary</h2>
<ul>
<li>Logistic Regression fails to precede high-risk customers by allowing a recall of 0.30 due to false-negative cases.
<li>Random Forest Classifier has the perfect training score but the testing score of 0.64. This gap allows us to say that the model is overfitting.
<li>Random Forest Classifier model on the scaled data, in this model, the training score is one, and the testing score is 0.64. At the moment of observing, the recall is 0. It indicates that the model is overfitting and that the false negatives are high, leading to error.
<li>The logistic Regression model on the scaled data has a training score of 0.71 and a testing score of 0.76. With these results, we can say that although it is not a model that predicts perfectly, it is close to the reality you want to predict. This is verified with a recall of the high-risk clients of 0.72, where the false negatives go down.
</ul>
