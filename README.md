# NLP_Examples
 
## Sentiment Analysis/Classifier and Flask Deployment

This project uses an open source data set of Airline tweets. The data set has the tweet already classified into positive, neutral, and negative along with the confidence level for each classification. 

In the example here I set up a simple NLP sentiment analysis example, cleaning the data and running the classification through a random forest. The code is then modified to allow for scoring one text input. 

Finally a chunk of code uses Flask to deploy the model and provide real time sentiment analysis of input text. 

Resources:
- https://towardsdatascience.com/deploying-models-to-flask-fb62155ca2c4
- https://github.com/jeremyrchow/Harassment-Classifier-App

## Document Topic Extraction

This project uses an open source dataset from Sklearn: from sklearn.datasets import fetch_20newsgroups. The data set consists of new articles that are already classified into twenty different topics. 

Text preprocessing includes stemming and removing stop words. Choosing our own number of topics, the LDA model uses unsupervised clustering to identify the topic of each document.

Resources:
- https://github.com/priya-dwivedi/Deep-Learning/blob/master/topic_modeling/LDA_Newsgroup.ipynb
- https://towardsdatascience.com/applying-machine-learning-to-classify-an-unsupervised-text-document-e7bb6265f52
- https://www.analyticsvidhya.com/blog/2016/08/beginners-guide-to-topic-modeling-in-python/


## Unsupervised Text Clustering/Classification

This project uses an open source data set of Jeopardy questions to do topic clustering. 

Resources: 
- https://towardsdatascience.com/applying-machine-learning-to-classify-an-unsupervised-text-document-e7bb6265f52
- https://medium.com/mlrecipies/document-classification-using-machine-learning-f1dfb1171935

## Semi-Supervised LDA Document Topic Classification

Resources:
- https://github.com/vi3k6i5/GuidedLDA/blob/master/examples/example_seeded_lda.py
- https://www.freecodecamp.org/news/how-we-changed-unsupervised-lda-to-semi-supervised-guidedlda-e36a95f3a164/

## Future Projects

Resources for further consideration
- Real-time sentiment analysis in a chat application: https://pdfs.semanticscholar.org/03ba/177161cf908b4530b72ba0cf34f7e0a6c48a.pdf
- https://medium.com/jatana/unsupervised-text-summarization-using-sentence-embeddings-adb15ce83db1
- http://mccormickml.com/2016/04/19/word2vec-tutorial-the-skip-gram-model/
- https://towardsdatascience.com/conversational-sentiment-analysis-52eabd20155b
- https://towardsdatascience.com/best-practices-for-nlp-classification-in-tensorflow-2-0-a5a3d43b7b73
- https://towardsdatascience.com/transfer-learning-in-nlp-f5035cc3f62f
