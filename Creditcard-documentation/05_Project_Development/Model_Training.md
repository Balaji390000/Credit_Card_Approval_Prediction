# Model Training

## Overview

Model training involves teaching the Machine Learning algorithm to recognize patterns from historical applicant data.

---

## Training Process

1. Load preprocessed dataset.
2. Split data into training and testing sets.
3. Train selected algorithms.
4. Tune hyperparameters.
5. Validate using cross-validation.
6. Save the trained model.

---

## Hyperparameter Tuning

Hyperparameters were optimized to improve model performance and reduce overfitting.

Examples include:

- Number of estimators
- Maximum tree depth
- Learning rate
- Regularization parameters

---

## Cross Validation

Cross-validation was performed to ensure that the model generalizes well to unseen data and does not rely on specific training samples.

---

## Output

The final trained model was exported using Joblib for deployment.