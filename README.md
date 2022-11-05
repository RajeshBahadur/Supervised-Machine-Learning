# Supervised-Machine-Learning
Module-17-Supervised Machine Learning-Credit Analysis
#Written Report on Credit Risk Analysis

1.	Overview of the analysis
The purpose of this analysis is to apply six different unbalanced machine learning models to the same dataset and compare the results obtained. The dataset used contains the credit applications from different individuals in the file named 2019Q1.csv , obtained from a personal credit company called LendingClub. 

The csv file contains 115,676 individuals with various loan status, the first starter code provided in the challenge is for doing oversampling, underdamping and combination algorithm. The second starter code provide in the challenge for doing Ensemble learning to reduce bias in the model.
Following types of Algorithms and corresponding names of Algorithms used in the challenge
a.	Oversampling Algorithms- Naïve Random Oversampling and SMOTE Oversampling.
b.	Under sampling Algorithms- Cluster Centroid
c.	Combination of over and under sampling-SMOTEENN
d.	Ensemble Learner- Balanced Random Forest Classifier and Easy Ensemble AdaBoost classifier

The starter code provided had codes which cleaned data e.g remove columns with null values, remove rows where the loan status is “issued” and convert remaining loan status to ‘Low Risk” and “High risk category”.

All models are evaluated based on the accuracy score to determine which is the best model to use for predicting credit risk.
