# Test Cases – Monobank (iOS Application)

## Overview
This document contains test cases for Monobank iOS application. Focus areas included authentication, balance display, and transaction functionality.

---

### ✅ Test Cases

| TC ID | Title                        | Precondition                | Steps                                                                 | Expected Result                         | Status |
|-------|------------------------------|-----------------------------|------------------------------------------------------------------------|------------------------------------------|--------|
| TC001 | Login with correct PIN       | User is registered          | 1. Launch app <br>2. Enter valid PIN                                   | User is logged in to main screen         | Pass   |
| TC002 | Login with incorrect PIN     | -                           | 1. Launch app <br>2. Enter wrong PIN                                   | Error message is shown                   | Pass   |
| TC003 | View account balance         | User is logged in           | 1. Login <br>2. Observe balance block                                  | Account balance is displayed correctly   | Pass   |
| TC004 | Make transfer to saved user  | User is logged in           | 1. Open Transfers <br>2. Select saved user <br>3. Enter amount and send | Transaction is completed successfully    | Pass   |
| TC005 | Send money with empty fields | -                           | 1. Open Transfers <br>2. Leave amount empty <br>3. Click Send           | Validation error shown                   | Pass   |

---

## Notes
- Tested on iOS 16, iPhone 12
- Risk-based prioritization applied during test plan creation
