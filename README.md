# Sampling
Sampling Techniques and Model Comparison on Credit Card Data

Project Overview
You analyze how different sampling techniques affect model accuracy.
You apply five sampling methods on one population.
You train five classification models on each sample.
You compare accuracy across all combinations.

Dataset
You use a public credit card dataset.
The dataset contains transaction features and a target column named Class.
Class value zero represents normal transactions.
Class value one represents fraudulent transactions.

Sampling Techniques Used
Simple Random Sampling selects records randomly from the population.
Systematic Sampling selects records at fixed intervals.
Stratified Sampling preserves class distribution during sampling.
Cluster Sampling selects all records from one randomly chosen cluster.
Bootstrap Sampling selects records with replacement.

Models Used
M1 uses Logistic Regression.
M2 uses Decision Tree.
M3 uses Random Forest.
M4 uses Naive Bayes.
M5 uses Support Vector Machine.

Workflow
You load the dataset.
You separate features and target.
You apply one sampling method at a time.
You split sampled data into training and testing sets using stratification.
You train each model on the training set.
You evaluate accuracy on the test set.
You store results in a comparison table.
You identify the best model and sampling combination.

Results
You generate an accuracy table with models as rows and sampling methods as columns.
You compute the best combination using maximum accuracy.
You print the model name, sampling type, and accuracy.

Key Observations
Stratified sampling maintains class balance.
Some sampling methods produce single class samples.
Models fail when training data contains one class.
Stratified train test split prevents such failures.

How to Run
You install required Python libraries.
You run the main notebook or script.
You review the printed accuracy table and best combination output.

Libraries Used
pandas
numpy
scikit learn

Repository Structure
Main notebook contains full implementation.
Functions define sampling methods.
Results table prints final comparison.
README explains project flow and findings.

Author
Saanchi Gupta
