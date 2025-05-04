
# Test Cases – Makeup (Web Application)

## Overview
This document includes manual test cases for the Makeup online store. Core scenarios tested include product browsing, cart functionality, and checkout.

---

### ✅ Test Cases

| TC ID | Title                          | Precondition                | Steps                                                                 | Expected Result                              | Status |
|-------|--------------------------------|-----------------------------|------------------------------------------------------------------------|------------------------------------------------|--------|
| TC001 | Open homepage                  | User is online and has browser access | 1. Navigate to main URL                                               | Homepage loads with featured products         | Pass   |
| TC002 | Search for product             | Homepage is loaded         | 1. Enter 'lipstick' in search bar <br>2. Click Search                 | Search results page displays matching items   | Pass   |
| TC003 | Add item to cart               | User is viewing a product page | 1. View a product <br>2. Click 'Add to cart'                          | Item appears in cart                          | Pass   |
| TC004 | View cart                      | At least one item is added to the cart | 1. Click on cart icon                                                 | Cart page displays with selected items        | Pass   |
| TC005 | Checkout with valid data       | User is logged in          | 1. Go to checkout <br>2. Fill all fields <br>3. Submit                | Order confirmation page is shown              | Pass   |

---

## Notes
- Functional testing focused on critical e-commerce flows  
- Performed on Chrome & Firefox

---

## 🐞 Bug Reports

### 🐛 Bug #001 – Product search returns no results  
- **Related TC**: TC002 – Search for product  
- **Summary**: Searching for "lipstick" returns no results even though products exist in the catalog.  
- **Precondition**: Homepage is loaded  
- **Steps to Reproduce**:  
  1. Open homepage  
  2. Enter "lipstick" in the search bar  
  3. Click "Search"  
- **Expected Result**: Products matching "lipstick" are displayed  
- **Actual Result**: "No products found" message is shown  
- **Severity**: Major  
- **Environment**: Chrome 120, Windows 11

---

### 🐛 Bug #002 – Add to cart button unresponsive  
- **Related TC**: TC003 – Add item to cart  
- **Summary**: Clicking "Add to cart" does not add the item; cart remains empty  
- **Precondition**: User is viewing a product page  
- **Steps to Reproduce**:  
  1. Open any product page  
  2. Click "Add to cart"  
- **Expected Result**: Item appears in cart  
- **Actual Result**: Nothing happens, cart remains empty  
- **Severity**: Critical  
- **Environment**: Firefox 124, macOS Ventura

---

### 🐛 Bug #003 – Checkout form accepts invalid email  
- **Related TC**: TC005 – Checkout with valid data  
- **Summary**: Checkout form allows submission with improperly formatted email  
- **Precondition**: User is logged in and has items in cart  
- **Steps to Reproduce**:  
  1. Go to checkout  
  2. Enter "user@invalid" as email  
  3. Fill other required fields and click Submit  
- **Expected Result**: Validation error on email field  
- **Actual Result**: Order is processed despite invalid email  
- **Severity**: High  
- **Environment**: Chrome 120, Windows 11
