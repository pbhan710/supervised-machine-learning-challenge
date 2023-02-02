# supervised-machine-learning-challenge
Repository of Jupyter notebook and data for the supervised machine learning challenge in the GT Data Science and Analytics bootcamp.

## Background
Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market.

You will be using this data to create machine learning models to classify the risk level of given loans. Specifically, you will be comparing the Logistic Regression model and Random Forest Classifier.

## Requirements
### Retrieve the Data (5 points)
- Import the lending_data.csv file as a Pandas dataframe (3 points)
- Confirm that the import was successful by displaying the dataframe (2 points)
### Predict Model Performance (15 points)
- Make a prediction on which model will perform better on the data (5 points)
- Justify the prediction with information about the models (10 points)
### Split the Data into Training and Testing Sets (30 points)
- Create the features DataFrame, X, by removing the loan_status column (10 points)
- Create y, the labels set, by using the loan_status column (10 points)
- Split the data into training and testing datasets by using the train_test_split function (10 points)
### Create, Fit and Compare Models (50 points)
- Create and train a Logistic Regression model (10 points)
- Score the Logistic Regression model (10 points)
- Create and train a Random Forest Classifier model (10 points)
- Score a Random Forest Classifier model (10 points)
- State which model performed better (5 points)
- Compare the actual model performance with your predictions (5 points)

## References
Loan Approval Dataset (2022). Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.