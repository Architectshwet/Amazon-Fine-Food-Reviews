# Amazon-Fine-Food-Reviews
The Amazon Fine Food Reviews dataset consists of 568,454 food reviews Amazon users left up to October 2012.

The purpose of this analysis is to make up a prediction model where we will be able to predict whether a recommendation is positive or negative. In this analysis, we will not focus on the Score, but only the positive/negative sentiment of the recommendation

## Procedure involved

The project is about the sentiment analysis on the text data using

1) nltk library which includes PorterStemmer(), word_tokenize() to change the unstructured text data to structured one
2) Use of countvectorizer(Convert a collection of text documents to a matrix of token counts), TfidfTransformer(to scale down the impact of tokens that occur very frequently in a given corpus and that are hence empirically less informative than features that occur in a small fraction of the training corpus) from sklearn library for feature extraction 
2) naive bayes (MultinomialNB, BernoulliNB)
3) logistic regression
4) use of metrics like roc curve, confision matrix and classification report to evaluate the machine learning model.
