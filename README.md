

# Task 3: Implementation of Text Mining and Sentiment Analysis 

 
OBJECTIVE AND SUB TASK DETAILS OF TASK3:
 
# Part One is Text Mining: 
 
Training a Classification Model for Drugs Review dataset using Naive 
Bayes MultinomialNB Classifier to predict the sentiments of Drugs reviews.
Here, Data pre-processing involves cleaning, Tokenizing the 
words,Stop word removal and Applying stemming technique.Finally, Generating the Term Frequency 
Matrix using CountVectorizer on the 'processed_combinedReviews' column.
This Matrix is set as 'X' parameter and 'score_label' is set as Y for the model training 
before Splitting the dataset to training and testing data.
Also, the Target Class imbalance is addressed after splitting the data



# Part Two is a Sentiment Analysis using NLTK Python Library:

The aim of Part two of Task3 is to Perform the Sentiment Analysis using “nltk”(Natural 
Language ToolKit) python package to compute, analyze & evaluate the sentiment metrics of 
Drugs reviewsusing the “SentimentIntensityAnalyzer” of the nltk.sentiment.vader package 
and storing the resulting Scores of Compounds, Negative, Neutral and Positive in 
separate columns of the same DataFrame. 
Output of this subtask is stored in a CSV file named as "drugsreview_df.csv" for 
further investigation on Sentiment score intensity of each Drug’s reviews.

# Part Three: Sentiment Analysis using Textblob Python Library: 

The aim of Part Three of Task3 is to Perform the Sentiment Analysis using textblob python 
library to compute, analyze & evaluate the Sentiment Polarity on the “combinedReviews” 
column of the “drugsreview_df” DataFrame. 
However, the calculated Sentiment Polarity DataFrame being saved into a CSV file 
and named as "Sentiment_Polarity.csv" for further investigation on each Drug.

# PYTHON CODE FILES FOR TASK3:
One Jupyter notebook file: Komala_textmining_SA.ipynb


# DATASET FILE FOR TASK3:
Drug_review_uci.csv
1 CSV file downloaded from UCI Machine Learning Repository
URL: https://archive.ics.uci.edu/dataset/461/drug+review+dataset+druglib+com  
