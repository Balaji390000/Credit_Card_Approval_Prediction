# Functional Requirements

## 1. Introduction

Functional requirements define the core functionalities that the Credit Card Approval Prediction System must perform. These requirements describe the expected behavior of the system from the user's perspective.

---

# 2. User Requirements

The system shall allow users to:

- Enter applicant information through a web interface.
- Submit applicant details for prediction.
- View the prediction result instantly.
- Reset the input form.
- Receive a clear approval or rejection message.

---

# 3. System Requirements

The system shall:

- Accept valid applicant information.
- Validate all mandatory fields.
- Handle missing or incorrect inputs gracefully.
- Perform data preprocessing before prediction.
- Load the trained Machine Learning model.
- Predict the approval status.
- Display prediction results.
- Log prediction requests for future analysis (optional).

---

# 4. Data Processing Requirements

The system shall:

- Handle missing values.
- Encode categorical variables.
- Normalize or standardize numerical values (if required).
- Convert user input into model-compatible format.

---

# 5. Prediction Requirements

The Machine Learning model shall:

- Accept processed applicant data.
- Predict Approval or Rejection.
- Return prediction within a few seconds.
- Maintain high prediction accuracy.

---

# 6. User Interface Requirements

The interface shall:

- Be simple and user-friendly.
- Allow quick data entry.
- Display meaningful error messages.
- Display prediction results clearly.

---

# 7. Administrative Functions

Future versions may include:

- Prediction history
- User authentication
- Database storage
- Dashboard analytics

---

# Summary

The functional requirements ensure that the application performs accurate and efficient credit card approval prediction while providing an intuitive user experience.