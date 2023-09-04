# CredNet - Credit Card Default Prediction with GRU

CredNet is a deep learning project that leverages a Gated Recurrent Unit (GRU) [a Recurrent Neural Network mechanism) model to predict credit card defaults using the American Express - Default Prediction dataset from Kaggle. The primary aim of this project is to develop an effective tool for identifying potential credit card defaults, assisting in risk assessment, and contributing to the field of financial analytics.

## Dataset

The dataset used in this project can be obtained from the Kaggle competition page: [American Express - Default Prediction](https://www.kaggle.com/competitions/amex-default-prediction?rvi=1). Alternatively, you can download the compressed dataset directly from [this link](https://www.kaggle.com/datasets/odins0n/amex-parquet).

## Getting Started

To replicate and contribute to this project, follow these steps:

1. Clone the repository to your local machine
2. Set up your Python environment and install the required libraries by running 'pip install -r requirements.txt' in your terminal.
3. **Exploratory Data Analysis (EDA)**: Execute the 'american-express-eda.ipynb' Jupyter notebook. This notebook performs Exploratory Data Analysis (EDA), offering valuable insights into the dataset's structure and features. Understanding the data is crucial before diving into model development.
4. **Data Preparation**: Use the 'split_train.ipynb' Jupyter notebook to split the large training dataset (16 GB) into smaller, manageable files. This step helps prevent memory-related issues during data processing. You can apply the same approach to the extensive testing dataset (33 GB).
5. **Training the GRU Model**: Utilize the 'AMEX_model_train.ipynb' Jupyter notebook to train the GRU model on the dataset. Feel free to experiment with various hyperparameters to fine-tune the model's performance and achieve optimal results.

## Contributing

We welcome contributions to this project! Whether you want to improve the model's accuracy, optimize code efficiency, or enhance the project's documentation, your contributions are valuable. Please open an issue or submit a pull request to get involved. Feel free to use this repository as a starting point for your own research, and together, we can contribute to enhanced credit risk assessment in the financial domain.

## License

This project is open-source and available under the MIT License. You are free to use, modify, and build upon the codebase for your research and applications.
