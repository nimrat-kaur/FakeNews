# Fake News Prediction

Fake news's simple meaning is to incorporate information that leads people to the wrong path. Nowadays fake news spreading like water and people share this information without verifying it. This is often done to further or impose certain ideas and is often achieved with political agendas.

In this project, we are using some Machine Learning and Natural language processing libraries like NLTK, re (Regular Expression), Scikit Learn.

## Dataset
Link:
https://drive.google.com/file/d/1GJp__f6UuA9MDN9iRKJ8dtTx8RthwcLG/view?usp=sharing

train.csv: Training dataset with the following attributes:
id-unique id for a news article;
title-the title of a news article;
author-author of the news article;
text-the text of the article;
label-a label that marks the article as potentially unreliable
(1: unreliable
0: reliable)

test.csv: A testing training dataset with all the same attributes at train.csv without the label.

submit.csv: A sample submission that you can use.

## Natural Language Processing
Machine learning data only works with numerical features so we have to convert text data into numerical columns. So we have to preprocess the text and that is called natural language processing.
In-text preprocess we are cleaning our text by stemming, removing stopwords, removing special symbols and numbers, etc. After cleaning the data we have to feed this text data into a vectorizer which will convert this text data into numerical features.

## Machine Learning Techniques Implemented:
1] Logistic Regression
2] Multinomial Naive Bayes
3] Support Vector Machine

## Classification Metrics:
To check how well our model we use some metrics to find the accuracy of our model. There are many types of classification metrics available in Scikit learn:
- Confusion Matrix
- Accuracy Score
- Precision
- Recall
- F1-Score

##### Best Performing model is that of SVM which gives 97% accuracy
