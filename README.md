Project Overview:

This project uses Machine Learning (Support Vector Machine Classifier) to predict whether a user will purchase a product based on social network advertisement data.

Columns Explanation:

User ID – Unique ID for each user (not useful for prediction)

Gender – Male or Female

Age – Age of the user

EstimatedSalary – Approximate annual salary

Purchased – Target column (0 = Not Purchased, 1 = Purchased)

Imported Libraries:

import pandas as pd ->Use: Pandas is used to read the CSV file and work with data in table form (DataFrame)

from sklearn.model_selection import train_test_split ->Use: Splits the dataset into training data and testing data.

 from sklearn.linear_model import LogisticRegression->Use: Imports the LogisticRegression to build the prediction model.

 from sklearn.metrics import confusion_matrix ->Checking model accuracy beyond just accuracy score

from sklearn.metrics import classification_report -> to get the report of accuracy,recall,precision,f1_score

import pickle ->Use: to save the whole model
