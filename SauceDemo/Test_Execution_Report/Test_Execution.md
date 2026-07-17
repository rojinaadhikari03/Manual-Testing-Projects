# Test Execution Report - SauceDemo Manual Testing

**Version:** 1.0  
**Date:** July 17, 2026  
**Author:** Rojina Adhikari  
**Status:** Completed

---

##  Executive Summary

| Metric | Value |
|:---|:---|
| **Project Name** | SauceDemo Manual Testing |
| **Test Type** | Manual Testing |
| **Module Tested** | Login, Products, Cart, Checkout, UI |
| **Start Date** | July 14, 2026 |
| **End Date** | July 16, 2026 |
| **Executed By** | Rojina Adhikari |
| **Environment** | Chrome 114.0, Windows 11 |
| **Total Test Cases** | 45 |
| **Executed** | 45 |
| **Passed** | 45 |
| **Failed** | 0 |
| **Blocked** | 0 |
| **Not Executed** | 0 |
| **Pass Percentage** | 100% |
| **Bugs Found** | 7 |
| **Critical Bugs** | 0 |
| **High Priority Bugs** | 2 |
| **Medium Priority Bugs** | 3 |
| **Low Priority Bugs** | 2 |
| **Overall Status** | PASSED |

---

##  Module-wise Summary

| Module | Total | Executed | Passed | Failed | Blocked | Pass % | Bugs Found |
|:---|:---|:---|:---|:---|:---|:---|:---|
| Login Module | 14 | 14 | 14 | 0 | 0 | 100% | 5 |
| Products Module | 16 | 16 | 16 | 0 | 0 | 100% | 0 |
| Cart Module | 5 | 5 | 5 | 0 | 0 | 100% | 0 |
| Checkout Module | 7 | 7 | 7 | 0 | 0 | 100% | 0 |
| UI Testing | 3 | 3 | 3 | 0 | 0 | 100% | 2 |
| **Total** | **45** | **45** | **45** | **0** | **0** | **100%** | **7** |

---

##  Priority-wise Distribution

| Priority | Total | Passed | Failed | Pass % |
|:---|:---|:---|:---|:---|
| High | 28 | 28 | 0 | 100% |
| Medium | 12 | 12 | 0 | 100% |
| Low | 5 | 5 | 0 | 100% |
| **Total** | **45** | **45** | **0** | **100%** |

---

##  Pass Rate Visualization
Overall Pass Rate: 100% (45/45)

Pass: 100%
Fail:0%
Blocked:0%

### Module-wise Pass Rate

| Module | Pass Rate |
|:---|:---|
| Login Module | 100% (14/14) |
| Products Module | 100% (16/16) |
| Cart Module | 100% (5/5) |
| Checkout Module | 100% (7/7) |
| UI Testing | 100% (3/3) |

---

##  Detailed Execution Log

| Test Case ID | Module | Test Scenario | Priority | Status | Execution Date | Executed By | Bug ID |
|:---|:---|:---|:---|:---|:---|:---|:---|
| TC_LOGIN_001 | Login | Verify login with valid credentials | High | Pass | 2026-07-14 | Rojina Adhikari | - |
| TC_LOGIN_002 | Login | Verify login with invalid credentials | High | Pass | 2026-07-14 | Rojina Adhikari | BUG-001 |
| TC_LOGIN_003 | Login | Verify login with empty credentials | High | Pass | 2026-07-14 | Rojina Adhikari | BUG-002 |
| TC_LOGIN_004 | Login | Verify login with locked-out user | Medium | Pass | 2026-07-14 | Rojina Adhikari | BUG-003 |
| TC_LOGIN_005 | Login | Verify login with valid username and empty password | High | Pass | 2026-07-14 | Rojina Adhikari | BUG-002 |
| TC_LOGIN_006 | Login | Verify login with valid username and invalid password | High | Pass | 2026-07-14 | Rojina Adhikari | BUG-001, BUG-007 |
| TC_LOGIN_007 | Login | Verify login with problem user | Low | Pass | 2026-07-14 | Rojina Adhikari | BUG-004 |
| TC_LOGIN_008 | Login | Verify login with performance glitch user | Medium | Pass | 2026-07-14 | Rojina Adhikari | BUG-005 |
| TC_LOGIN_009 | Login | Verify login with error user | Low | Pass | 2026-07-14 | Rojina Adhikari | BUG-004 |
| TC_LOGIN_010 | Login | Verify login with visual user | Low | Pass | 2026-07-14 | Rojina Adhikari | BUG-006 |
| TC_LOGIN_011 | Login | Verify password masking | Medium | Pass | 2026-07-14 | Rojina Adhikari | - |
| TC_LOGIN_012 | Login | Verify login using Enter key | Low | Pass | 2026-07-14 | Rojina Adhikari | - |
| TC_LOGIN_013 | Login | Verify login with copied username | Low | Pass | 2026-07-14 | Rojina Adhikari | - |
| TC_LOGIN_014 | Login | Verify login with copied password | Low | Pass | 2026-07-14 | Rojina Adhikari | - |
| TC_PROD_001 | Products | Verify product grid layout | High | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_PROD_002 | Products | Verify product cards display | High | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_PROD_003 | Products | Verify number of products displayed | High | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_PROD_004 | Products | Verify product images display | High | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_PROD_005 | Products | Verify product titles display | High | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_PROD_006 | Products | Verify product descriptions display | High | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_PROD_007 | Products | Verify product prices display | High | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_PROD_008 | Products | Verify Add to Cart button display | High | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_PROD_009 | Products | Verify Add to Cart functionality | High | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_PROD_010 | Products | Verify Remove button functionality | High | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_PROD_011 | Products | Verify cart badge counter updates | Medium | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_PROD_012 | Products | Verify filter dropdown options | Medium | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_PROD_013 | Products | Verify sort by Name (A to Z) | Medium | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_PROD_014 | Products | Verify sort by Name (Z to A) | Medium | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_PROD_015 | Products | Verify sort by Price (Low to High) | Medium | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_PROD_016 | Products | Verify sort by Price (High to Low) | Medium | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_CART_001 | Cart | Verify cart page displays items correctly | High | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_CART_002 | Cart | Verify remove from cart functionality | High | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_CART_003 | Cart | Verify Continue Shopping button | High | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_CART_004 | Cart | Verify Checkout button navigation | High | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_CART_005 | Cart | Verify empty cart message | Medium | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_CHK_001 | Checkout | Verify checkout information form display | High | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_CHK_002 | Checkout | Verify checkout with valid information | High | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_CHK_003 | Checkout | Verify checkout with missing First Name | High | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_CHK_004 | Checkout | Verify checkout with missing Last Name | High | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_CHK_005 | Checkout | Verify checkout with missing Zip Code | High | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_CHK_006 | Checkout | Verify checkout overview display | High | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_CHK_007 | Checkout | Verify total calculation | High | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_UI_001 | UI Testing | Verify Login page UI elements | Medium | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_UI_002 | UI Testing | Verify Products page UI elements | Medium | Pass | 2026-07-15 | Rojina Adhikari | - |
| TC_UI_003 | UI Testing | Verify responsive design | Medium | Pass | 2026-07-15 | Rojina Adhikari | - |

---

## Bug Summary

| Bug ID | Title | Severity | Priority | Status | Test Case ID |
|:---|:---|:---|:---|:---|:---|
| BUG-001 | Incorrect Error Message Format for Invalid Credentials | Medium | High | Open | TC_LOGIN_002 |
| BUG-002 | Incorrect Error Message Format for Empty Credentials | Medium | High | Open | TC_LOGIN_003 |
| BUG-003 | Incorrect Error Message Format for Locked-Out User | Medium | Medium | Open | TC_LOGIN_004 |
| BUG-004 | Broken Product Images for Problem User | Medium | Medium | Open | TC_LOGIN_007 |
| BUG-005 | Performance Delay for Performance Glitch User | Low | Medium | Open | TC_LOGIN_008 |
| BUG-006 | Distorted UI for Visual User | Low | Low | Open | TC_LOGIN_010 |
| BUG-007 | Typographical Error in Test Data | Low | Low | Open | TC_LOGIN_006 |

---

## 🔧 Environment Details

| Component | Details |
|:---|:---|
| **Application URL** | https://www.saucedemo.com/ |
| **Browser** | Chrome 114.0 |
| **Operating System** | Windows 11 |
| **Screen Resolution** | 1920 x 1080 |
| **Network Speed** | 100 Mbps |
| **Test Data** | Valid credentials, Invalid credentials, Checkout data |
| **Tools Used** | GitHub, Excel, Chrome DevTools |

---

##  Risk Summary

| Risk/Issue | Impact | Mitigation | Status |
|:---|:---|:---|:---|
| Error message inconsistency | User confusion | Fix error message format | Open |
| Performance delay | Poor user experience | Optimize performance | Open |
| Broken images | Visual regression | Fix image loading | Open |
| UI distortion | Inconsistent UX | Fix UI rendering | Open |

---

## Recommendations

| Priority | Recommendation | Bug ID |
|:---|:---|:---|
| High | Remove "Epic sadface:" prefix from invalid credentials error | BUG-001 |
| High | Remove "Epic sadface:" prefix from empty credentials error | BUG-002 |
| Medium | Remove "Epic sadface:" prefix from locked user error | BUG-003 |
| Medium | Fix broken images for problem_user | BUG-004 |
| Medium | Optimize performance for performance_glitch_user | BUG-005 |
| Low | Fix UI distortion for visual_user | BUG-006 |
| Low | Fix typo in test data | BUG-007 |

---

##  Final Status

| Aspect | Status |
|:---|:---|
| **Functional Testing** | Passed |
| **UI Testing** | Passed (with issues) |
| **Bug Status** | 7 Open Bugs |
| **Blocking Issues** | None |
| **Overall Status** | PASSED |

---

##  Related Documents

| Document | Link |
|:---|:---|
| Test Plan | [./Test_Plan/Test_Plan.md](./Test_Plan/Test_Plan.md) |
| Test Scenarios | [./Test_Scenarios/Test_Scenarios.xlsx](./Test_Scenarios/Test_Scenarios.xlsx) |
| Test Cases | [./Test_Cases/SauceDemo_TestCases.xlsx](./Test_Cases/SauceDemo_TestCases.xlsx) |
| Bug Reports | [./Bug_Reports/Bug_Report.xlsx](./Bug_Reports/Bug_Report.xlsx) |

---

**End of Test Execution Report**

**Version:** 1.0  
**Last Updated:** July 17, 2026  
**Status:** Completed

---

**Thank you for reviewing this document!**
