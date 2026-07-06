# Gantt Chart

## Overview

A Gantt Chart is a project management tool that illustrates the timeline of project activities, their duration, and dependencies. It helps in tracking the progress of each phase from project initiation to deployment.

---

## Project Schedule

| Task | Week 1 | Week 2 | Week 3 | Week 4 | Week 5 | Week 6 |
|------|:------:|:------:|:------:|:------:|:------:|:------:|
| Problem Identification | ███ | | | | | |
| Requirement Analysis | ███ | █ | | | | |
| Dataset Collection | | ███ | | | | |
| Data Preprocessing | | ███ | █ | | | |
| Exploratory Data Analysis | | | ███ | | | |
| Feature Engineering | | | ███ | █ | | |
| Model Development | | | | ███ | █ | |
| Model Evaluation | | | | | ███ | |
| Flask Integration | | | | | ███ | █ |
| Testing | | | | | | ███ |
| Documentation | █ | █ | █ | █ | █ | █ |
| Final Deployment | | | | | | ███ |

---

## Mermaid Gantt Chart

```mermaid
gantt
    title Credit Card Approval Prediction Project Schedule
    dateFormat YYYY-MM-DD

    section Planning
    Problem Identification      :done, p1, 2025-01-01, 4d
    Requirement Analysis        :done, p2, after p1, 5d

    section Development
    Dataset Collection          :done, d1, after p2, 5d
    Data Preprocessing          :done, d2, after d1, 6d
    Feature Engineering         :done, d3, after d2, 5d
    Model Training              :done, d4, after d3, 6d

    section Deployment
    Flask Development           :done, d5, after d4, 5d
    Testing                     :done, d6, after d5, 4d
    Documentation               :done, d7, after d6, 5d
```

---

## Conclusion

The project followed a structured schedule, ensuring timely completion of all development phases while maintaining quality and accuracy.