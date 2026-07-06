# Software Requirement Specification (SRS)

# Project Title

**Credit Card Approval Prediction using Machine Learning**

---

# 1. Introduction

The Credit Card Approval Prediction System is a Machine Learning-based web application that predicts whether a customer's credit card application should be approved based on applicant information.

The application reduces manual effort, improves prediction consistency, and assists banking institutions in making informed decisions.

---

# 2. Purpose

The purpose of the system is to automate the credit card approval process using predictive analytics.

---

# 3. Scope

The project includes:

- Data preprocessing
- Machine Learning model training
- Prediction generation
- Flask web deployment

The project excludes:

- Online banking integration
- Live customer verification
- Credit bureau APIs

---

# 4. Stakeholders

| Stakeholder | Responsibility |
|--------------|---------------|
| Customer | Submit application |
| Bank Officer | Review prediction |
| Administrator | Maintain system |
| Developer | Build application |

---

# 5. Functional Requirements

- Accept applicant data.
- Validate inputs.
- Preprocess data.
- Predict approval status.
- Display prediction.

---

# 6. Non-Functional Requirements

- Fast prediction
- High accuracy
- Easy usability
- Reliable performance
- Secure input validation

---

# 7. Constraints

- Prediction depends on dataset quality.
- Model accuracy depends on training data.
- Internet required for package installation.

---

# 8. Assumptions

- User enters valid information.
- Trained model exists.
- Required Python libraries are installed.

---

# 9. Inputs

Examples include:

- Gender
- Age
- Income
- Employment Status
- Education
- Marital Status
- Existing Loans
- Credit History

---

# 10. Outputs

The system returns one of the following:

- **Approved**
- **Rejected**

along with a prediction message displayed on the web interface.

---

# 11. Future Enhancements

- User login
- Database integration
- Cloud deployment
- Explainable AI
- Mobile application
- REST API
- Real-time banking integration

---

# Conclusion

The Software Requirement Specification defines the functional and non-functional requirements necessary for developing a reliable, efficient, and scalable Credit Card Approval Prediction System.