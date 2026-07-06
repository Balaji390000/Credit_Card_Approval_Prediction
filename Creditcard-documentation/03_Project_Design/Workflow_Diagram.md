
# Workflow Diagram

## Workflow Description

The workflow begins when the user enters applicant information into the web application. The backend validates the information, preprocesses it, loads the trained model, predicts the approval status, and displays the result.

---

## Workflow Diagram

```mermaid
flowchart TD

Start([Start])

Input[Enter Applicant Details]

Validate{Valid Input?}

Error[Display Error]

Preprocess[Data Preprocessing]

Model[Load Trained Model]

Predict[Predict Approval]

Result[Display Result]

End([End])

Start --> Input
Input --> Validate

Validate -- No --> Error
Error --> Input

Validate -- Yes --> Preprocess
Preprocess --> Model
Model --> Predict
Predict --> Result
Result --> End
```