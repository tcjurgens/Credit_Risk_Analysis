# Credit_Risk_Analysis

## Overview
For this assignment, we used all resources at our disposal and the provided LoanStats_2019Q1.csv in order to help identify if individuals may be low or high risk status for a credit loan.

Using credit card credit dataset from LendingClub, we over and under-sampled the data using RandomOverSampler, SMOTE, and the ClusterCentroids algorithms. We then used a combination of over and undersampling using the SMOTEENN algorithm. 

The next task completed was to compare two machine learning models that reduce bias to predict credit risk. These algorithms being BalancedRandomForestClassifier and EasyEnsembleClassifier.

## Results
- Naive Random Oversampling
<img width="850" alt="Screen Shot 2021-10-14 at 8 58 07 PM" src="https://user-images.githubusercontent.com/86446641/137415503-44a33574-1ed4-46b9-ac35-74bb050ce14a.png">

Above, we have a 65.34% accuracy score, 1% precision high risk, 100% precision low risk, 63% recall high-risk, and 66% recall low-risk. Other data also shown in the chart.

- SMOTE Oversampling
<img width="942" alt="Screen Shot 2021-10-14 at 8 58 39 PM" src="https://user-images.githubusercontent.com/86446641/137415547-bad7549c-eb6b-4d71-b960-de690c85c887.png">

Above, we have a 65.12% accuracy score, 1% precision high risk, 100% precision low risk, 64% recall high-risk, and 66% recall low-risk. Other data also shown in the chart.

- Undersampling
<img width="938" alt="Screen Shot 2021-10-14 at 8 58 56 PM" src="https://user-images.githubusercontent.com/86446641/137415571-ab34cdea-2ff2-4e4c-9995-0bb51cc5fc33.png">

Above, we have a 52.94% accuracy score, 1% precision high risk, 100% precision low risk, 61% recall high-risk, and 45% recall low-risk. Other data also shown in the chart.

- Combinatin (Over and Under) Sampling
<img width="915" alt="Screen Shot 2021-10-14 at 8 59 36 PM" src="https://user-images.githubusercontent.com/86446641/137415611-8d90a48e-6c1a-458c-b01a-2befb30ca60c.png">

Above, we have a 61.85% accuracy score, 1% precision high risk, 100% precision low risk, 69% recall high-risk, and 55% recall low-risk. Other data also shown in the chart.

- Balanced Random Forest Classifier
<img width="989" alt="Screen Shot 2021-10-14 at 9 01 01 PM" src="https://user-images.githubusercontent.com/86446641/137415709-c1164027-157d-4ee4-a38e-61aa921331c5.png">

Above, we have a 83.02% accuracy score, 4% precision high risk, 100% precision low risk, 76% recall high-risk, and 90% recall low-risk. Other data also shown in the chart.

- Easy Ensemble AdaBoost Classifier
<img width="868" alt="Screen Shot 2021-10-14 at 9 01 49 PM" src="https://user-images.githubusercontent.com/86446641/137415764-15f7cb05-2bfd-475d-9141-78c312ea19b5.png">

Above, we have a 92.54% accuracy score, 7% precision high risk, 100% precision low risk, 91% recall high-risk, and 94% recall low-risk. Other data also shown in the chart.

## Summary
In the first four models, the accuracy score is not as high as the ensemble scores. The mixed models have generally low accuracy scores as well. 
The best predictive models should have a fair mix of recall and precision accuracy. Therefore, I would recommend one of the 2 ensemble models. 
It appears that the Easy Ensemble AdaBoost Classifier has the most balanced mix of precision and recall accuracy scores and I would recommend that specific model to be used to assess credit risk in this example.
