# SauceDemo - Manual Testing Project

**Project Name:** SauceDemo Manual Testing  
**Application URL:** [https://www.saucedemo.com/](https://www.saucedemo.com/)  
**Author:** Rojina Adhikari  
**Date:** July 17, 2026  
**Status:** Completed

---

##  Project Overview

This project focuses on **manual testing** of the SauceDemo web application. The testing covers functional, UI, and usability aspects of the application to ensure a seamless user experience.

### Application Description

SauceDemo is a demo e-commerce web application designed for testing purposes. It simulates a simple online store where users can log in, view products, add items to the cart, and complete the checkout process.

### Key Features Tested

| Module | Features |
|:---|:---|
| **Login** | Valid login, invalid login, locked user, empty fields, special users |
| **Products** | Product display, add to cart, remove from cart, filter/sort |
| **Cart** | View cart, remove items, continue shopping, checkout |
| **Checkout** | Checkout form, validation, order overview, order completion |
| **UI/UX** | Page layout, responsive design, cross-browser compatibility |

---

## Project Objective

The objective of this project is to perform **comprehensive manual testing** of the SauceDemo web application to ensure:

| # | Objective | Status |
|:---|:---|:---|
| 1 | All login functionalities work as expected | Passed |
| 2 | UI elements are displayed correctly | Passed |
| 3 | Error handling is proper and user-friendly | Passed |
| 4 | Application is responsive across different screen sizes | Passed |
| 5 | All user roles behave as expected | Passed |

---

##  Project Structure
SauceDemo/
├── README.md # Project Overview (This file)
├── Test_Plan/ # Test planning documents
│ └── Test_Plan.md
├── Test_Scenarios/ # High-level test scenarios
│ └── Test_Scenarios.xlsx
├── Test_Cases/ # Detailed test cases
│ └── SauceDemo_TestCases.xlsx
├── Bug_Reports/ # Bug tracking
│ ├── Bug_Report.xlsx
│ └── BUG-REPORTS.md
├── Test_Execution_Report/ # Execution reports
│ ├── Execution_Report.xlsx
│ └── Execution_Report.md
├── UI_Testing/ # UI testing artifacts
│ ├── Login_Page_Checklist.md
│ └── Dashboard_UI_Checklist.md
└── Screenshots
##  Quick Project Status

| Metric | Value | Status |
|:---|:---|:---|
| **Total Test Cases** | 45 | Pass |
| **Executed** | 45 | Pass |
| **Passed** | 45 | Pass |
| **Failed** | 0 | Pass |
| **Pass Rate** | 100% | Pass |
| **Bugs Found** | 7 | Warning |
| **Critical Bugs** | 0 | Pass |
| **High Priority Bugs** | 2 | Warning |
| **Medium Priority Bugs** | 3 | Warning |
| **Low Priority Bugs** | 2 | Pass |

---

##  Testing Activities

### 1. Test Planning
- Created Test Plan document outlining scope, objectives, and strategy
- Defined testing approach and resources

### 2. Test Scenarios
- Designed 17 high-level test scenarios
- Covered Login, Products, Cart, Checkout, and UI modules

### 3. Test Case Creation
- Created 45 detailed test cases
- Included preconditions, steps, test data, and expected results

### 4. Test Execution
- Executed all 45 test cases
- Pass rate: 100%
- Execution period: July 14-16, 2026

### 5. Bug Reporting
- Identified 7 bugs
- Documented with severity, priority, and steps to reproduce

### 6. UI Testing
- Login Page UI Checklist
- Dashboard/Products Page UI Checklist

---

##  Bugs Found

| Bug ID | Title | Severity | Priority | Status |
|:---|:---|:---|:---|:---|
| BUG-001 | Incorrect Error Message Format for Invalid Credentials | Medium | High | Open |
| BUG-002 | Incorrect Error Message Format for Empty Credentials | Medium | High | Open |
| BUG-003 | Incorrect Error Message Format for Locked-Out User | Medium | Medium | Open |
| BUG-004 | Broken Product Images for Problem User | Medium | Medium | Open |
| BUG-005 | Performance Delay for Performance Glitch User | Low | Medium | Open |
| BUG-006 | Distorted UI for Visual User | Low | Low | Open |
| BUG-007 | Typographical Error in Test Data | Low | Low | Open |

---

##  Test Results

### Module-wise Summary

| Module | Total | Passed | Failed | Pass % | Bugs |
|:---|:---|:---|:---|:---|:---|
| Login Module | 14 | 14 | 0 | 100% | 5 |
| Products Module | 16 | 16 | 0 | 100% | 0 |
| Cart Module | 5 | 5 | 0 | 100% | 0 |
| Checkout Module | 7 | 7 | 0 | 100% | 0 |
| UI Testing | 3 | 3 | 0 | 100% | 2 |
| **Total** | **45** | **45** | **0** | **100%** | **7** |

---

##  Test Environment

| Component | Details |
|:---|:---|
| **Application URL** | https://www.saucedemo.com/ |
| **Browser** | Chrome 114.0 |
| **Operating System** | Windows 11 |
| **Screen Resolution** | 1920 x 1080 |
| **Network Speed** | 100 Mbps |
| **Tools Used** | GitHub, Excel, Chrome DevTools |

---

##  Tools Used

| Tool | Purpose |
|:---|:---|
| **GitHub** | Version control and repository hosting |
| **Microsoft Excel** | Test case management, bug tracking |
| **Google Sheets** | Collaboration and documentation |
| **Chrome DevTools** | UI and responsive testing |

---

##  Deliverables

| # | Deliverable | Description | Status |
|:---|:---|:---|:---|
| 1 | Test Plan | Master test plan document | Completed |
| 2 | Test Scenarios | High-level test scenarios | Completed |
| 3 | Test Cases | Detailed test cases with steps | Completed |
| 4 | Bug Reports | All bugs found during testing | Completed |
| 5 | Test Execution Report | Test execution summary | Completed |
| 6 | UI Testing Checklists | UI validation results | Completed |
| 7 | Screenshots | Test evidence | Completed |

---

## 📝 Recommendations

### High Priority (Must Fix)

| # | Recommendation | Bug ID |
|:---|:---|:---|
| 1 | Remove "Epic sadface:" prefix from invalid credentials error | BUG-001 |
| 2 | Remove "Epic sadface:" prefix from empty credentials error | BUG-002 |

### Medium Priority (Should Fix)

| # | Recommendation | Bug ID |
|:---|:---|:---|
| 3 | Remove "Epic sadface:" prefix from locked user error | BUG-003 |
| 4 | Fix broken images for problem_user | BUG-004 |
| 5 | Optimize performance for performance_glitch_user | BUG-005 |

### Low Priority (Nice to Have)

| # | Recommendation | Bug ID |
|:---|:---|:---|
| 6 | Fix UI distortion for visual_user | BUG-006 |
| 7 | Fix typo in test data | BUG-007 |

---

##  Final Status

| Aspect | Status |
|:---|:---|
| **Functional Testing** | Passed |
| **UI Testing** | Passed (with issues) |
| **Bug Status** | 7 Open Bugs |
| **Blocking Issues** | None |
| **Overall Status** | Passed |

##  Author

| Name | Role | Contact |
|:---|:---|:---|
| Rojina Adhikari | QA Tester | rojinatech03@gmail.com |

---

##  Timeline

| Phase | Start Date | End Date | Status |
|:---|:---|:---|:---|
| Test Planning | July 13, 2026 | July 13, 2026 | Completed |
| Test Case Creation | July 13, 2026 | July 14, 2026 | Completed |
| Test Execution | July 14, 2026 | July 15, 2026 | Completed |
| Bug Reporting | July 16, 2026 | July 16, 2026 | Completed |
| UI Testing | July 14, 2026 | July 15, 2026 | Completed |
| Report Generation | July 16, 2026 | July 17, 2026 | Completed |

---

##  Quick Links

| Document | Link |
|:---|:---|
| Test Plan | [./Test_Plan/Test_Plan.md](./Test_Plan/Test_Plan.md) |
| Test Scenarios | [./Test_Scenarios/Test_Scenarios.xlsx](./Test_Scenarios/Test_Scenarios.xlsx) |
| Test Cases | [./Test_Cases/SauceDemo_TestCases.xlsx](./Test_Cases/SauceDemo_TestCases.xlsx) |
| Bug Reports | [./Bug_Reports/Bug_Report.xlsx](./Bug_Reports/Bug_Report.xlsx) |
| Execution Report | [./Test_Execution_Report/Execution_Report.xlsx](./Test_Execution_Report/Execution_Report.xlsx) |
| UI Testing | [./UI_Testing/](./UI_Testing/) |
| Screenshots | [./Screenshots/](./Screenshots/) |

---

##  License

This project is for educational and testing purposes only.

---

**Last Updated:** July 17, 2026  
**Version:** 1.0  
**Status:** Completed

---

**Thank you for reviewing this project!** 
