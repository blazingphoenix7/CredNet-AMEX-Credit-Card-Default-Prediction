# CredNet-AMEX-Credit-Card-Default-Prediction-GRU-Model
CredNet - A GRU Model for predicting credit card default on the American Express Dataset.

This repository contains an implementation of a Recurrent Neural Network (RNN) model designed to predict credit card default using the American Express - Default Prediction dataset from Kaggle. The goal of the model is to effectively identify potential credit card defaults and assist in risk assessment.

To replicate this project, follow these steps:

1. Download the dataset from Kaggle: The dataset can be accessed from the Kaggle competition page at https://www.kaggle.com/competitions/amex-default-prediction?rvi=1. Additionally, you can download the compressed version of the dataset from https://www.kaggle.com/datasets/odins0n/amex-parquet.

2. Exploratory Data Analysis: Execute the 'american-express-eda.ipynb' Jupyter notebook. This notebook performs Exploratory Data Analysis (EDA) and provides insights into the dataset, helping you gain a better understanding of its structure and features.

3. Prepare the Training Data: Run the 'split_train.ipynb' Jupyter notebook. This file is responsible for splitting the large training dataset (16 GB) into smaller files, which prevents kernel crashes due to memory limitations while processing the data. You can use the same file for splitting the large testing dataset (33 GB) into smaller files.

4. Train the GRU Model: Use the 'AMEX_model_train.ipynb' Jupyter notebook to train the GRU model on the dataset. Feel free to experiment with various hyperparameters to optimize the model's performance and achieve the best possible results.

By following these steps and customizing the model's hyperparameters, you can explore and fine-tune the GRU model for credit card default prediction, contributing to enhanced credit risk assessment in the financial domain. Feel free to use, modify, and build upon this repository for further research and applications. 


