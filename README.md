# NLP-projects
# Sarcasm Detection with Neural Networks

## DATASET
News Headlines Dataset for Sarcasm Detection
Data Source: https://www.kaggle.com/rmisra/news-headlines-dataset-for-sarcasmdetection?
select=Sarcasm_Headlines_Dataset.json

## Content
Each record consists of three attributes:
 
 is_sarcastic: 1 if the record is sarcastic otherwise 0
 headline: the headline of the news article
 article_link: link to the original news article. Useful in collecting supplementary data
 
In this project, a binary classification model was designed that processes individual word with
natural language processing methodologies to predict the presence of sarcasm in News
Headlines.
## NLP Terminologies
 Tokenization is essentially splitting a phrase, sentence, paragraph, or an entire text
document into smaller units, such as individual words or terms. Each of these smaller units
are called tokens.

When we pre-process the text data, not all the input sentences are of same length, some of
the sentences are longer or shorter. The solution to this problem of different lengths of
inputs is padding with zero to a fixed length.
padding=’post’: add the zeros at the end of the sequence to make the samples of the same
size.

Word embedding is the collective name for a set of language modeling and feature learning
techniques in natural language processing (NLP) where words or phrases from the
vocabulary are mapped to vectors of real numbers. A word embedding is a learned
representation for text where words that have the same meaning have a similar
representation.
