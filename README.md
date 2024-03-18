# upGrad Data Science Bootcamp - Hackathon Project

## Loan Repayment Assessment

### Overview:
Welcome to the repository of my hackathon project for the upGrad Data Science Bootcamp. In this project, I worked on predicting loan defaulters using machine learning techniques.

### Problem Statement:
The goal of this project is to build and train a model that identifies whether a customer will repay or default from the loan dataset.

### Dataset:
The dataset contains 80000 records of various details about the borrower.

There is also a test_data with 20000 rows used for external evaluation of the model. The predictions of the test_data is stored in the test_results.csv file.

### Features:
The dataset contains 28 features, including 'addr_state', 'annual_inc', and 'emp_title', 'loan_amount', etc. The 'loan_status' column is the response variable, taking values of 'Defaulted' and 'Paid'.

### Approach:
- I used feature encoding to convert features to their proper formats.
- I used EDA to select certain appropriate columns from the dataset for the modeling process.
- I used machine learning techniques, including XGBoost Classifier and Random Forest Classifier, to build classification models for predicting loan defaulters.
- Due to the highly unbalanced nature of the dataset, I employed techniques like undersampling to balance the classes.
- I also used cross-validation and hyperparameter tuning to evaluate the performance of various models and pick the best one.

### Conclusion:
In conclusion, this project demonstrates the use of machine learning techniques to predict loan defaulters. By building a classification model, we can help banks and others lenders to identify potential defaulters and take appropriate action to minimize financial losses.


Feel free to explore the repository and reach out to me if you have any questions or feedback. Thank you for visiting!