# SentimentAnalysis-1
Sentiment analysis is performed on amazon review data
This code is for extracting sentiment from amazon review data set provided by UCSD.

Dataset used - [Amazon review data - UCSD dataset](https://jmcauley.ucsd.edu/data/amazon/)

Dataset Citations

Ups and downs: Modeling the visual evolution of fashion trends with one-class collaborative filtering
R. He, J. McAuley
WWW, 2016
[pdf](http://cseweb.ucsd.edu/~jmcauley/pdfs/www16a.pdf)

PROCEDURE FOLLOWED
- Sentiment is not directly provided in the data set, so polarity is obtained for each review using text blob library
- Dataset is divided into test and train 
- Following are the classifiers used for the analysis purpose
  1. Naive Bayes
  2. Decision Tree
  3. Adaboost Classifier
  4. Random Classifier
  5. Multi Layer Perceptron
  
  RESULT
  MLP outperfomed other classifiers
  
  
  
