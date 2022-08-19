# Starbucks Offer Recommendation System

## Introduction

This project is to mainly assess the effectiveness of a marketing 
campaign deployed by Starbucks on certain demographic groups of customers.

## Directory

Starbuck_Campaign
|- README.md
|- Starbucks_Capstone_notebook.ipynb
|- data
    | - portfolio.json
    | - profile.json
    | - transcript.json
|- .ipynb_checkpoints
|- Capstone_Project-Report.pdf

## Tools and Softwares

The project was implemented in Jupyter Notebooks using Python with libraries like 
Pandas, Numpy and Sklearn.

To access notebook using terminal :

```
jupyter notebook Starbucks_Capstone_notebook.ipynb

```

### Business Problem Statements

The following questions were considered in analysis the business problem:

- Which types of customers are more likely to respond to an offer ? 
- Is there any incremental impact from the marketing campaign ?

### Data

The three input data files portfolio.json, profile.json, transcript.json are 
stored in the data folders. 


### Exploratory Analysis and Data Preprocessing

Column splitting, missing data operations and features engineering to provide better 
clarity in business contexts. Further, each offer and transaction are merged with the
demographic data of the customers. The final dataset shows the interactions between 
the customers and the offers provided with the net spent and rewards claimed. 


### Model Fitting

Data are trained on four different models (Random Forest Classifier, Gradient Boosting, 
Light Gradient Boosting, Extreme Gradient Boosting) and selected for the 
best based on accuracy scores. The model is to be improved via Grid Search.


### Correlation Analysis

The data is also used to map the univariate correlation between key demographic features. 
The fitted model can be used to predict the likely outcome of hit rate based on the 
recommendation from the correlation to confirm the recommendation.


### Analysis and Justification

To test the result of the hit rate, the t-test could be use to compare the difference 
in sales performance for the target segment between transactions between non-offer 
receiving  and offer receiving groups.  


### 5. Report and Github

A full analysis report is included, Capstone_Project-Report.pdf.  
The github repository has been stored in ( https://github.com/showall/starbucks_reward_program.git)