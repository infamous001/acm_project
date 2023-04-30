# acm_project
ACM selection project

In this project i have worked on Iris Flower Dataset
task in hand is to predict the class of Iris flower ->Iris-setosa,Iris-versicolor,Iris-virginica based on given project

I have submitted 2 colab notebooks 

1> In first notebook I have implemented 3 models ->logistic regression, kernel svm and random forest classifier. in this notebook I have implemented different models using sklearn library

2> In second notebook I have implemented logisitc regression from scratch. Logistic Regression used for Biniary classfication but to used it in in muticlass classification what I have done is I have OneHotEncoded target y and then have applied logistic regression seperately for all three classes ypred1 ypred2 yprd3 , then made a final list of predicted classes by comparing probabilities from ypred1 ypred2 ypred3 to check which class has highest probability and added that class as predicted class for the given features
finally I got 88.6 accuracy by the above approach
