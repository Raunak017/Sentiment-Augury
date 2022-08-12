# Sentiment-Augury
Performing Sentiment Analysis on a given dataset using Naive Bayes.

Dataset Link : https://www.kaggle.com/c/sentiment-analysis-on-movie-reviews/data?select=train.tsv.zip

The dataset is a movie review and I have trained a model to predict the outcome for a
movie review. The dataset has been taken from Kaggle.com. The link is provided
above. The movie reviews are under the column named ‘Phrases’ and the classes are
labelled under the column named ‘Sentiment’.


The dataset is comprised of tab-separated files with phrases from the Rotten
tomatoes dataset. The train/test split has been preserved for the purposes of
benchmarking, but the sentences have been shuffled from their original order. Each
Sentence has been parsed into many phrases by the Stanford parser. Each phrase has
a PhraseId. Each sentence has a SentenceId. Phrases that are repeated (such as
short/common words) are only included once in the data.
train.tsv contains the phrases and their associated sentiment labels.

There is also a SentenceId in order to track which phrases belong to a single sentence.
I then converted the train.tsv file to a csv file.
