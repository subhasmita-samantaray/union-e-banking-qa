# Union E-Banking System — Sample Bug Reports

**Note:** The following are hypothetical examples for a QA portfolio. They are not confirmed defects from an executed application test.

## Bug Report 1: Login Accepts Invalid Credentials

- **Bug ID:** BUG-001
- **Module:** Login
- **Severity:** High (proposed)
- **Priority:** High (proposed)
- **Environment:** To be specified during testing
- **Status:** Example only — Not Verified

### Preconditions
A registered test account exists in the test environment.

### Steps to Reproduce
1. Open the banking application's login page.
2. Enter a valid test username.
3. Enter an incorrect password.
4. Click Login.

### Expected Result
The application rejects the invalid credentials and displays an appropriate error message.

### Actual Result
Not yet observed. Record the actual behavior only after executing the test.

## Bug Report 2: Negative Transfer Amount Accepted

- **Bug ID:** BUG-002
- **Module:** Fund Transfer
- **Severity:** High (proposed)
- **Priority:** High (proposed)
- **Environment:** To be specified during testing
- **Status:** Example only — Not Verified

### Preconditions
A test account is available in the authorized test environment.

### Steps to Reproduce
1. Open the fund transfer page.
2. Enter valid test beneficiary details.
3. Enter a negative transfer amount.
4. Submit the transfer.

### Expected Result
The application rejects the negative amount and does not initiate a transfer.

### Actual Result
Not yet observed. Record the actual behavior only after executing the test.

## Defect Reporting Guidelines
- Include clear reproduction steps.
- Record expected and actual results separately.
- Assign severity and priority based on impact and urgency.
- Attach screenshots or logs when available.
- Update the defect status after verification and retesting.
