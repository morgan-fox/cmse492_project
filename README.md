# 2024-2025 Premier League Season Prediction 

## Overview 
This project will incorperate a machine learning model that predicts the outcomes for the 2024-2025 Premier League season based on historical match data found on kaggle. The dataset will be used to train models to predict match outcomes, as well as evaluate the model’s performance. The goal is to create a predictive model that accurately estimates team standings and other outcomes throughout the season. 

## Project Objectives 
- Understanding different trends in Premier League data to identify key factors that have influence on match outcomes.
- Utilizing feature engineering to improve model prediction accuracy.
- Train and test for multiple models in order to predict match outcomes, optimizing for low errors and high variability (r^2).
- Evaluate each model to assess performance and make imporvemets as needed. 
- Using best performing model to predict the outcomes of matches in the 2024-2025 season.
- Provide visualizations into model predictions and performance.

## Project Structure
```plaintext
├── data/                     
│   └── Premier_League.csv    
├── notebooks/                
├── src/                      
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── train_model.py
│   └── evaluate_model.py
├── README.md               
└── requirements.txt 
```

## Setup 
- Clone Repository using git clone https://github.com/morgan-fox/cmse492_project.git and cd cmse492_project
- Install nececssary dependencies using pip install -r requirements.txt
- Download the Premier_League.csv dataset located in the data folder

## Requirements 
Required Libraries:
- Numpy
- Pandas
- Seaborn
- Scikit-learn
- Matplotlib


## Updated Results 
Best performing model:
- XGBoost

Predicted League Standings
![image](https://github.com/user-attachments/assets/105db2a6-659a-4f59-a80e-1aa4e59d607f)
