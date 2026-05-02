# Registration Form Test Scenarios

## Feature Overview

This document contains test scenarios for a user registration form with the following fields:

- Name
- Email
- Password
- Confirm Password

The goal is to verify that users can register successfully only when all required fields are valid.

## Test Scenarios

| Scenario ID | Test Scenario | Type |
|---|---|---|
| TS_001 | Verify that the user can register with valid name, valid email, valid password, and matching confirm password | Positive |
| TS_002 | Verify that the user cannot register when the email field is empty | Empty Field |
| TS_003 | Verify that the user cannot register when the password field is empty | Empty Field |
| TS_004 | Verify that the user cannot register when the name field is empty | Empty filed |
| TS_005 | Verify that the user cannot register when the confirm password field is empty | Empty Field |
| TS_006 | Verify that the user cannot register when the password and confirm password field do not match | Negative |
| TS_007 | Verify that the user cannot register with the invalid email format | Negative |
| TS_008 | Verify that the passowrd field is masked by default | Security |
| TS_009 | Verify that the entered password is not shorter than the minimum required length | Boundary |
| TS_010 | Verify that the user cannot register with an already registered email address | Negative |
| TS_011 | Verify that the user gets an appropriate error message when required fields are left empty | Usability |
| TS_012 | Verify that a clear error message is displayed when the email format is invalid | Usability |
