# Literature Survey

## Overview

Several studies have explored the use of Machine Learning techniques for credit risk assessment and credit card approval prediction. Researchers have compared multiple classification algorithms to identify models capable of accurately predicting applicant eligibility.

## Existing Approaches

### Logistic Regression

One of the most commonly used statistical models for binary classification problems. It offers simplicity and interpretability but may struggle with complex nonlinear relationships.

### Decision Tree

Decision Trees classify applicants by learning decision rules from historical data. They are easy to interpret but may suffer from overfitting.

### Random Forest

Random Forest combines multiple Decision Trees to improve prediction accuracy and reduce overfitting. It is widely used for financial prediction tasks.

### Support Vector Machine

Support Vector Machines are effective for high-dimensional classification problems and often provide good performance on structured datasets.

### K-Nearest Neighbors

KNN classifies applicants based on similarity with neighboring records. Its performance depends heavily on feature scaling and dataset size.

## Research Gap

Many existing systems focus primarily on prediction accuracy without providing an easy-to-use web interface for real-time decision support. This project bridges that gap by integrating a trained Machine Learning model with a Flask-based web application.