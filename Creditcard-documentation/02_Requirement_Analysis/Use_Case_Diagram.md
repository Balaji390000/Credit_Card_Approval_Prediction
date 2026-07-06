# Use Case Diagram

## Actors

1. User
2. Machine Learning Model
3. Administrator (Future Enhancement)

---

## Use Case Description

The user enters applicant information into the web application. The system validates the data, preprocesses it, loads the trained model, predicts the approval status, and displays the result.

---
![usecase](..images/ChatGPT Image Jul 6, 2026, 04_54_13 PM.png)

## Mermaid Use Case Diagram

```mermaid
graph LR

User((User))

A[Open Web Application]
B[Enter Applicant Details]
C[Validate Input]
D[Preprocess Data]
E[Load ML Model]
F[Predict Approval]
G[Display Result]

User --> A
User --> B
B --> C
C --> D
D --> E
E --> F
F --> G
```

---

## Use Cases

| Use Case | Description |
|-----------|-------------|
| Open Application | Access the web interface |
| Enter Details | Input applicant information |
| Validate Data | Check data correctness |
| Predict | ML model predicts approval |
| View Result | Display approval status |