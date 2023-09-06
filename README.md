# Spam-and-Not-Spam-Classifier-Natural-Language-Processing-
A machine learning model to classify messages as Spam or Not spam using the library nltk.

Introduction:
1.In this project, I have tried to design a machine learning model that can classify mails,messages into spams or Not-spams categories.
2.Using the library nltk,we can clean out data so that the words which really effect the target parameters are left in the messages or mails.
3.Cleaning of data and then converting the string data into float values is the most crucial part of this project.

Contents:
1. A SMSSPAMCLASSIFICATION csv file is provided and we need to fetch data from this file using pandas.
2. Then using the nltk library we will remove the common words that are present in each of the messages/mails, so that the words that actually affect our target variables are left.
3. After cleaning the data we will convert this string data into float values so that the converted data can be feed into our machine learning classification model.
4. We can choose various classification models like SVM, Naive Bayes etc.
5. After feeding the model we will create a confusion matrix and classification report.
6.The results of our model can be checked using the confusion matrix and classification report.


Conclusion:
1.From the confusion matrix we can deduce that our model is working fine.And accuracy is above 90%.


