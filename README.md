# ML Logistic Regression
Logistic Regression is a Machine Learning classification algorithm that is used to predict the probability of a 
categorical dependent variable. In logistic regression, the dependent variable is a binary variable that contains 
data coded as 1 (yes, success, etc.) or 0 (no, failure, etc.). In other words, the logistic regression 
model predicts P(Y=1) as a function of X.

## Objective:
The purpose of this assignment is to apply Logistic regression to classify a binary value or categorical value  . 
and also discuss why we chose that attribute/feature and what we are trying to learn from the classification.

## Dataset Overview:
Dataset: https://www.kaggle.com/shrutimehta/zomato-restaurants-data 

## What we  Achieved ?
Based on the Different features in the dataset using Logistic Regression , we are able  to get 
if  the restaurant rating is "Excellent"  or  "Average". 

## What Data Preparation we did :

1) Load the data using the Pandas library.
2) Considered only the  columns in the Dataset , which can impact the rating. 
3) The Dataset has different sets of  target values for Rating like (‘Excellent’, ‘Good’, ‘Average’ , 'Very Good '). 
    Since we would like to implement a binary classification algorithm, we decided to have the rows with 
    target value Excellent and Average
4) Format the column headers as they have spaces. ( why formatting ? To apply functions on the columns headers ) 
5) Rating is in the  text Format , so updated to Binary Values 0 and 1.
6) Convert required  features  like 'Table booking','Has Online delivery to numerical  values
7) Data Analysis - Use Library like  pairplot Which gives fair idea bout how data is 
   distributed or organized

## Accuracy score: 
## 0.96 

##  Sigmoid Function:

Logistic regression algorithm also uses a linear equation with independent predictors to predict a value. 
We want to have the output of the algorithm to be class variable in our case which is Rating
as  i.e 0-Average, 1-Excellent. To squeeze the predicted value between 0 and 1, we use the sigmoid function.
![Alt text](/images/Sigmoid.png)


 ##  Confusion Matrix:
 The confusion matrix  result tells us correct and incorrect predictions.
 ![Alt text](/images/ConfusionMatrix.png)



## Conclusion
 Logistic regression  can be used for both binary and multivariate classification tasks. With the current solution we used  binary classification task, which gives the rating of restaurent which can be "Excellent" or "Average".

## Team

|Name | Detail|
|---|---|
| University | [SJSU UNIVERSITY]( http://www.sjsu.edu/) |
| Team | Code Busters|
|Professor| Mr.Arsanjani|
|Team | [Harini Balakrishnan](https://www.linkedin.com/in/harini-balakrishnan/) 
|Team | [Ravi Katta](https://www.linkedin.com/in/ravi-shanker-katta/)  
|Team | [Anushri Srinath Aithal](https://www.linkedin.com/in/anushri-aithal/) 
|Team | [Sunder Thyagarajan](https://www.linkedin.com/in/sunderthyagarajan/)
