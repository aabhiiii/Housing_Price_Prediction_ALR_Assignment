# Housing Price Prediction ALR Assignment
> We are trying to determine the features that helps in predicting the price of a house, and How well those variables describe the price of a house.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- In this case study we are provided with the data of sale of houses in Australia
- A lot of features regarding the salesprice and and other features of houses are provided as a dataset.
- The dataset is about the past sale of houses in australia, so it included the information like LotArea, LandContour, Utilities, HouseStyle, YearBuilt, Foundation etc for a sales price of the house.
- Our objective is to find what all features/variables which are relevent in predicting the price of a house and fit a linear regression model(using Ridge and lasso regularisation) to predict house price.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- We have got good R- Square value of 0.59 for test data which is similar to training data for both ridge and Lasso regularisation
- Residuals are normally distribured and variance of the residuals is constant across predictions

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
##Recommendations
- Below are the list of important predictors and interpretaion using their coefficient value
- LandContour
- Utilities
- MasVnrType
- ExterQual
- Foundation
- HeatingQC
- PavedDrive

## Technologies Used
- Python - version 3.7.13
- Pandas - version 1.3.5
- Matplotlib - version 3.2.2
- Seaborn - version 0.11.2
- statsmodels - version 0.10.2
- sklearn
- Google Colab

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by the US-based housing company named Surprise Housing
- This project was based on the Advance Linear Regression module in ML EPGP program in Upgrad


## Contact
Created by [@aabhiiii] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->