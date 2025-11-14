# Bug Testing Assignment

## Overview
This repository contains my software testing assignment focusing on bug identification and bug tracking using Bugzilla demo server.

**Course:** Software Testing  
**Date:** November 14, 2025  
**Students:** Ahmed Alsuhaimi - 

---

## Assignment Structure

### Part 1 & 2: Bug Identification and Reporting
- **Website Tested:** [Academy Bugs Store](https://academybugs.com/store/)
- **Bug Tracking System:** [Bugzilla Demo](https://bugzilla52.allizgub.org/)
- **Number of Bugs Found:** 3
- **Documentation:** See `bug-reports/` folder

---

## Bugs Identified

### Bug #1313: Broken Manufacturer Link
- **Severity:** Normal
- **Priority:** P3
- **Status:** UNCONFIRMED
- **Description:** The manufacturer link in the product details page leads to an error page instead of showing manufacturer information.
- **Steps to Reproduce:**
  1. Open https://academybugs.com
  2. Click the "Find Bugs" link on the navigation bar
  3. Open any product
  4. Click the manufacturer link under the quantity
- **Expected Result:** The manufacturer link shows an appropriate page
- **Actual Result:** The manufacturer link opens an error page
- **Full Report:** [View PDF](bug-reports/bug-1-broken-manufacturer-link.pdf)

---

### Bug #1311: Page Freezes When Changing Currency
- **Severity:** Major
- **Priority:** P4
- **Status:** UNCONFIRMED
- **Description:** The page becomes unresponsive when attempting to change the currency in the product details page.
- **Steps to Reproduce:**
  1. Open https://academybugs.com
  2. Click the "Find Bugs" link on the navigation bar
  3. Open any product
  4. Change the currency in the right side menu
- **Expected Result:** The currency changes smoothly without freezing
- **Actual Result:** The page freezes when changing the currency
- **Full Report:** [View PDF](bug-reports/bug-2-currency-page-freeze.pdf)

---

### Bug #1312: Product Description Not in English
- **Severity:** Normal
- **Priority:** P2
- **Status:** UNCONFIRMED
- **Description:** The short description and full description of products are displayed in a language other than English.
- **Steps to Reproduce:**
  1. Open https://academybugs.com
  2. Click the "Find Bugs" link on the navigation bar
  3. Open any product
  4. Check the short description and full description sections
- **Expected Result:** Product descriptions appear in English
- **Actual Result:** Product descriptions are in a different language
- **Full Report:** [View PDF](bug-reports/bug-3-description-language.pdf)

---

## Tools & Environment

- **Bug Tracking System:** Bugzilla 5.2 Demo Server
- **Test Website:** Academy Bugs (https://academybugs.com/store/)
- **Browser:** All browsers tested
- **OS:** All operating systems

---

## Repository Contents
```
bug-testing-assignment/
├── README.md (this file)
└── bug-reports/
    ├── bug-1-broken-manufacturer-link.pdf
    ├── bug-2-currency-page-freeze.pdf
    └── bug-3-description-language.pdf
```

---

## Notes

- All bugs were reported on Bugzilla demo server: https://bugzilla52.allizgub.org/
- Bug IDs: #1311, #1312, #1313
- Part 3 (Bug Workflow Management) to be completed with team member assignment

---
