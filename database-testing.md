# Union E-Banking System — Database Testing

## 1. Objective
Document database validation scenarios for the academic Union E-Banking System project.

## 2. Testing Scope
- User registration data
- Account information
- Beneficiary records
- Fund transfer records
- Data consistency and integrity

## 3. Database Test Scenarios

| Test ID | Scenario | Expected Result | Status |
|---|---|---|---|
| DB-001 | Verify a registered user record | Correct user details are stored | Not Executed |
| DB-002 | Verify account information | Account data matches the application response | Not Executed |
| DB-003 | Verify beneficiary creation | Valid beneficiary details are stored | Not Executed |
| DB-004 | Verify a successful transfer record | Transfer details and status are correct | Not Executed |
| DB-005 | Submit invalid transfer data | Invalid data is rejected and no incorrect record is created | Not Executed |

## 4. Validation Checklist
- Verify required fields and data types.
- Check for duplicate records where duplicates are not allowed.
- Validate transaction amounts and statuses.
- Verify relationships between users, accounts, beneficiaries, and transfers.
- Confirm that invalid operations do not create incorrect data.

## 5. SQL Examples
Adapt these examples to the actual schema and column names of the application.

```sql
-- Check user records
SELECT * FROM user;

-- Check account records
SELECT * FROM account;

-- Check beneficiary records
SELECT * FROM beneficiary;

-- Check transfer records
SELECT * FROM transfer;
```

## 6. Execution Notes
These are proposed database testing scenarios. Run the queries against your own test database, record actual results, and update each status only after execution.

Do not include real customer data, passwords, or sensitive banking information.
