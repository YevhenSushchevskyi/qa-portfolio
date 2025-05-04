#Test Cases - GoiT Website

## Overview
This document contains functional test cases for the GoIT Website project, focusing on login functionality, new user registration, and contact form submission. All tests are designed to verify the correct handling of various scenarios, including successful and failed login attempts, as well as submission of valid and invalid data through the contact form.

---

### ✅ Test Cases

| TC ID  | Title                    | Precondition                            | Steps                                               | Expected Result                        | Status |
|--------|--------------------------|-----------------------------------------|-----------------------------------------------------|----------------------------------------|--------|
| TC001  | Valid login              | User is registered                     | 1. Open login page<br>2. Enter valid email and password<br>3. Click Login | User is redirected to dashboard         | Pass   |
| TC002  | Invalid login            | User exists but enters incorrect password | 1. Open login page<br>2. Enter invalid password<br>3. Click Login | Error message is displayed              | Pass   |
| TC003  | Empty login fields       | User is on the login page               | 1. Open login page<br>2. Leave fields empty<br>3. Click Login | Validation error shown                  | Pass   |
| TC004  | Register new user        | User is logged out                     | 1. Open signup page<br>2. Enter valid info<br>3. Submit | Confirmation message appears           | Pass   |
| TC005  | Submit empty contact form| User is on the "Contact Us" page       | 1. Open Contact Us<br>2. Leave all fields empty<br>3. Click Submit | Validation errors shown below fields   | Pass   |
| TC006  | Submit valid contact form| User is on the "Contact Us" page       | 1. Open Contact Us<br>2. Fill in name, email, message<br>3. Submit | Thank-you message is displayed         | Pass   |

---

## Notes
- Test environment: Chrome 120, Windows 11
- Bug reports were filed for TC002 and TC005 during early iterations
