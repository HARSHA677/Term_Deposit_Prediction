# Term Deposit (FixedDeposit) Prediction -Banking Case Study

# Problem Statement:
A major bank in Middle East came to NeoStats with help in analysing its current customer base and its marketing campaign. It wants to understand which customers are most
likely to take a term deposit (fixed deposit), and then send this list to their call centre.

# Objective:
1. Data Analysis & Visualization:

2. Modelling: Term Deposit and Related Variables:Identify variables strongly related to Term Deposit. Discuss your approach when the variable is categorical. Which tests or metrics will you
employ?

4. Predictive Model Building:Train a prediction model of your choice to estimate the probability that a customer will opt for a termdeposit. Adhere to an 80:20 train:test split. Report and present the
model's performance metrics on both the train and test datasets.

5. Model Improvement Strategies: Discuss potential methods or approaches to enhance model performance. This could include feature engineering, different algorithms, or refining the data
preprocessing steps.

# Results
Performance of Random Forest Classifier and XG boost was better than others. 

Without feature selection, Outlier removal and upsampling reduced the problem of overfitting was detected.

Able to remove (not completely) overfitting in Random Forest.

Model with outlier removal and manual encoding performs better when
compared with all of the metrics for XGboost.

Thus, in this the removal of the balance column is a better solution than
imputating it.
O
versampling to balance out the data sample w,e can see a significant increase
in the model accuracy score and recall score of Guassian NB, XG and Random
forest. Thus, in the case of oversampling best choice to consider.
