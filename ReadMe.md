# Spam Message Checker

In this notebook, I am going to build a classifier that performs Spam Message Checking.
Following are the steps to achieve required objective.

### a)  first read the  sample dataset which is in csv file which has spam/ham messages
### b) This dataset has the following count of ham and spam text. 
count of ham = 4825 count of spam = 747
### c) lets replace ham with 0 and spam with 1
### d) we split the dataset into test and train datasets
### e) Then apply the following
	1) MultinomialNB from sklearn.naive_bayes
	2) Guassian Naive Bayes
	3) DecisionTreeClassifier
	4) Random Forest classifier
### f) Compare the results of these classifiers
In our example: Final Accuracy is 
DecisionTree = 97.040 %
Random Forest = 97.49 % 
GaussianNB = 99.28 % 
MultinomialNB = 99.28 %

### g) store in file and then load file and test the examples
The pickle module implements binary protocols for serializing and de-serializing a Python object structure.
### h) Analyse output and examine input 
 the required results:[0 0 1 1 0 0 1] according to input messages
