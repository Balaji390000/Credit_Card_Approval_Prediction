# Data Preprocessing

## Overview

Raw datasets often contain inconsistencies that can negatively impact model performance. Data preprocessing transforms raw data into a clean and structured format suitable for Machine Learning.

---

## Preprocessing Steps

### 1. Data Cleaning

The dataset was inspected for:

- Missing values
- Duplicate entries
- Invalid records
- Incorrect formats

---

### 2. Missing Value Handling

Missing values were handled using appropriate techniques such as:

- Mean or median imputation for numerical features
- Mode imputation for categorical features
- Removal of records with excessive missing values

---

### 3. Encoding Categorical Variables

Categorical variables were converted into numerical values using encoding techniques such as:

- Label Encoding
- One-Hot Encoding

---

### 4. Feature Scaling

Numerical features were standardized to ensure consistent ranges across variables.

Techniques include:

- StandardScaler
- MinMaxScaler

---

### 5. Data Splitting

The dataset was divided into:

- Training Set (80%)
- Testing Set (20%)

This separation ensures unbiased evaluation of the trained model.

---

## Outcome

After preprocessing, the dataset became clean, consistent, and ready for feature engineering and model training.