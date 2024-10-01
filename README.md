# TT_Sprint17_FinalProject
This is a repository for TT Sprint 17 Project forecasting customer churn for a telecom operator. This project:

- Tested machine learning binary classification models, including logistic regression, random forest and gradient boosting (Light GBM) to identify recommended model for predicting customer churn. 
- Conducted exploratory data analysis, used feature engineering to create new variables for analysis, tested models on training, validation and test data, and identified gradient boosting as the most effective model.
- The model was built and tested on the Jupyter platform using Python language coding.
- The model was developed and tested by the data science student, and reviewed by a project reviewer.

**Results and Conclusions** The Gradient Boosting model (Light GBM, number rounds=100, GBDT boosting, binary objective, colsample_bytree=0.8, max_depth=3, num_leaves=31, subsample=0.8) was recommended to the company to use to identify customers that may leave, given the high AUC-ROC score (0.842 on test data) and similar accuracy score (0.808). 

Sample code and results for final test data:
![image](https://github.com/user-attachments/assets/6bef3ed1-98b0-4721-8190-40d334bf9a09)

This project uses customer data available here: https://practicum-content.s3.us-west-1.amazonaws.com/data-eng/datasets/final_provider.zip

To run the program, Python 3 (3.11.5) was used with the following libraries: pandas, numpy, matplotlib, sklearn, lightgbm.

To launch this project on a local machine, the data set should be accessible in the project folder, and python lanched with the above listed packages installed. 
