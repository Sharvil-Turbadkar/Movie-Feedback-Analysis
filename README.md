# Movie-Feedback-Analysis
Conducted a Case study on Rotten Tomato Movie Reviews

## Heroku App Link:https://movie-feedback-analysis.herokuapp.com/

## Domain:Movie Industry
<img src= "/images/707_poster .jpg" title='Project Poster'>
                                                                  
## Client:Rotten Tomato
## Abstract
I synergized alongside my teammates to develop a personalized movie recommender system using Item Based Collaborative Filtering model and proposed an explanation as to why a user has been recommended a particular movie. 

## Business Goals:
1. Which attributes will affect the likelihood of watching a movie the most?
2. Do critic and audience views match?
3. Which writers, directors, and studios have the strongest polarity?
4. Quantifying polarity across time to gauge market effects.

## EDA
While pre-processing data we faced the problem of multi-collinearity as a result we had to remove columns with near to zero variance using PCA. We also performed MICE imputation for imputing missing values. 
One Hot Encoding was done to convert categorical variables into numeric variables   
## Feature Importance 
We deployed ensemble models for feature selection to assess which factors led to a higher similarity between movies using random forest and gradient boosting. Audience Rating and Audeicne 
## Sentimental Analysis
We also used naïve Bayes to classify user sentiments using VADER tokenizer for perfecting media text classification.  
## Prediction
To evaluate a movie’s success, we used logistic regression and ensemble models to make a binary classification and prescribe movies that not only had a high similarity but also which were predicted to be a success. 
## Insights 
1. Actor-director duos are beneficial for both parties as they reap a higher success and are thus more likely to be recommended
2. Contrary to popular beliefs audience and critic reviews are very alike 
3. Average movie ratings have reached an all time low at the turn of the Millenium and have seen a steady increase since 
4. Studios that make R Rated movies are likely to flop 
