# Union E-Banking System — Test Cases

## 1. Login Testing

| Test Case ID | Scenario | Test Steps | Expected Result | Status |
|---|---|---|---|---|
| TC001 | Valid login | Enter valid credentials and click Login | User logs in successfully | Not Executed |
| TC002 | Invalid password | Enter a valid username and incorrect password | Login is rejected with an appropriate message | Not Executed |
| TC003 | Empty credentials | Leave username and password blank, then click Login | Required-field validation is displayed | Not Executed |

## 2. Registration Testing

| Test Case ID | Scenario | Test Steps | Expected Result | Status |
|---|---|---|---|---|
| TC004 | Valid registration | Enter valid required details and submit | Account is created if the details meet requirements | Not Executed |
| TC005 | Missing required fields | Leave mandatory fields empty and submit | Validation messages are displayed | Not Executed |

## 3. Beneficiary Testing

| Test Case ID | Scenario | Test Steps | Expected Result | Status |
|---|---|---|---|---|
| TC006 | Add beneficiary | Enter valid beneficiary details and submit | Beneficiary is added successfully | Not Executed |
| TC007 | Invalid beneficiary details | Enter invalid details and submit | Invalid details are rejected with suitable validation | Not Executed |

## 4. Fund Transfer Testing

| Test Case ID | Scenario | Test Steps | Expected Result | Status |
|---|---|---|---|---|
| TC008 | Valid transfer | Enter valid transfer details and submit | Transfer is processed correctly | Not Executed |
| TC009 | Insufficient balance | Attempt a transfer exceeding the available balance | Transfer is rejected | Not Executed |
| TC010 | Invalid transfer amount | Enter zero or a negative amount | Invalid amount is rejected | Not Executed |

## Execution Notes
These are proposed test cases for a portfolio project. They have not been executed yet. Update the status and record actual results only after testing the relevant functionality in the application.
