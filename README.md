# Sentiment Analysis using Naive Bayes with Spark implementation

# Data
- We will work with Amazon Reviews. These reviews, made available by [Julian McAuley, UCSD], are raw qualitative (text) and quantitative (rating) evaluations of products by users. 
# Project Goal:
- We propose to use ML+NLP on positive/negative reviews to see what words carry out a positive/negative meaning for users.
- Process:
  - We will load Amazon Reviews from json into a dataframe
  - We will create a label (positive/negative) for each review and a dataset for ML
  - We will create features from a the text indexing pipeline using a TF-IDF approach
  - We will use Machine Learning (NaiveBayes classifier) to classify positive/negative reviews
  - We will interpret this classification in terms of positive/negative

