# Supervised Machine Learning and Credit Risk

## Overview
Use imbalanced-learn and scikit-learn libraries to build and evaluate unbalanced Credit Risk models.

## Languages and Programs used
- Python
- Jupyter Notebook
- Machine Learning 

## Analysis
In this sample there are a total of 68,817 loans. Of those loans there is a great imbalanced between loans that are low risk and high risk, with low risk loans having a population size of 68,470 and high risk loans having a population size of 347. In this challenge 4 tests were made using Naive Random Oversampling, SMOTE Oversampling, Undersampling, and Combination Sampling. In every single test the precision of the rates were identical, with high risk loans having a precision of 0.01 and low risk having a precision of 1. This shows that the model is extremely accurate in testing whether or not loans are high or low risk and does not have many or any false negatives and positives. The recalls (sensitivity) of the model are slightly different for the different tests. The sensitivity for high risk loans is 0.74 for the Naive Random Oversampling, 0.63 for the SMOTE Oversampling, 0.68 for the Undersampling, and 0.72 for the Combination Sampling. The sensitivity for low risk loans is 0.61 for the Naive Random Oversampling, 0.69 for the SMOTE Oversampling, 0.41 for the Undersampling, and 0.57 for the Combination Sampling. The trade off between sensitivity and recall is definitly seen in the f1 scores of the tests which can be expected. Overall this model is extremely precise which is important when giving loans out. I recommend that organizations use the SMOTE Oversampling method during analysis of this as this method has the highest precision and recall and can be confidently used to decided interest rates on loans.


