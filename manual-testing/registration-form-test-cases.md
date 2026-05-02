# Registration Form Test Cases

## Feature Overview

This document contains detailed test cases for the user registration form.

## Test Cases

| Test Case ID | Scenario ID | Test Case Title | Preconditions | Test Data | Test Steps | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|---|---|
| TC_001 | TS_001 | Verify successful registration with valid details | User is on the registration page | Name: John Smith; Email: john.smith@example.com; Password: Password@123; Confirm Password: Password@123 | 1. Enter valid name 2. Enter valid email 3. Enter valid password 4. Enter matching confirm password 5. Click Register | Account should be created successfully and the user should see a success message or be redirected to the login/dashboard page | Not executed | Not executed |
| TC_002 | TS_002 | Verify unsuccessful registration when the email field is empty | User is on the registration page | Name: John Smith; Email: blank; Password: Password@123; Confirm Password: Password@123 | 1. Enter valid name 2. Leave the email field empty 3. Enter valid password 4. Enter matching confirm password 5. Click Register | Account should not be created and a validation message should be displayed for the email field | Not executed | Not executed |
| TC_003 | TS_006 | Verify unsuccessful registration when password and confirm password do not match | User is on the registration page | Name: John Smith; Email: john.smith@example.com; Password: Password@123; Confirm Password: Password@12345 | 1. Enter valid name 2. Enter valid email 3. Enter valid password 4. Enter different confirm password 5. Click Register | Account should not be created and a validation message should be displayed for the confirm password field | Not executed | Not executed |
