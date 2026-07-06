# Demo Guide

## Overview

The Credit Card Approval Prediction System is a Machine Learning-based web application that predicts whether a credit card application is likely to be approved or rejected based on applicant details. This guide explains how to demonstrate the application's functionality step by step.

---

# Prerequisites

Before starting the demonstration, ensure that:

- Python 3.10 or later is installed.
- Required Python libraries are installed.
- The trained Machine Learning model (`model.pkl` or `.joblib`) is available.
- The Flask application is configured correctly.

---

# Running the Application

### Step 1: Open Terminal

Navigate to the project directory.

```bash
cd Credit-Card-Approval-Prediction
```

### Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 3: Start Flask Server

```bash
python app.py
```

### Step 4: Open Browser

Visit:

```
http://127.0.0.1:5000
```

---

# Demonstration Steps

### 1. Home Page

- Open the application.
- Verify that the home page loads successfully.

---

### 2. Login (If Implemented)

- Enter valid username and password.
- Click **Login**.
- Verify successful authentication.

---

### 3. Prediction

- Enter applicant details.
- Click **Predict**.
- Wait for the model to process the data.

---

### 4. Result

Verify that the system displays:

- Approved or Rejected
- Prediction message
- Additional information (if available)

---

### 5. History (If Implemented)

- Navigate to the History page.
- Verify that previous prediction records are displayed.

---

# Expected Outcome

The system should generate an accurate prediction within a few seconds and display the result without errors.

---

# Demonstration Flow

```mermaid
flowchart LR

Home --> Login

Login --> Prediction

Prediction --> Result

Result --> History

History --> Logout
```