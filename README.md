# Tweets Sentiment Classification
Twitter is one of the popular Social Networking Service (SNS) platforms and people express their opinion 
with text called tweets. The main purpose of this project is to analyse tweets’ sentiment by using machine 
learning and deep learning algorithms such as Multinomial Naïve Bayes (NB) and Bidirectional Encoder 
Representations from Transformers (BERT). 

In this project, the text dataset is from twitter which includes the review of airlines and its sentiment. To be 
specific, the figure below shown, the text dataset given consists of the tweet’ id, tweets and its sentiment. 
Especially, sentiment is a categorical class having 3 classes such as negative, neutral and positive. Also, 
tweets consist of not only pure text but also tags such as airline’s name and links.

<p align="center">
 <img src="https://user-images.githubusercontent.com/82886152/219145646-a4127f21-692e-4f54-bcd4-841d56fa1c0b.png">
</p>

For preprocessing of text, removing unnecessary words, balancing the dataset and one-hot encoding is implemented. Especially, the different method is applied for two main algorithms. For Multinomial NB, the Bag of Words (BOW) approach and Term Frequency-Inverse Document Frequency (TF-IDF) is performed. For BERT, tokenization is applied before training. Lastly, all the prediction is evaluated by precision, recall, F1-score and confusion matrix.

The details can be found in the report uploaded in the repository.
