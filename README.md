# Autotagging-of-Question-and-Answers-of-Stackoverflow-Questions
This is a multi label classification text classification problem. The task is to predict the tags (i,e., keywords, topics, summaries), given only the question text and its title. The dataset contains content from disparate stack exchange sites, containing a mix of both technical and no-technical questions.

## Dataset
The dataset is downloaded from kaggle competition: Facebook Recruiting III -Keyword Extraction. 
The link for the datasets download is: https://www.kaggle.com/c/3539/download-all

### Steps for multilabel text classification problem:
1. Importing Libraries
2. Loading Data: The datasets must be converted into .feather format using <b> pandas.feather </b> so as to fast read and write operations on data.
3. Data Preprocessing:-
  a. Removing data duplicacy
  b. Removing HTML Tags
  c. Removing punctuation and special symbols
  d. Tokenization and Stemming
4. Using Tfvectorizer, convert all tags into one hot encoding for multilabel classification
5. Making machine learning model
6. Deployment of machine learning model

#### Word Cloud
![Word CLoud](/Images/word cloud.png)

#### Frequency of top 20 tags
![Frequency of top 20 tags](/Images/Frequency of top 20 tags.png)
