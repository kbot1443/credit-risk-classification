# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
    - In this analysis, the goal was to build machine learning models to predict loan outcomes, specifically identifying healthy loans (0) and high-risk loans (1). The purpose of this analysis was to assist in making informed lending decisions by leveraging financial data.
    
* Explain what financial information the data was on, and what you needed to predict.
    - The dataset contained various financial variables, including loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. 
    
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
    - The target variable was the loan outcome, with two classes: 0 for healthy loans and 1 for high-risk loans.

* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
    - Two machine learning models were used - Logistic Regression and Random Forest. Logistic Regression is a linear model, while Random Forest is an ensemble method.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Balanced Accuracy Score: 0.95
  * Precision for class 0 (healthy loans): 1.00
  * Recall for class 0 (healthy loans): 0.99
  * Precision for class 1 (high-risk loans): 0.85
  * Recall for class 1 (high-risk loans): 0.91



* Machine Learning Model 2:
    Balanced Accuracy Score: 0.997
    Precision for class 0 (healthy loans): 1
    Recall for class 0 (healthy loans): 1
    Precision for class 1 (high-risk loans): 1
    Recall for class 1 (high-risk loans): 1

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? ) - they are both equally as important.

    Both machine learning models, Logistic Regression and Random Forest, achieved outstanding results in terms of balanced accuracy, precision, and recall, indicating their effectiveness in classifying loans. The balanced accuracy score was exceptionally high for both models, suggesting that they perform well on both healthy and high-risk loans.

    The choice between the two models may depend on various factors:

    If interpretability and simplicity are essential, Logistic Regression is a strong choice, as it provides clear coefficients for feature importance.
    If we prioritize slightly higher model complexity for potentially better performance, Random Forest is a good option.
    In this context, where the goal is to make lending decisions and accurately identify high-risk loans, both models perform exceptionally well. 