# Registration Form Test Cases

## Feature Overview

This document contains detailed test cases for the user registration form.

---

## TC_001: Successful Registration with Valid Details

**Scenario ID:** TS_001  
**Type:** Positive  
**Priority:** High  
**Preconditions:** User is on the registration page.

### Test Data

| Field | Value |
|---|---|
| Name | John Smith |
| Email | john.smith@example.com |
| Password | Password@123 |
| Confirm Password | Password@123 |

### Test Steps

1. Enter valid name.
2. Enter valid email.
3. Enter valid password.
4. Enter matching confirm password.
5. Click the Register button.

### Expected Result

Account should be created successfully, and the user should see a success message or be redirected to the login/dashboard page.

### Actual Result

Not executed

### Status

Not executed

---

## TC_002: Registration with Empty Email Field

**Scenario ID:** TS_002
**Type:** Empty Field
**Priority:** High
**Preconditions:** User is on the registration page.

### Test Data

| Field | Value |
|---|---|
| Name | John Smith |
| Email | Blank |
| Password | Password@123 |
| Confirm Password | Password@123 |

### Test Steps

1. Enter valid name.
2. Leave the email field empty.
3. Enter valid password.
4. Enter matching confirm password.
5. Click the Register button.

### Expected Result

Account should not be created and a validation message should be displayed for the email field.

### Actual Result

Not executed

### Status

Not executed

---

## TC_003: Registration with Mismatched Password and Confirm Password

**Scenario ID:** TS_006  
**Type:** Negative  
**Priority:** High  
**Preconditions:** User is on the registration page.

### Test Data

| Field | Value |
|---|---|
| Name | John Smith |
| Email | john.smith@example.com |
| Password | Password@123 |
| Confirm Password | Password@12345 |

### Test Steps

1. Enter valid name.
2. Enter valid email.
3. Enter valid password.
4. Enter different confirm password.
5. Click the Register button.

### Expected Result

Account should not be created and a validation message should be displayed for the confirm password field.

### Actual Result

Not executed

### Status

Not executed
