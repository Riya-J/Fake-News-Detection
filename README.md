# Fake-News-Detection
This project aims at classifying news as real or fake. It was implemented using the following steps:
1. Assigning labels to the data
2. Data Visualization
3. Removing stopwords, punctuations from the dataset and converting the text into lowercase.
4. Applying TF-IDF vectorisation on the news articles
5. Applying Logistic Regression on the dataset 

# About the Dataset
The two datasets for real and fake news were taken from Kaggle. It contains 21417 true news articles and 23502 fake news articles. Labels were then assigned to the datasets ( 1 - Real, 0 - Fake) and the datasets were concatenated and shuffled before training it. The subjects of the articles include News, Politics, Us News, Middle East News and Left-news. 
