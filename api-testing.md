# Union E-Banking System — API Testing

## 1. Project Overview
This document outlines the proposed API testing approach for the academic Union E-Banking System project.

## 2. API Testing Scope
- User registration
- User login and authentication
- Account information
- Beneficiary management
- Fund transfers
- Input validation and error handling

## 3. Test Scenarios

| Test ID | Scenario | Expected Result | Status |
|---|---|---|---|
| API-001 | Register with valid details | User is registered successfully | Not Executed |
| API-002 | Register with missing mandatory fields | Validation error is returned | Not Executed |
| API-003 | Login with valid credentials | Authentication succeeds | Not Executed |
| API-004 | Login with invalid credentials | Request is rejected appropriately | Not Executed |
| API-005 | Access a protected endpoint without authentication | Access is denied | Not Executed |
| API-006 | Submit an invalid transfer amount | Invalid request is rejected | Not Executed |
| API-007 | Submit an invalid beneficiary request | Validation error is returned | Not Executed |

## 4. Validation Checklist
- Verify HTTP status codes.
- Validate response body and required fields.
- Check error messages for invalid requests.
- Verify authentication and authorization behavior.
- Check that invalid requests do not create incorrect database records.
- Confirm that the response matches the documented API contract.

## 5. Tools
- Postman
- REST API
- SQL database queries, where applicable

## 6. Execution Notes
These scenarios are proposed test cases. Execute them against the project’s available API, then record actual responses, evidence, and final statuses.

**Important:** Update the test results only after execution. Do not include real banking credentials, tokens, or customer information.
