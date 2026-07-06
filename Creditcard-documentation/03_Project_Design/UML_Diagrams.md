# UML Diagrams

## Class Diagram

```mermaid
classDiagram

class User

class FlaskApplication

class DataPreprocessing

class MLModel

class Prediction

User --> FlaskApplication

FlaskApplication --> DataPreprocessing

DataPreprocessing --> MLModel

MLModel --> Prediction
```

---

## Sequence Diagram

```mermaid
sequenceDiagram

participant User

participant Flask

participant Preprocessing

participant Model

User->>Flask: Submit Application

Flask->>Preprocessing: Clean Data

Preprocessing->>Model: Predict

Model-->>Flask: Prediction

Flask-->>User: Display Result
```

---

## Activity Diagram

```mermaid
flowchart TD

Start --> Input

Input --> Validation

Validation -->|Valid| Prediction

Validation -->|Invalid| Input

Prediction --> Result

Result --> End
```