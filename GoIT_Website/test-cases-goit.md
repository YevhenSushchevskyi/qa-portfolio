# Test Cases – GoIT Website

## Overview
This document includes functional test cases for the GoIT Website project. Focus was on login, registration, and contact form functionality.

---

### ✅ Test Cases

| TC ID | Title                        | Precondition                | Steps                                                                 | Expected Result                        | Status |
|-------|------------------------------|-----------------------------|------------------------------------------------------------------------|-----------------------------------------|--------|
| TC001 | Valid login                  | User is registered          | 1. Open login page  <br>2. Enter valid email and password <br>3. Click Login | User is redirected to dashboard         | Pass   |
| TC002 | Invalid login                | -                           | 1. Open login page  <br>2. Enter invalid password <br>3. Click Login        | Error message is displayed              | Pass   |
| TC003 | Empty login fields           | -                           | 1. Open login page  <br>2. Leave fields empty <br>3. Click Login          | Validation error shown                  | Pass   |
| TC004 | Register new user            | User is logged out          | 1. Open signup page <br>2. Enter valid info <br>3. Submit                 | Confirmation message appears            | Pass   |
| TC005 | Submit empty contact form    | -                           | 1. Open Contact Us <br>2. Leave all fields empty <br>3. Click Submit       | Validation errors shown below fields    | Pass   |
| TC006 | Submit valid contact form    | -                           | 1. Open Contact Us <br>2. Fill in name, email, message <br>3. Submit       | Thank-you message is displayed          | Pass   |

---

## Notes
- Test environment: Chrome 120, Windows 11
- Bug reports were filed for TC002 and TC005 during early iterations
