# Starbucks customers and offers data analysis
This reposoitory is for the capstone project of Udacity's data science nano degree, utilizing Starbucks data

The associated blog post can be found [here](https://alkalaji.github.io/starbucks-data-analysis-final/)

## Introduction
In this notebooks we analyze the data provided by Starbucks simulating customer behavior in response to offers through their mobile app. We follow CRISP-DM to analyze the data and gain insights into how customers interact with those offers. We will also answer different questions that are important to the business.

## Motivation
Offers are an important tool for engaging your customers, promoting new offerings, or increasing loyalty. Therefore it is very important to understand:
- How different customers interact with different offers
- How those offers change customer behavior and spending
- Being able to target the right customer with the right offer

## File structure
* _Starbucks_Capstone_Project.ipynp_: is the notebook file containing the analysis
* _data_ folder: contains the json files and soe itnermediary generated datasets
* _model_ fodler: contains the trained model

## Data
The data used in this project is provided as part of the project.

__Please note that the data file transcript.json could not be uploaded due to its size. Therefore, it must be acquired from Udacity's workspace and saved in 'data' folder__

The data is provided in the following three files:
- __portfolio.json__ - containing offer ids and meta data about each offer (duration, type, etc.)
- __profile.json__ - demographic data for each customer
- __transcript.json__ - records for transactions, offers received, offers viewed, and offers completed

## Requirements
__Please note that the data file transcript.json could not be uploaded due to its size. Therefore, it must be acquired from Udacity's workspace and saved in 'data' folder__

The packages required to run this project are the following:
- pandas
- numpy
- seaborn
- matplotlib
- sklearn
- plotly
- plotly-orca (to install: conda install -c plotly plotly-orca)
- statsmodels
- tqdm
