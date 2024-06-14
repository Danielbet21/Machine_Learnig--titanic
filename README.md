**Languages**

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

**🖥️ Libraries**

![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Seaborn Badge](https://img.shields.io/badge/Seaborn-4c72b0.svg?style=for-the-badge&logo=Seaborn&logoColor=white)

## Project Overview
This project involves predicting the survival of passengers on the Titanic using machine learning models. The goal is to analyze various factors influencing survival rates and to generate a submission file for validation against a test dataset.

## File Descriptions
train.csv: Training dataset containing labeled data for model training.
test.csv: Test dataset containing passenger information for which survival predictions are to be made.
submission.csv: The final submission file with predicted survival outcomes for each passenger in the test dataset.
## Usage
Preprocessing: Load and preprocess the training data to handle missing values, encode categorical variables, and normalize features.
Model Training: Train the machine learning model using the processed training dataset.
Prediction: Apply the trained model to the test dataset to generate survival predictions.
Submission: Create a CSV file with PassengerId and Survived columns and submit for evaluation.
## Submission File Format
PassengerId: Unique identifier for each passenger.
Survived: Predicted survival status (1 for survived, 0 for did not survive).
