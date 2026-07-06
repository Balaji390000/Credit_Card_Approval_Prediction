# System Flowchart

## Process Flow

```mermaid
flowchart TD

A(Start)

B[Open Website]

C[Enter Applicant Information]

D{Validation}

E[Show Error]

F[Preprocess Data]

G[Run ML Model]

H{Approved?}

I[Display Approved]

J[Display Rejected]

K(End)

A --> B
B --> C
C --> D

D -- Invalid --> E
E --> C

D -- Valid --> F
F --> G
G --> H

H -- Yes --> I
H -- No --> J

I --> K
J --> K
```

---

## Description

This flowchart represents the complete execution flow of the Credit Card Approval Prediction application from user input to final prediction.