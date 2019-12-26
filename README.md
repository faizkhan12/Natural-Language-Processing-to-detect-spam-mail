# Natural-Language-Processing-to-detect-spam-mail
This repository contains the process of Natural Language Processing which converts the given string into numerical data and then classify the data set using one of Machine Learning Algorithm. Here I have used Naive Bais Classifier to detect if messages are ham or spam.

# Algorithm and Tools Used 
1. import nltk(For natural Language processing)
2. import pandas(For dataframe)
3. imoort matplotlib,seaplot(For data visualization)
4. from sklearn.naive_byes import MultinomialNB

# Datasets
The datasets obtained are from <a href = "https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection">Ucl datasets</a>. The datset is located at /Dataset folder . This Dataset contains about 5000 mail sms consisting of either ham or spam types

# TF-IDF
TF-IDF stands for *term frequency-inverse document frequency*, and the tf-idf weight is a weight often used in information retrieval and text mining. This weight is a statistical measure used to evaluate how important a word is to a document in a collection or corpus. The importance increases proportionally to the number of times a word appears in the document but is offset by the frequency of the word in the corpus. Variations of the tf-idf weighting scheme are often used by search engines as a central tool in scoring and ranking a document's relevance given a user query.

# Process Involved
1. First convert a tokens into Vector using Vectorization using bag-of-words model
2. Count how many time a word occur(term frequency)
3. Weight the counts,frequesnt tokens will have lower weight(Inverse Document Frequesny)
4. Normalize the vectors to Unit Length, to abstract from the original text length(12 norm)
5. After all text data converted to numerical, we need to split or train-test data to get an accuracy

# Result 

![Alt text](result.png?raw=true "predicted values" )
