# Entity Relationship Diagram

## Overview

Although the current application does not use a database, the following ER diagram represents a future implementation where applicant records and prediction history are stored.

---

## Entities

### Applicant

- Applicant ID
- Name
- Age
- Gender
- Income
- Employment Status
- Credit History

### Prediction

- Prediction ID
- Applicant ID
- Prediction Result
- Prediction Date

---

## ER Diagram

```mermaid
erDiagram

APPLICANT ||--o{ PREDICTION : generates

APPLICANT{

int Applicant_ID

string Name

int Age

string Gender

float Income

string Employment

string Credit_History

}

PREDICTION{

int Prediction_ID

string Result

date Prediction_Date

}
```

---

## Relationship

One applicant can have multiple prediction records over time.