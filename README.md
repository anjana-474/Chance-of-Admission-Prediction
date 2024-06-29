# Chance of Admission Prediction Using Linear Regression

This project demonstrates how to predict the chance of admission for graduate applicants using linear regression. 

# Dataset
The dataset contains the following columns:

- Serial No: Identifier for each applicant.
- GRE Score: Graduate Record Examination score (out of 340).
- TOEFL Score: Test of English as a Foreign Language score (out of 120).
- University Rating: Rating of the university (1 to 5).
- SOP: Strength of the Statement of Purpose (1 to 5).
- LOR: Strength of the Letter of Recommendation (1 to 5).
- CGPA: Undergraduate GPA (on a scale of 10).
- Research: Research experience (1 if the applicant has research experience, 0 otherwise).
- Chance of Admit: Probability of admission (0 to 1).

# Library Packages

- pandas
- scikit-learn
- numpy
- matplotlib

# Steps

**Data Loading and Preprocessing:**
- Load the dataset into a Pandas DataFrame.
- Check for any missing or inconsistent data and handle it accordingly.

**Feature Selection:**
- Select relevant features for the prediction model, excluding Serial No.

**Data Splitting:**
- Split the data into training and testing sets (commonly 80% training and 20% testing).

**Model Training:**
- Use linear regression from scikit-learn to train the model on the training data.

**Model Evaluation:**
- Predict the chance of admission on the testing set.
- Evaluate the model using metrics such as Mean Absolute Error (MAE) and Mean Squared Error (MSE)

# Conclusion

This project provides a basic implementation of linear regression for predicting the chance of admission based on various factors. The results help understand the importance of each factor in the admission process. Further tuning and exploration can be done to improve the model’s accuracy.
