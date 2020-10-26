inventory-management

Objective:
To manage the inventory of different products and
To understand how to work with imbalanced dataset.

Dataset:
198917 rows, 14 columns
contains both historical sales data AND active inventory

Goal: 
We have a to building a binary classifier which gives us a list of product ID which need to retained in the inventory or list of products that need to be removed

Code description:
EDA: use matplotlib and seaborn to create different charts/diagrams to show distribution within the dataset
Data modeling: convert data type, split the historical and active state data, create training and testing variables, balanced the data by using SMOTE
1. Random Forest
2. Logistic Regression
3. XGBoost
create validiation dataset, plot confusion matrix and classification report to show classification results, compute ROC curve and AUC for each class. 
