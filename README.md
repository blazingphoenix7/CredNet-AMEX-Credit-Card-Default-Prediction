# CredNet-AMEX-Default-Prediction-GRU-Model
 A RNN model for predicting credit card default using the American Express - Default Prediction dataset from Kaagle

 Please go ahead and toy around with the hyperparameters to improve model performance.
 Steps for replicating this project:
   1. Download dataset from: https://www.kaggle.com/competitions/amex-default-prediction?rvi=1
   2. Download the compressed version of the dataset from: https://www.kaggle.com/datasets/odins0n/amex-parquet
   3. Run the 'american-express-eda.ipynb' jupyter notebook. This file performs Exploratory Data Analysis and will help you understand the dataset better.
   4. Run the 'split_train.ipynb' jupyter notebook. This file will split your training dataset into smaller files. The training dataset is of 16 GB while the testing dataset is of       33 GB. Doing so, will prevent kernel crashing due to memory limits.
   5. Run the 'AMEX_model_train.ipynb' jupyter notebook. This file will train a GRU model on the dataset. Feel toy around with the various hyperparameters to improve model               performance.


