# IBM-Watson-RecomendationEngine

## Introduction

For this project I analyzed the interactions that users have with articles on the IBM Watson Studio platform, and tried to make recommendations on new articles they will like. 

This project is divided into 4 main parts:
#### Exploratory Data Analysis
  This part is for data exploration.
#### Rank Based Recommendations
  Finds the most popular articles based on the most interactions. These are then the articles we might recommend to new users
#### User-User Based Collaborative Filtering
  Looks at users that are similar in terms of the items they have interacted with. These items could then be recommended to similar users.
#### Matrix Factorization
  Builds on recommendations using machine lerning model. Using the matrix decomposition, we can predict new articles an individual might interact with .

## Dependencies
pandas
numpy
matplotlib
sklearn
