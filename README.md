# Detectionofcyberbullying
Detection of Cyber bullying Using Machine Learning Approach

Abstract: Recently the usage of social media platforms has increased exponentially, people share information with each other easily using technologies. The lives of people have improved from various perspectives, but this has come with a high price on the growth of various cyber-crime activities. Cyberbullying is one of the major issues which is faced by most of the children and teenagers. This could increase the risk of anxiety, sleep deprivation, and depression to a great extent and can also hamper their mental health and lifestyle. Detection of such activities on the basis of various text analysis and Natural language processing could help us tackle them. This paper focuses on, available data sources, different feature extraction and different multi-label classifiers used in the detection of cyberbullying. The aim of the project is to improve the detection of cyberbullying content so that youngsters could use social media network freely. With the help of text analytics, meaningful information about the text could be obtained and natural language processing helps us to interact with the computer and human language.  Combining both the technologies with the help of a machine learning algorithm can help us in predicting different cyberbullying attacks.

Keywords: Text Analytic, Natural language processing, Text processing, Machine learning, and Data mining.

Data Used: The data used in prediction of cyberbullying was downloaded from kaggle. 
Link for download: https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data

File Description: The data consist of large number of Wikipedia comments which consist of pre-defined  labels.   The  types  of  labels  are  toxic,  severetoxic,  obscene,  threat,  insult  andidentityhate.

Following were the files which where used:

1.train.csv:- this is the files which contains comments with thier respected binarylabels.  The binary labels are represented by ’0’ and ’1’ for not toxic and toxic.

2.test.csv:- consist of comments which is use for prediction.

3.testlabels:- labels used for test data, values -1 indicates it was not used for scoring.

Analysis of the data:-
EDA is a part of techniques which help us in getting more insite and get to learn about the data. It is a way of visualizing, summarizing and interpreting the information that is hidden in rows and column formats.

Data Cleaning and Trasformation:-
Preparing the data for analysis by removing and modifying data that is incorrect, andimproperly  formatted.  Incorrect  and  inconsistent  data  can  lead  to  false  conclusion,therefore good result depends upon how well the data is been cleaned.The  basis  cleaning  task used are transform  the  data  by removing  special  characters,  converting  the  text  into  lowercase,  removal  of  noisy  dataand so on,stop-ord removal,stemming of words. 

Feature Extraction: 
1) TF_IDF
2) N-Gram
3) Sequence Padding

Model Implementation: 
The following were the classifers used: 
1) Gradient boosting classifier
2) Linear Support Vector CLassifier
3) Logistic regression
4) Decision tree

All the above steps have been explain and implemented in the latest.ipynb file.
