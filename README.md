# Phishing or not phishing ?

METHODOLOGY USED:
I have used various Binary Classification ML algorithms to find weather a website is an phishing website or not based on 30 independent variables.It is noted that there was no missing value present in the data. The target variable in the dataset consist of two classes which are as follows

• 1 indicates the website is a phishing website.

• 0 indicates the website is a non-phishing website.

Also the target variables was fairly balanced enough with 55.46% phishing websites and 44.54% non-phishing websites.

The dataset was divided into two parts: X and Y(i.e, the part of the data with out the target variable and the target variable itself).
Then the dataset was divided into x and y train datas, x and y test datas.


I used different unsupervised ML algorithms to attain the goal with the help of following python libraries:

• SKLEARN

• PANDAS

• NUMPY

• MATPLOTLIB

The following classification models were used for training, testing and validation:

• LOGISTIC REGRESSION

• SUPPORT VECTOR CLASSIFIER WITH SIGMOID KERNAL

• SUPPORT VECTOR CLASSIFIER WITH RBF KERNAL

• DECISION TREE

• RANDOM FOREST CLASSIFIER

• KNN

OBSERVATIONS:

Out of all the models Random Forest classifier has the highest validation accuracy of 97%. The accuracy obtained by this model on the train set is 99.6%. I choose this model not only because of its pretty good accuracy score, This model also have the highest F1 score compared all other models I used.

You can compare the validation accuracy and the F1 scores of all the algorithms used from the screenshot uploaded on this repository.






