# Advanced Regression Assignment
> Project submitted by Ramandeep Mehra <br>
>
> This project uses Regularisation to build a polynomial regression model for the prediction of the actual value of the prospective properties and decide whether to invest in them or not.
> - Which variables are significant in predicting the price of a house
> - How well the variables describe the price of a house
>
> The project contains:
> - Data Analysis notebook
> - The data set `train.csv`
> - The data dictionary `datainfo.txt`
> - Answers to the Subjective Questions in pdf format `SubjectiveQuestions.pdf`


## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#contact)


  
## General Information


- **General information:** 
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario

- **Background:** 
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. 

- **Business problem:**
Aim is to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Assignment Steps performed in the notebook

## Data visualisations
- perform EDA to understand various variables
- check correlation between the variables 

## Data preparation

- Importing and understading the data.
- Missing value treatment and outlier analysis
- Exploratory data analysis to find out the inference about the data and its correlation with the target variables.
- Tranformation of the target variable to handle the data skewness.
- Data preprocession like Label encoding and ceration of dummies.
- Test train split and Feature scaling
- Data modelling using RFE to identify the top 10 variables.
- Ridge and Lasso Regression to find the top feature variables and finding the optimal alpha value

## Data modelling and evaluation
- create linear regression model with no Regularisation
- create models using Ridge and Lasso Regularisation
- create additional models model using mixed approach (RFE & VIF/p-Value) and apply Ridge and lasso Regularisation
- report the final model



## Conclusions
Please see the notebook for more detailed insights.
1. `GrLivArea` is by far the most important predictor
2. The top variables are intuitive.
3. Lasso is the chosen model for the final model, because it creates a simple model with the top features.





## Technologies Used

![Python](https://img.shields.io/badge/Python-3.10-informational?style=flat&logoColor=white&color=2bbc8a)
![NumPy](https://img.shields.io/badge/NumPy-1.21.5-informational?style=flat&logoColor=white&color=2bbc8a)
![Pandas](https://img.shields.io/badge/Pandas-1.3.5-informational?style=flat&logoColor=white&color=2bbc8a)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5.1-informational?style=flat&logoColor=white&color=2bbc8a)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11.2-informational?style=flat&logoColor=white&color=2bbc8a)
![sklearn](https://img.shields.io/badge/Sklearn-1.0.2-informational?style=flat&logoColor=white&color=2bbc8a)
![statsmodels](https://img.shields.io/badge/statsmodels-0.13.1-informational?style=flat&logoColor=white&color=2bbc8a)
![scipy](https://img.shields.io/badge/scipy-1.8.0-informational?style=flat&logoColor=white&color=2bbc8a)



## Contact
Created by [Ramandeep Mehra](https://github.com/Ramandeepmehra) - feel free to contact me! <br>
Student at UpGrad: *upGrad and IIITB Machine Learning & AI Program-Dec 2023* <br>
© 2024


