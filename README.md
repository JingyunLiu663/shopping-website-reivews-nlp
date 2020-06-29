# Natural Language Processing (NLP) for Shopping Reviews

In this project, we will use the NLP method to analyze a shopping website dataset involving the reviews written by customers.

## Files in this repository 
1. Women Clothing E-Commerce Reviews.csv: Raw Data used for this NLP analysis demonstration. <br/>
    Title, Review Text, and Rating are the objective comments given by each customer.<br/>
    Recommended IND represents whether the customer is willing to recommend the product to others, i.e., the sentiment.<br/>
    
2. shopping_reviews_nlp.ipynb: This is the Jupyter Notebook used for natural language processing <br/>

## Pre-Processing
As general steps, we first need to tokenize the text and transform all the words to lower-case. We then remove all the stop words, puncuations, and stem the document. Finally, we vectorize all the words in a document with tf-idf weighted average.

## Apply Topic Modelling to Reduce Dimensionally 
Apply Latent Dirichlet Allocation (LDA) and Latent Semantic Analysis (LSA) to convert documents from bag-of-words into bag-of-topics (Dimensionality Reduction.

Use cross validation to select an appropriate number of topics for the whole dataset.

## Logistic Regression to Predict Sentiment of Reviews
Predict sentiment (Recommended / Not recommended) of reviews using their bag-of-topics features by fitting a logistic regression model.

Calculate the prediction error, which is defined as the percentage of incorrect predictions.
