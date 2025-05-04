# 📋 Test Plan: Mobile Banking Application

**Project:** Mobile Banking Application  
**Platform:** iOS 16, iPhone 12  
**Testing Type:** Functional  
**Methodology:** Manual Testing  
**Prioritization:** Risk-based prioritization  
**Date:** 2025-05-05

---

## 🎯 Objective

To verify that critical user functions (authentication, balance viewing, and money transfers) operate reliably and correctly on the target mobile platform.

---

## 🧪 Scope of Testing

Features covered:

- Login with correct and incorrect PIN  
- Viewing account balance  
- Sending money to a saved user  
- Form validation when submitting empty data

---

## 🧷 Test Environment

- **Device:** iPhone 12  
- **OS Version:** iOS 16  
- **Environment:** Staging  
- **App Build:** [Insert build version if applicable]

---

## ⚠️ Risk-Based Prioritization

| Priority | Covered Test Cases               | Justification                              |
|----------|----------------------------------|--------------------------------------------|
| High     | TC001, TC004                     | Core user flows: authentication, transfer  |
| Medium   | TC003                            | Common feature, less risk                  |
| Low      | TC005                            | Edge validation, not business-critical     |

---

## 📌 Notes

- All test cases passed successfully on iOS 16, iPhone 12  
- Testing was performed manually  
- Android compatibility to be tested in the next cycle  
- Additional scenarios (e.g., negative flows, edge cases) are planned
