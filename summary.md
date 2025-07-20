**Summary of the Loan Prediction project**

1. Data analysis:
- Loan amount and income distribution:  
![Income Distribution](/img/income_distribution.png "Income Distribution")     
![Loan Distribution](/img/loan_distribution.png "Loan Distribution")     
- The categorical variable analysis to look at the chances of getting a loan based a valid credit history. 
(Useful to find an important feature or check the logistic regression in the initial step)

![Credit Histry](/img/credit_histry.png "Credit Histry")

  
2. Data cleaning & preprocessing:

- Fixing the missing values.
Instead of eliminating the extreme data, using the log transformation to reduce the significance of the extreme data.

![Log Transformation](/img/log_transformation.png "Log Transformation")

(The result of log transformation for the loan amount distribution)

3. Build a classification model and assessing performance:

- Test with different classification models (logistic regression, decision tree, random forest), different feature values and different parameters to see the performance and the accuracy of the prediction.
 
    - Logistic regression
  ![Logistic regression](/img/accuracy_logistic_regression.png "Logistic regression")
    - Decision tree with different selections of the feature values
![Decision Tree](/img/accuracy_decision_tree.png "accuracy_decision_tree")
    - Random forest with all the features values
    ![Random Forest](/img/accuracy_random_forest.png "Random Forest")
