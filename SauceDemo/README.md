#  SauceDemo - Manual Testing Project


## Project Overview

| Field | Details |
|:---|:---|
| **Project Name** | SauceDemo Manual Testing |
| **Application URL** | [https://www.saucedemo.com/](https://www.saucedemo.com/) |
| **Testing Type** | Manual Testing |
| **Test Environment** | Chrome 114.0, Windows 11 |
| **Testing Phase** | Functional Testing, UI Testing, Responsive Testing, Cross-Browser Testing, Bug Reporting, Test Execution |
| **Start Date** | July 14, 2026 |
| **End Date** | July 16, 2026 |
| **Executed By** | Rojina Adhikari |
| **Current Status** | ✅ **PASSED** |
| **Total Test Cases** | 45 |
| **Test Cases Executed** | 45 (100%) |
| **Passed** | 45 |
| **Failed** | 0 |
| **Pass Rate** | **100%** |
| **Bugs Found** | 7 |
| **Critical Bugs** | 0 |
| **High Priority Bugs** | 2 |
| **Medium Priority Bugs** | 3 |
| **Low Priority Bugs** | 2 |

---

# Project Objective

The objective of this project is to perform **comprehensive manual testing** of the SauceDemo web application to ensure:

-  All login functionalities work as expected
-  UI elements are displayed correctly
- Error handling is proper and user-friendly
-  Application is responsive across different screen sizes
-  All user roles (standard, problem, error, visual) behave as expected

---

##  Repository Structure

```
SauceDemo/
├── README.md                              # Project Overview (This file)
├── Test_Plan/                             # Test planning documents
│   └── Test_Plan.md
├── Test_Scenarios/                        # High-level test scenarios
│   └── Test_Scenarios.md
├── Test_Cases/                            # Detailed test cases
│   └── SauceDemo_TestCases.xlsx
├── Bug_Reports/                           # Bug tracking
│   ├── Bug_Report.xlsx
│   └── BUG-REPORTS.md
├── Test_Execution_Report/                 # Execution reports
│   ├── Execution_Report.xlsx
│   └── Execution_Report.md
├── UI_Testing/                            # UI testing artifacts
│   ├── Login_Page_Checklist.md
│   └── Dashboard_UI_Checklist.md
└── Screenshots/                           # Test evidence
    ├── Login_Module/
    ├── Inventory_Module/
    ├── Bug_Reports_Evidence/
    └── Full_Page_Screenshots/
```

---

##  Quick Project Status

| Metric | Value | Status
|:---|:---|:---|
| **Total Test Cases** | 45 |pass |
| **Executed** | 45 | pass |
| **Passed** | 45 | pass |
| **Failed** | 0 | pass |
| **Pass Rate** | 100% | pass |
| **Bugs Found** | 7 | Warning |
| **Critical Bugs** | 0 | pass |
| **High Priority Bugs** | 2 | Warning |
| **Medium Priority Bugs** | 3 | Warning |
| **Low Priority Bugs** | 2 | Pass |
| **Blocking Issues** | 0 | Pass|

# Pass Rate Visualization

```
Overall Pass Rate: 100% (45/45)

 100% Pass
 0% Fail
 0% Blocked


# Module-wise Pass Rate

```
Login Module     ████████████████████████████████████████ 100% (14/14)
Products Module  ████████████████████████████████████████ 100% (16/16)
Cart Module      ████████████████████████████████████████ 100% (5/5)
Checkout Module  ████████████████████████████████████████ 100% (7/7)
UI Testing       ████████████████████████████████████████ 100% (3/3)
```

---

#Test Execution Summary

# Module-wise Breakdown

| Module | Total | Executed | Passed | Failed | Pass % | Bugs |
|:---|:---|:---|:---|:---|:---|:---|
| Login Module | 14 | 14 | 14 | 0 | 100% | 5 |
| Products Module | 16 | 16 | 16 | 0 | 100% | 0 |
| Cart Module | 5 | 5 | 5 | 0 | 100% | 0 |
| Checkout Module | 7 | 7 | 7 | 0 | 100% | 0 |
| UI Testing | 3 | 3 | 3 | 0 | 100% | 2 |
| **Total** | **45** | **45** | **45** | **0** | **100%** | **7** |

# Priority-wise Distribution

| Priority | Total | Passed | Failed | Pass % |
|:---|:---|:---|:---|:---|
| High | 28 | 28 | 0 | 100% |
| Medium | 12 | 12 | 0 | 100% |
| Low | 5 | 5 | 0 | 100% |

---

# Bugs Summary

| Bug ID | Title | Severity | Priority | Status | Test Case ID |
|:---|:---|:---|:---|:---|:---|
| BUG-001 | Incorrect Error Message Format for Invalid Credentials | Medium | High | Open | TC_LOGIN_002 |
| BUG-002 | Incorrect Error Message Format for Empty Credentials | Medium | High | Open | TC_LOGIN_003 |
| BUG-003 | Incorrect Error Message Format for Locked-Out User | Medium | Medium | Open | TC_LOGIN_004 |
| BUG-004 | Broken Product Images for Problem User | Medium | Medium | Open | TC_LOGIN_007 |
| BUG-005 | Performance Delay for Performance Glitch User | Low | Medium | Open | TC_LOGIN_008 |
| BUG-006 | Distorted UI for Visual User | Low | Low | Open | TC_LOGIN_010 |
| BUG-007 | Typographical Error in Test Data | Low | Low | Open | TC_LOGIN_006 |

# Bug Statistics

```
Priority Distribution:
High   ████████████████████████████████ 2 (29%)
Medium ██████████████████████████████████████████ 3 (43%)
Low    ████████████████████████████████ 2 (29%)

Severity Distribution:
Medium ██████████████████████████████████████████ 4 (57%)
Low    ████████████████████████████████████ 3 (43%)
```

---

# UI Testing Summary

| UI Test Area | Status | Issues Found |
|:---|:---|:---|
| **Login Page UI** |  Pass | 2 (Error message prefix) |
| **Products Page UI** |  Pass | 4 (Broken images, distorted UI, etc.) |
| **Responsive Design** |  Pass | 0 |
| **Special Users** |  Pass | 4 (UI issues documented) |

---

# Screenshots


# Reports

| Report | Description | Link |
|:---|:---|:---|
| **Test Plan** | Master test plan document | [View](./Test_Plan/Test_Plan.md) |
| **Test Scenarios** | High-level test scenarios | [View](./Test_Scenarios/Test_Scenarios.md) |
| **Test Cases** | All test cases with steps and results | [View](./Test_Cases/SauceDemo_TestCases.xlsx) |
| **Bug Reports** | Detailed bug reports | [View](./Bug_Reports/Bug_Report.xlsx) |
| **Execution Report** | Test execution summary | [View](./Test_Execution_Report/Execution_Report.xlsx) |
| **UI Testing Report** | UI testing checklists | [View](./UI_Testing/) |

---

#Test Environment

| Component | Details |
|:---|:---|
| **Application URL** | https://www.saucedemo.com/ |
| **Browser** | Chrome 114.0 |
| **Operating System** | Windows 11 |
| **Screen Resolution** | 1920 x 1080 |
| **Network Speed** | 100 Mbps |
| **Tools Used** | GitHub, Excel, Chrome DevTools |
| **Test Data** | Valid credentials, Invalid credentials, Checkout data |

---

#Risks & Issues

| Risk | Impact | Mitigation | Status |
|:---|:---|:---|:---|
| Error message inconsistency | User confusion | Fix error message format | Open |
| Performance delay | Poor user experience | Optimize performance | Open |
| Broken images | Visual regression | Fix image loading | Open |
| UI distortion | Inconsistent UX | Fix UI rendering | Open |

---

# Recommendations

# High Priority (Must Fix)

- [ ] **BUG-001**: Remove "Epic sadface:" prefix from invalid credentials error
- [ ] **BUG-002**: Remove "Epic sadface:" prefix from empty credentials error

# Medium Priority (Should Fix)

- [ ] **BUG-003**: Remove "Epic sadface:" prefix from locked user error
- [ ] **BUG-004**: Fix broken images for problem_user
- [ ] **BUG-005**: Optimize performance for performance_glitch_user

# Low Priority (Nice to Have)

- [ ] **BUG-006**: Fix UI distortion for visual_user
- [ ] **BUG-007**: Fix typo in test data

---

# Team Members

| Role | Name |
|:---|:---|
| **QA Tester** | Rojina Adhikari |

---

# Timeline

| Phase | Start Date | End Date | Status |
|:---|:---|:---|:---|
| Test Planning | July 13, 2026 | July 13, 2026 |  Completed |
| Test Case Creation | July 13, 2026 | July 14, 2026 |  Completed |
| Test Execution | July 14, 2026 | July 15, 2026 |  Completed |
| Bug Reporting | July 16, 2026 | July 16, 2026 |  Completed |
| UI Testing | July 14, 2026 | July 15, 2026 |  Completed |
| Report Generation | July 16, 2026 | July 16, 2026 |  Completed |

---

##  Quick Links

- [Application](https://www.saucedemo.com/)
- [Test Plan](./Test_Plan/Test_Plan.md)
- [Test Scenarios](./Test_Scenarios/Test_Scenarios.md)
- [Test Cases](./Test_Cases/SauceDemo_TestCases.xlsx)
- [Bug Reports](./Bug_Reports/Bug_Report.xlsx)
- [Execution Report](./Test_Execution_Report/Execution_Report.xlsx)
- [Screenshots](./Screenshots/)
- [UI Testing](./UI_Testing/)

---

# License

This project is for educational and testing purposes only.

---

##  Contact

| Name | Role | Contact |
|:---|:---|:---|
| Rojina Adhikari | QA Tester| [rojinatech03@gmail.com] |

---

**Last Updated:** July 17, 2026  
**Version:** 1.0  
**Status:**  **PASSED**

---

##  Final Status

```
┌─────────────────────────────────────────────────────────────────┐
│                      PROJECT STATUS                             │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│    Test execution completed                                  │
│   All 45 test cases passed                                  │
│    7 bugs identified (0 critical, 2 high priority)         │
│    No blocking issues found                                  │
│    UI issues identified                                     │
│                                                                 │
│   Status: PASSED                                            │
│                                                                 │
│   Application is FUNCTIONALLY STABLE but has UI/UX issues     │
│   Recommended to fix high-priority bugs before release        │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---

**Thank you for reviewing this project!** 
