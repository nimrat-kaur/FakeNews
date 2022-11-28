# Fake News Detection

Fake news's simple meaning is to incorporate information that leads people to the wrong path.Nowadays fake news spreading like water and people share this information without verifying it. This is often done to further or impose certain ideas and is often achieved with political agendas.

In this project, we are using some machine learning and Natural language processing libraries like NLTK, re (Regular Expression), Scikit Learn.

Natural Language Processing
Machine learning data only works with numerical features so we have to convert text data into numerical columns. So we have to preprocess the text and that is called natural language processing.
In-text preprocess we are cleaning our text by stemming, removing stopwords, removing special symbols and numbers, etc. After cleaning the data we have to feed this text data into a vectorizer which will convert this text data into numerical features.

Machine Learning Techniques Implemented:
1] Logistic Regression
2] Multinomial Naive Bayes
3] Support Vector Machine

Classification Metrics:
To check how well our model we use some metrics to find the accuracy of our model. There are many types of classification metrics available in Scikit learn:
- Confusion Matrix
- Accuracy Score
- Precision
- Recall
- F1-Score

Best Performing model is that of SVM which gives 97% accuracy
