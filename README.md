# Credit-Card-Default-Prediction
This is a Machine Learning Classification project which aims to bridge the gap of uncertainty by utilizing the data driven approach by using past data of customers in conjunction with Machine Learning to predict whether or not a customer will default on their credit card.

Major steps involved are:

a) Collecting the data(in csv format)       
b) Data Cleaning- Checking for zero and nulls and then replace them with their respective values(Mean,median ,mode)           
c) Handling the missing values  
d) Handling the outliers -using Boxplot , standardization and normalization , IQR    
e) Applied ML algorithms to building the model               
f) Hyper parameter Tuning - Parameters passed in ML algorithms in order to improve the accuracy like n_estimator, random_state

Algorithms used to building the model are: 

a) Gaussian Naive Bayes
b) Logistic Regression 
c) K-NN
d) Decision Tree
e) Random Forest

After doing all the train /CV test , the datset gave us the highest F1- score is scaled with gaussian Naive Bayes taking lead at 0.518.
Therefore ,Gaussian Naive Bayes was chosen as the model to classify the defaulters.
