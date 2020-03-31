# Movie Classifier

[Slideshow](https://docs.google.com/presentation/d/1sC_LHiYveaq3vvDj5L8S7d0OH5hgnVQEjt75xUpMHqg/edit?usp=sharing)

# Project Goals

  Use metrics from IMDb to determine if a movie will be considered good by Rotten Tomatoes
  
  On RT, 61 and up is considered at least "good" while 60 and below is considered "average" or worse
  
# Data

  Scraped data for every film from 2010 on from IMDb, then used API call on OMDb to get additional data on each movie
  
  Checked for normality and multicollinearity and nothing stood out as abnormal
  
# Modeling Phase

  Tested seven models: Logistic Regression, K-nearest Neighbors, Decision Tree, Random Forest. Gradient Boost, Adaboost, and xG Boost
  
  Final Model used is xG Boost
    Precision - 77%
    
    Recall - 74%
    
    Accuracy - 80%
    
    F1 Score - 75%
    
