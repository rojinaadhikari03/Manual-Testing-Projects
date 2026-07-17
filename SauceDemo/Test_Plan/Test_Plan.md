#  Test Plan - SauceDemo Web Application

**Version:** 1.0  
**Date:** July 17, 2026  
**Author:** Rojina Adhikari  


---

## Document Information

| Field | Details |
|:---|:---|
| **Document Title** | Test Plan - SauceDemo Manual Testing |
| **Version** | 1.0 |
| **Date Created** | July 12, 2026 |
| **Last Updated** | July 16, 2026 |
| **Author** | Rojina Adhikari |



---

## Table of Contents

1. [Introduction](#introduction)
2. [Scope of Testing](#scope-of-testing)
3. [Out of Scope](#out-of-scope)
4. [Test Objectives](#test-objectives)
5. [Test Strategy](#test-strategy)
6. [Test Environment](#test-environment)
7. [Test Data](#test-data)
8. [Test Schedule](#test-schedule)
9. [Resources](#resources)
10. [Deliverables](#deliverables)
11. [Entry & Exit Criteria](#entry--exit-criteria)
12. [Risk Management](#risk-management)
13. [Defect Management](#defect-management)
14. [Sign-off](#sign-off)

---

## 1. Introduction

### 1.1 Project Overview

| Field | Details |
|:---|:---|
| **Project Name** | SauceDemo Manual Testing |
| **Application** | SauceDemo Web Application |
| **Application URL** | [https://www.saucedemo.com/](https://www.saucedemo.com/) |
| **Testing Type** | Manual Testing |
| **Test Environment** | Chrome 114.0, Windows 11 |
| **Testing Phase** | Functional, UI, Responsive, Cross-Browser |

### 1.2 Application Description

SauceDemo is a demo e-commerce web application designed for testing purposes. It simulates a simple online store where users can:

| # | Feature | Description |
|:---|:---|:---|
| 1 | Login | Log in with different user roles |
| 2 | Products | View products with images, descriptions, and prices |
| 3 | Cart | Add/remove products to/from cart |
| 4 | Checkout | Complete checkout process |
| 5 | Filter/Sort | Sort and filter products |

### 1.3 Purpose of Test Plan

This Test Plan outlines the strategy, approach, resources, and schedule for testing the SauceDemo web application. It serves as a guideline for the QA team to ensure comprehensive testing coverage.

---

## 2. Scope of Testing

### 2.1 Features to Be Tested

| Module | Features | Priority |
|:---|:---|:---|
| **Login Module** | Valid login, Invalid login, Empty credentials, Locked-out user, Special user accounts, Password masking, Error message display | High |
| **Products Module** | Product grid, Product images/titles/descriptions/prices, Add to Cart, Remove from Cart, Cart badge, Filter/Sort, Hamburger menu | High |
| **Cart Module** | View cart items, Remove items, Continue Shopping, Checkout navigation | High |
| **Checkout Module** | Checkout form, Form validation, Order overview, Total calculation, Order completion | High |
| **UI Testing** | Page layout, Color and font consistency, Responsive design, Cross-browser compatibility | Medium |

### 2.2 Test Types

| Test Type | Description | Status |
|:---|:---|:---|
| **Functional Testing** | Verify all functionalities work as expected | Planned |
| **UI Testing** | Verify interface elements, layout, and visual consistency |  Planned |
| **Responsive Testing** | Verify behavior across different screen sizes |  Planned |
| **Cross-Browser Testing** | Verify on Chrome, Firefox, Brave | Planned |

---

## 3. Out of Scope

The following areas are **NOT** covered in this testing:

| # | Item | Reason |
|:---|:---|:---|
| 1 | Performance Testing | Not part of manual testing scope |
| 2 | Security Testing | Out of scope for this phase |
| 3 | Mobile App Testing | Only web application is tested |
| 4 | API Testing | Limited to functional UI testing |
| 5 | Database Testing | Not applicable for demo application |

---

## 4. Test Objectives

| # | Objective | Success Criteria |
|:---|:---|:---|
| 1 | Verify all login scenarios work correctly | 100% pass rate for login test cases |
| 2 | Verify UI elements are displayed correctly | All UI checklists pass |
| 3 | Verify error handling is user-friendly | Clear error messages displayed |
| 4 | Verify responsive behavior across devices | Application adapts to all screen sizes |
| 5 | Verify cross-browser compatibility | Works on Chrome, Firefox, Brave |
| 6 | Identify and document all bugs | All bugs logged with proper details |
| 7 | Ensure application is stable | No blocking issues found |

---

## 5. Test Strategy

### 5.1 Testing Approach

| Step | Activity | Description |
|:---|:---|:---|
| 1 | **Test Planning** | Define scope, objectives, and schedule |
| 2 | **Test Scenario Design** | Identify test scenarios and prioritize |
| 3 | **Test Case Creation** | Create detailed test cases with steps and expected results |
| 4 | **Test Data Preparation** | Prepare credentials, test data, and environment |
| 5 | **Test Execution** | Execute test cases and record results |
| 6 | **Bug Reporting** | Log bugs with screenshots and detailed steps |
| 7 | **Test Reporting** | Generate test execution report and final summary |

### 5.2 Test Execution Method

| Method | Description | When to Use |
|:---|:---|:---|
| **Manual Testing** | Test cases executed manually by QA team | All testing phases |
| **Checklist-based Testing** | UI testing using checklists | UI validation |
| **Screenshot Evidence** | Capture screenshots for each test | Bug reporting and documentation |

---

## 6. Test Environment

### 6.1 Hardware Requirements

| Component | Specification |
|:---|:---|
| **Processor** | Intel i5 or equivalent |
| **RAM** | 8 GB minimum |
| **Storage** | 50 GB free space |
| **Screen Resolution** | 1920 x 1080 (recommended) |

### 6.2 Software Requirements

| Component | Details |
|:---|:---|
| **Operating System** | Windows 11 |
| **Browsers** | Chrome 114+, Firefox 113+, Brave |
| **Tools** | GitHub, Excel, Chrome DevTools |
| **Network** | Internet connection |

### 6.3 Test Environment Details

| Component | Details |
|:---|:---|
| **Application URL** | https://www.saucedemo.com/ |
| **Test Environment** | Production (Demo Site) |
| **Network Speed** | 100 Mbps |
| **DNS** | Default |

---

## 7. Test Data

### 7.1 Valid Credentials

| Username | Password | Role |
|:---|:---|:---|
| standard_user | secret_sauce | Standard user |
| locked_out_user | secret_sauce | Locked out user |
| problem_user | secret_sauce | Problem user (UI issues) |
| performance_glitch_user | secret_sauce | Performance glitch user |
| error_user | secret_sauce | Error user (UI defects) |
| visual_user | secret_sauce | Visual testing user |

### 7.2 Invalid Credentials

| Username | Password | Purpose |
|:---|:---|:---|
| invalid_user | wrong_password | Invalid login testing |
| standard_user | wrong_password | Invalid password testing |
| (empty) | (empty) | Empty field testing |

### 7.3 Checkout Test Data

| Field | Sample Data |
|:---|:---|
| First Name | John, Jane, Test |
| Last Name | Doe, Smith, User |
| Zip Code | 12345, 90210, 10001 |

---

## 8. Test Schedule

| Phase | Activity | Start Date | End Date | Duration | Status |
|:---|:---|:---|:---|:---|:---|
| 1 | Test Planning | July 13, 2026 | July 13, 2026 | 1 day |  Completed |
| 2 | Test Scenario Design | July 13, 2026 | July 13, 2026 | 1 day |  Completed |
| 3 | Test Case Creation | July 13, 2026 | July 14, 2026 | 1 day |  Completed |
| 4 | Test Data Preparation | July 14, 2026 | July 14, 2026 | 1 day |  Completed |
| 5 | Test Execution | July 14, 2026 | July 15, 2026 | 1 day |  Completed |
| 6 | Bug Reporting | July 16, 2026 | July 16, 2026 | 1 day |  Completed |
| 7 | UI Testing | July 14, 2026 | July 15, 2026 | 1 day |  Completed |
| 8 | Report Generation | July 16, 2026 | July 16, 2026 | 1 day | Completed |

---

## 9. Resources

### 9.1 Team Members

| Role | Name | Responsibilities |
|:---|:---|:---|
| **QA Tester** | Rojina Adhikari | Test case creation, execution, bug reporting, UI testing, report generation |

### 9.2 Tools Required

| Tool | Purpose |
|:---|:---|
| **GitHub** | Repository and version control |
| **Microsoft Excel** | Test case management, bug tracking |
| **Markdown Editor** | Documentation |
| **Chrome DevTools** | UI testing, responsive testing |

---

## 10. Deliverables

### 10.1 Testing Artifacts

| # | Deliverable | Description | Status |
|:---|:---|:---|:---|
| 1 | Test Plan | This document |  Completed |
| 2 | Test Scenarios | High-level scenarios |  Completed |
| 3 | Test Cases | Detailed test cases with steps |  Completed |
| 4 | Test Data | Sample test data | Completed |
| 5 | Bug Reports | All bugs found |  Completed |
| 6 | Test Execution Report | Summary of execution |  Completed |
| 7 | UI Testing Checklist | UI validation results |  Completed |
| 8 | Screenshots | Test evidence | Completed |

### 10.2 Location of Deliverables

| Deliverable | Location |
|:---|:---|
| Test Plan | `SauceDemo/Test_Plan/Test_Plan.md` |
| Test Scenarios | `SauceDemo/Test_Scenarios/Test_Scenarios.xlsx` |
| Test Cases | `SauceDemo/Test_Cases/SauceDemo_TestCases.xlsx` |
| Bug Reports | `SauceDemo/Bug_Reports/Bug_Report.xlsx` |
| Execution Report | `SauceDemo/Test_Execution_Report/Execution_Report.xlsx` |
| UI Testing | `SauceDemo/UI_Testing/` |
| Screenshots | `SauceDemo/Screenshots/` |

---

## 11. Entry & Exit Criteria

### 11.1 Entry Criteria

| # | Criteria | Status |
|:---|:---|:---|
| 1 | Test Plan approved | Approved |
| 2 | Test Cases created and reviewed |  Completed |
| 3 | Test Data prepared |  Completed |
| 4 | Test Environment ready | Completed |
| 5 | Team members assigned |  Assigned |

### 11.2 Exit Criteria

| # | Criteria | Status |
|:---|:---|:---|
| 1 | All test cases executed |  100% |
| 2 | All test cases passed or documented |  45/45 passed |
| 3 | All critical/high bugs fixed | 2 high bugs open |
| 4 | Test Execution Report completed |  Completed |
| 5 | Final Test Report signed off |  Completed |

---

## 12. Risk Management

### 12.1 Identified Risks

| # | Risk | Probability | Impact | Mitigation |
|:---|:---|:---|:---|:---|
| 1 | Test environment unavailable | Low | High | Have backup environment ready |
| 2 | Bug fixes causing regression | Medium | High | Perform regression testing |
| 3 | Time constraints | Low | Medium | Prioritize test cases |
| 4 | Browser compatibility issues | Medium | Medium | Test on multiple browsers |
| 5 | UI changes without notice | Low | Medium | Communicate with development team |

### 12.2 Contingency Plan

| Scenario | Action |
|:---|:---|
| Environment down | Use alternate browser/device |
| Test data unavailable | Create backup test data |
| Bug fixes delayed | Document and track in bug report |
| Scope creep | Review and adjust scope with PM |

---

## 13. Defect Management

### 13.1 Defect Severity Levels

| Severity | Description | Examples |
|:---|:---|:---|
| **Critical** | Application crash, data loss | Cannot login, application breaks |
| **High** | Major feature broken | Login not working, payment failing |
| **Medium** | Minor feature broken | Error message incorrect, UI alignment |
| **Low** | Cosmetic issues | Typo, font size, color mismatch |

### 13.2 Defect Priority Levels

| Priority | Description | Response Time |
|:---|:---|:---|
| **High** | Must fix immediately | Within 24 hours |
| **Medium** | Should fix before release | Within 3 days |
| **Low** | Nice to have | Next release |

### 13.3 Bug Lifecycle

| Stage | Description |
|:---|:---|
| **Open** | Bug is reported |
| **In Progress** | Developer starts working |
| **In Review** | Developer submits PR |
| **Ready for Retest** | QA gets notified |
| **Fixed** | Bug is fixed |
| **Reopen** | Bug still exists |
| **Closed** | Bug is closed |

---

## 14. Sign-off

### 14.1 Approval Signatures

| Role | Name | Signature | Date |
|:---|:---|:---|:---|
| **QA Tester** | Rojina Adhikari | [Signature] | July 17, 2026 |

### 14.2 Document Approval

| Version | Date | Author | Changes |
|:---|:---|:---|:---|
| 1.0 | July 17, 2026 | Rojina Adhikari | Initial Test Plan |

---

## 📊 Test Plan Summary

| Category | Details |
|:---|:---|
| **Total Test Cases** | 45 |
| **Modules Covered** | Login, Products, Cart, Checkout, UI |
| **Test Types** | Functional, UI, Responsive, Cross-Browser |
| **Browsers Covered** | Chrome, Firefox, Brave |
| **Devices Covered** | Desktop |
| **Test Data** | Valid/Invalid credentials, Checkout data |
| **Expected Duration** | 3 days |

---

## 🔗 Related Documents

| Document | Link |
|:---|:---|
| Test Scenarios | [./Test_Scenarios/Test_Scenarios.xlsx](./Test_Scenarios/Test_Scenarios.xlsx) |
| Test Cases | [./Test_Cases/SauceDemo_TestCases.xlsx](./Test_Cases/SauceDemo_TestCases.xlsx) |
| Bug Reports | [./Bug_Reports/Bug_Report.xlsx](./Bug_Reports/Bug_Report.xlsx) |
| Execution Report | [./Test_Execution_Report/Execution_Report.xlsx](./Test_Execution_Report/Execution_Report.xlsx) |
| UI Testing | [./UI_Testing/](./UI_Testing/) |

---

**End of Test Plan Document**

**Version:** 1.0  
**Last Updated:** July 17, 2026  
**Status:**  Approved

---

**Thank you for reviewing this Test Plan!** 
