# Test Cases – Makeup (Web Application)

## Overview
This document includes manual test cases for the Makeup online store. Core scenarios tested include product browsing, cart functionality, and checkout.

---

### ✅ Test Cases

| TC ID | Title                          | Precondition                | Steps                                                                 | Expected Result                              | Status |
|-------|--------------------------------|-----------------------------|------------------------------------------------------------------------|------------------------------------------------|--------|
| TC001 | Open homepage                  | -                           | 1. Navigate to main URL                                               | Homepage loads with featured products         | Pass   |
| TC002 | Search for product             | -                           | 1. Enter 'lipstick' in search bar <br>2. Click Search                 | Search results page displays matching items   | Pass   |
| TC003 | Add item to cart               | -                           | 1. View a product <br>2. Click 'Add to cart'                          | Item appears in cart                          | Pass   |
| TC004 | View cart                      | -                           | 1. Click on cart icon                                                 | Cart page displays with selected items        | Pass   |
| TC005 | Checkout with valid data       | User is logged in           | 1. Go to checkout <br>2. Fill all fields <br>3. Submit                | Order confirmation page is shown              | Pass   |

---

## Notes
- Functional testing focused on critical e-commerce flows
- Performed on Chrome & Firefox
