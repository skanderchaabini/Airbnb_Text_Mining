# Airbnb_Text_Mining


This project aims to build a Natural Language Processing model to predict whether an Airbnb
property listing will be unlisted or not in the next quarter.  
  
To help answer the question “Which type of listings are more likely to be unlisted in the next
quarter?”, we were given 4 files, 2 of them with historical data and labeled if a listing was
unlisted this quarter, where 'unlisted' means listings that were removed from the Airbnb
platform.  
  
train.xlsx - This file contains information about the Airbnb listings. Each row represents a
listing and contains the description of that listing and a description of the host.  
  
train_reviews.xlsx - This file contains the reviews made in Airbnb about each listing in our
dataset. Each row represents a review/comment and it has an index column that
corresponds to the listing index number.  
  
The test data files(test.xlsx, test_reviews.xlsx) possess similar information for unlabeled
listings regarding next quarter.    

We will build an NLP pipeline that analyzes the text data to identify features correlated with
unlisted listings. We will preprocess the text, using techniques used in class, such as,
removing punctuation, stop words and tokenization. We will perform sentiment analysis on
the review comments to identify negative sentiments and issues that may lead to delisting.
The pipeline aims to determine which factors will contribute to make a listing more likely to
be removed.
