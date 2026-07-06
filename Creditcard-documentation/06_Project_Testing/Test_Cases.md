# Test Cases

## Overview

This document describes the test cases executed to validate the functionality of the Credit Card Approval Prediction System. Each test ensures that the application behaves correctly under different input conditions.

---

## Test Case Summary

| Test Case ID | Test Scenario | Input | Expected Result | Status |
|--------------|---------------|-------|-----------------|--------|
| TC-01 | Open Home Page | Application URL | Home page loads successfully | ✅ Pass |
| TC-02 | Login with valid credentials | Valid Username & Password | Redirect to Prediction Page | ✅ Pass |
| TC-03 | Login with invalid credentials | Invalid Username/Password | Display error message | ✅ Pass |
| TC-04 | Submit valid applicant details | Valid applicant information | Prediction generated successfully | ✅ Pass |
| TC-05 | Submit empty form | No input | Validation error displayed | ✅ Pass |
| TC-06 | Invalid age value | Negative age | Error message displayed | ✅ Pass |
| TC-07 | Invalid income value | Alphabetic input | Validation error displayed | ✅ Pass |
| TC-08 | View Prediction History | Previous predictions exist | History displayed successfully | ✅ Pass |
| TC-09 | Model Prediction | Valid processed input | Approved/Rejected displayed | ✅ Pass |
| TC-10 | Logout | Click Logout | Return to Login Page | ✅ Pass |

---

## Test Execution Summary

- Total Test Cases: 10
- Passed: 10
- Failed: 0

---

## Conclusion

All functional test cases passed successfully, confirming that the system performs as expected under normal operating conditions.