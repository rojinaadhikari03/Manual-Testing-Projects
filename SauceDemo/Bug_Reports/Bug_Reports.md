#  Bug Reports - SauceDemo Manual Testing

**Version:** 1.0  
**Date:** July 17, 2026  
**Author:** Rojina Adhikari  
**Status:** Open

---

##  Bug Reports Summary

| Bug ID | Title | Module | Severity | Priority | Status | Test Case ID |
|:---|:---|:---|:---|:---|:---|:---|
| BUG-001 | Incorrect Error Message Format for Invalid Credentials | Login | Medium | High | Open | TC_LOGIN_002 |
| BUG-002 | Incorrect Error Message Format for Empty Credentials | Login | Medium | High | Open | TC_LOGIN_003 |
| BUG-003 | Incorrect Error Message Format for Locked-Out User | Login | Medium | Medium | Open | TC_LOGIN_004 |
| BUG-004 | Broken Product Images for Problem User | Login/Inventory | Medium | Medium | Open | TC_LOGIN_007 |
| BUG-005 | Performance Delay for Performance Glitch User | Login | Low | Medium | Open | TC_LOGIN_008 |
| BUG-006 | Distorted UI for Visual User | Login/Inventory | Low | Low | Open | TC_LOGIN_010 |
| BUG-007 | Typographical Error in Test Data | Login | Low | Low | Open | TC_LOGIN_006 |

---

## Bug Statistics

### Severity Distribution

| Severity | Count | Percentage |
|:---|:---|:---|
| Critical | 0 | 0% |
| High | 0 | 0% |
| Medium | 4 | 57% |
| Low | 3 | 43% |
| **Total** | **7** | **100%** |

### Priority Distribution

| Priority | Count | Percentage |
|:---|:---|:---|
| High | 2 | 29% |
| Medium | 3 | 43% |
| Low | 2 | 29% |
| **Total** | **7** | **100%** |

### Status Distribution

| Status | Count | Percentage |
|:---|:---|:---|
| Open | 7 | 100% |
| In Progress | 0 | 0% |
| Fixed | 0 | 0% |
| Closed | 0 | 0% |
| **Total** | **7** | **100%** |

### Module-wise Distribution

| Module | Count |
|:---|:---|
| Login | 5 |
| Login / Inventory | 2 |
| **Total** | **7** |

---

##  Detailed Bug Reports

### BUG-001: Incorrect Error Message Format for Invalid Credentials

| Field | Value |
|:---|:---|
| **Bug ID** | BUG-001 |
| **Title** | Incorrect Error Message Format for Invalid Credentials |
| **Module** | Login |
| **Severity** | Medium |
| **Priority** | High |
| **Status** | Open |
| **Test Case ID** | TC_LOGIN_002 |
| **Reported By** | Rojina Adhikari |
| **Reported Date** | July 16, 2026 |
| **Environment** | Chrome 114.0, Windows 11 |

**Description:**
The error message displayed for invalid credentials contains an additional prefix "Epic sadface:" which is not mentioned in the expected result. The expected result only states "Username and password do not match any user in this service."

**Steps to Reproduce:**
1. Navigate to SauceDemo login page: https://www.saucedemo.com/
2. Enter invalid username: invalid_user
3. Enter invalid password: wrong_password
4. Click the 'Login' button

**Expected Result:**
Error message should be displayed: "Username and password do not match any user in this service." User should remain on the login page.

**Actual Result:**
Error message displayed: "Epic sadface: Username and password do not match any user in this service". User remained on the login page. URL did not change.

**Impact:**
Inconsistent error message format. May confuse users. Does not match requirement specification.

**Recommendation:**
Remove the "Epic sadface:" prefix and display the error message as: "Username and password do not match any user in this service."

---

### BUG-002: Incorrect Error Message Format for Empty Credentials

| Field | Value |
|:---|:---|
| **Bug ID** | BUG-002 |
| **Title** | Incorrect Error Message Format for Empty Credentials |
| **Module** | Login |
| **Severity** | Medium |
| **Priority** | High |
| **Status** | Open |
| **Test Case ID** | TC_LOGIN_003 |
| **Reported By** | Rojina Adhikari |
| **Reported Date** | July 16, 2026 |
| **Environment** | Chrome 114.0, Windows 11 |

**Description:**
The error message displayed for empty credentials contains an additional prefix "Epic sadface:" which is not mentioned in the expected result. The expected result only states "Username is required."

**Steps to Reproduce:**
1. Navigate to SauceDemo login page: https://www.saucedemo.com/
2. Leave both username and password fields empty
3. Click the 'Login' button

**Expected Result:**
Error message should be displayed: "Username is required." User should remain on the login page.

**Actual Result:**
Error message displayed: "Epic sadface: Username is required". User remained on the login page. URL did not change.

**Impact:**
Inconsistent error message format. The prefix "Epic sadface:" is confusing for users. Does not match requirement specification.

**Recommendation:**
Remove the "Epic sadface:" prefix and display the error message as: "Username is required."

---

### BUG-003: Incorrect Error Message Format for Locked-Out User

| Field | Value |
|:---|:---|
| **Bug ID** | BUG-003 |
| **Title** | Incorrect Error Message Format for Locked-Out User |
| **Module** | Login |
| **Severity** | Medium |
| **Priority** | Medium |
| **Status** | Open |
| **Test Case ID** | TC_LOGIN_004 |
| **Reported By** | Rojina Adhikari |
| **Reported Date** | July 16, 2026 |
| **Environment** | Chrome 114.0, Windows 11 |

**Description:**
The error message displayed for the locked-out user contains an additional prefix "Epic sadface:" which is not mentioned in the expected result. The expected result only states "Sorry, this user has been locked out."

**Steps to Reproduce:**
1. Navigate to SauceDemo login page: https://www.saucedemo.com/
2. Enter locked-out username: locked_out_user
3. Enter valid password: secret_sauce
4. Click the 'Login' button

**Expected Result:**
Error message should be displayed: "Sorry, this user has been locked out." User should remain on the login page.

**Actual Result:**
Error message displayed: "Epic sadface: Sorry, this user has been locked out". User remained on the login page. URL did not change. Login was prevented as expected.

**Impact:**
Inconsistent error message format. Does not match requirement specification. Minor cosmetic issue.

**Recommendation:**
Remove the "Epic sadface:" prefix and display the error message as: "Sorry, this user has been locked out."

---

### BUG-004: Broken Product Images for Problem User

| Field | Value |
|:---|:---|
| **Bug ID** | BUG-004 |
| **Title** | Broken Product Images for Problem User |
| **Module** | Login / Inventory |
| **Severity** | Medium |
| **Priority** | Medium |
| **Status** | Open |
| **Test Case ID** | TC_LOGIN_007 |
| **Reported By** | Rojina Adhikari |
| **Reported Date** | July 16, 2026 |
| **Environment** | Chrome 114.0, Windows 11 |

**Description:**
When logged in as problem_user, all product images are broken and replaced with placeholder icons. Product names and prices are displayed correctly.

**Steps to Reproduce:**
1. Navigate to SauceDemo login page: https://www.saucedemo.com/
2. Enter username: problem_user
3. Enter password: secret_sauce
4. Click the 'Login' button
5. Observe the Products page

**Expected Result:**
User should login successfully and navigate to Products page with all product images displayed correctly.

**Actual Result:**
User logged in successfully and navigated to Products page. However, product images were broken/replaced with placeholder icons on the inventory page. Product names and prices were displayed correctly.

**Impact:**
Poor user experience. Visual regression. Affects visual quality of the page.

**Recommendation:**
Fix the image loading issue for problem_user. Ensure all product images load correctly.

---

### BUG-005: Performance Delay for Performance Glitch User

| Field | Value |
|:---|:---|
| **Bug ID** | BUG-005 |
| **Title** | Performance Delay for Performance Glitch User |
| **Module** | Login |
| **Severity** | Low |
| **Priority** | Medium |
| **Status** | Open |
| **Test Case ID** | TC_LOGIN_008 |
| **Reported By** | Rojina Adhikari |
| **Reported Date** | July 16, 2026 |
| **Environment** | Chrome 114.0, Windows 11 |

**Description:**
When logged in as performance_glitch_user, the login process takes 5-8 seconds to complete, which is significantly slower than the expected load time.

**Steps to Reproduce:**
1. Navigate to SauceDemo login page: https://www.saucedemo.com/
2. Enter username: performance_glitch_user
3. Enter password: secret_sauce
4. Click the 'Login' button
5. Measure the time taken to redirect to Products page

**Expected Result:**
User should login successfully and navigate to Products page within a reasonable time (under 3 seconds).

**Actual Result:**
Login took approximately 5-8 seconds to complete. User eventually navigated to Products page successfully. All images and functionality loaded correctly after the delay.

**Impact:**
Poor user experience. Slow performance. May lead to user frustration.

**Recommendation:**
Investigate and optimize the login performance for performance_glitch_user to reduce the delay to under 3 seconds.

---

### BUG-006: Distorted UI for Visual User

| Field | Value |
|:---|:---|
| **Bug ID** | BUG-006 |
| **Title** | Distorted UI for Visual User |
| **Module** | Login / Inventory |
| **Severity** | Low |
| **Priority** | Low |
| **Status** | Open |
| **Test Case ID** | TC_LOGIN_010 |
| **Reported By** | Rojina Adhikari |
| **Reported Date** | July 16, 2026 |
| **Environment** | Chrome 114.0, Windows 11 |

**Description:**
When logged in as visual_user, the Products page UI is distorted. Product images have different sizes, buttons are styled differently, and the overall layout is inconsistent.

**Steps to Reproduce:**
1. Navigate to SauceDemo login page: https://www.saucedemo.com/
2. Enter username: visual_user
3. Enter password: secret_sauce
4. Click the 'Login' button
5. Observe the Products page UI

**Expected Result:**
User should login successfully and navigate to Products page with consistent UI as seen with standard_user.

**Actual Result:**
User logged in successfully and navigated to Products page. However:
1. All product images had different sizes/shapes than standard_user
2. Add to Cart buttons were styled differently (different colors and margins)
3. The overall layout appeared distorted

**Impact:**
Poor visual appearance. Inconsistent user experience. Affects visual testing use case.

**Recommendation:**
Fix UI rendering for visual_user to ensure consistent layout and styling.

---

### BUG-007: Typographical Error in Test Data

| Field | Value |
|:---|:---|
| **Bug ID** | BUG-007 |
| **Title** | Typographical Error in Test Data |
| **Module** | Login |
| **Severity** | Low |
| **Priority** | Low |
| **Status** | Open |
| **Test Case ID** | TC_LOGIN_006 |
| **Reported By** | Rojina Adhikari |
| **Reported Date** | July 16, 2026 |
| **Environment** | N/A (Documentation Issue) |

**Description:**
There is a typographical error in the Test Data column for TC_LOGIN_006. The password is spelled as wrong_passwprd instead of wrong_password.

**Steps to Reproduce:**
1. Open the test case document
2. Navigate to TC_LOGIN_006
3. Review the Test Data column

**Expected Result:**
Password should be correctly spelled as: wrong_password

**Actual Result:**
Password is spelled incorrectly in the Test Data: wrong_passwprd (typo - missing 'o')

**Impact:**
Documentation error. May cause confusion during test execution. Minor issue.

**Recommendation:**
Correct the typo in the test data from wrong_passwprd to wrong_password.

---

## Related Documents

| Document | Link |
|:---|:---|
| Test Plan | [./Test_Plan/Test_Plan.md](./Test_Plan/Test_Plan.md) |
| Test Scenarios | [./Test_Scenarios/Test_Scenarios.xlsx](./Test_Scenarios/Test_Scenarios.xlsx) |
| Test Cases | [./Test_Cases/SauceDemo_TestCases.xlsx](./Test_Cases/SauceDemo_TestCases.xlsx) |
| Execution Report | [./Test_Execution_Report/Execution_Report.xlsx](./Test_Execution_Report/Execution_Report.xlsx) |

---

**End of Bug Reports Document**

**Version:** 1.0  
**Last Updated:** July 17, 2026  
**Status:** Open

---

**Thank you for reviewing this document!**
