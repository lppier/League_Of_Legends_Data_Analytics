## League_Of_Legends_Data_Analytics

Summary : We were able to attain 71.3% pre-game accuracy as to whether a team would win against another team. This accuracy goes up marginally as the match progresses as more data is attained. 

Data Analytics on League of Legends dataset from Kaggle : https://www.kaggle.com/chuckephron/leagueoflegends
We assumed the role of investigating odds of a certain team winning in an e-sports situation at certain time points. (before the game, 5 minutes into the game, 10 minutes into the game and halfway through the game). 

This was a group project in data mining following the CRISP-DM methodology :
- Business understanding
- Data understanding
- Data preparation
- Modeling
- Evaluation
- Deployment

Personally, I did some data pre-processing, creating new predictors out of exisiting features. I also ran the models in R to investigate the accuracy at various time slices. For the report, I worked on the interpretation and evaluation of the models' metrics. eg. ROC curve, confusion matrix, etc.

## Team Members
Anurag Chatterjee                     
Bhujbal Vaibhav Shivaji              
Charles Thomas De Leau            
Lim Pier                                       
Liu Theodorus David Leonardi  
Tsan Yee Soon                             

## Data Preparation
Some work in R was done to transform data from the original fields to fields that we felt were valuable as predictors for modeling. eg. win efficiency

## Modeling
We investgated random forests, xgboost, neural networks, decision trees and logistic regression over the course of this project. The eventual model chosen was logistic regression.

The R Markdown files (cleaned up) are included. This repository is the final one that contains the submitted findings.
Working repository during the project : https://github.com/lppier/KE5107_LeagueofLegends
