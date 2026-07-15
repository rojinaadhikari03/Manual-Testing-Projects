# Test Execution Report

SauceDemo Login Module Testing


## 1. Executive Summary

| Field | Value |
|:---|:---|
| Project Name | SauceDemo Web Application |
| Module Tested | Login Module |
| Report Title | Login Module Test Execution Report |
| Report Date| July 14, 2026 |
| Prepared By | Rojina Adhikari |
| Version | 1.0 |
| Status | PASSED WITH ISSUES |

---

# 1.1 Test Objectives

| # | Objective | Status |
|:---|:---|:---|
| 1 | Verify login functionality with valid credentials | Completed |
| 2 | Verify login functionality with invalid credentials | Completed |
| 3 | Verify login functionality with empty credentials | Completed |
| 4 | Verify login functionality with locked-out user |  Completed |
| 5 | Verify login with special user accounts (problem_user, performance_glitch_user, error_user, visual_user) |  Completed |
| 6 | Verify password validation scenarios | ✅Completed |

---

### 1.2 Key Findings

| # | Finding |
|:---|:---|
| 1 | All 10 test cases executed successfully (100% pass rate) |
| 2 |  All error messages contain inconsistent "Epic sadface:" prefix |
| 3 |  Visual bugs present for problem_user (broken images) |
| 4 |  Performance delay observed with performance_glitch_user (5-8 seconds) |
| 5 |  UI/Functional defects present for error_user |
| 6 | UI distortion present for visual_user |
| 7 | ✅ Core login functionality works as expected for all user types |

---

### 1.3 Overall Status

```
┌─────────────────────────────────────────────────────────────────┐
│                 OVERALL TEST STATUS                             │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  10/10 Test Cases Executed                                 │
│   100% Pass Rate                                            │
│   100% Test Coverage for Login Module                      │
│   7 Bugs Identified                                       │
│    No Blocking Issues Found                                 │
│                                                                 │
│   ┌─────────────────────────────────────────────────────────┐  │
│   │                                                         │  │
│   │             PROCEED WITH CAUTION                     │  │
│   │                                                         │  │
│   └─────────────────────────────────────────────────────────┘  │
│                                                                 │
│   Recommendation: Fix high-priority bugs before production    │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---

## 2. Test Execution Summary

### 2.1 Summary Statistics

| Metric | Count | Percentage |
|:---|:---|:---|
| Total Test Cases | 10 | 100% |
| Test Cases Executed | 10 | 100% |
| Passed | 10 | 100% |
| Failed | 0 | 0% |
| Blocked | 0 | 0% |
| Not Executed | 0 | 0% |

### 2.2 Pass/Fail Visualization

```
Pass Rate: 100% (10/10)

 100% Pass
0% Fail
 0% Blocked
 0% Not Executed
```

### 2.3 Module-wise Breakdown

| Module | Total Test Cases | Passed | Failed | Blocked | Pass % |
|:---|:---|:---|:---|:---|:---|
| Login - Positive Scenarios | 1 | 1 | 0 | 0 | 100% |
| Login - Negative Scenarios | 5 | 5 | 0 | 0 | 100% |
| Login - Special Users | 4 | 4 | 0 | 0 | 100% |
| Total| 10 | 10 | 0 | 0 | 100% |

---

## 3. Detailed Test Results

#3.1 Positive Test Cases

| Test Case ID | Test Scenario | Priority | Status | Actual Result |
|:---|:---|:---|:---|:---|
| TC_LOGIN_001 | Verify login with valid credentials | High | Pass | User successfully logged in and was redirected to the Products page (https://www.saucedemo.com/inventory.html). All 6 products were displayed correctly with images, descriptions, prices, and Add to Cart buttons. Cart icon displayed "0" initially. |

### 3.2 Negative Test Cases

| Test Case ID | Test Scenario | Priority | Status | Actual Result |
|:---|:---|:---|:---|:---|
| TC_LOGIN_002 | Verify login with invalid credentials | High |  Pass | Error message displayed: "Epic sadface: Username and password do not match any user in this service". User remained on the login page. URL did not change. |
| TC_LOGIN_003 | Verify login with empty credentials | High |  Pass | Error message displayed: "Epic sadface: Username is required". User remained on the login page. Both fields remained empty. |
| TC_LOGIN_004 | Verify login with locked-out user | Medium |  Pass | Error message displayed: "Epic sadface: Sorry, this user has been locked out". Login was prevented. |
| TC_LOGIN_005 | Verify login with valid username and empty password | High |  Pass | Error message displayed: "Epic sadface: Password is required". Password field remained empty. |
| TC_LOGIN_006 | Verify login with valid username and invalid password | High |  Pass | Error message displayed: "Epic sadface: Username and password do not match any user in this service". Login was prevented. |

### 3.3 Special User Test Cases

| Test Case ID | Test Scenario | Priority | Status | Actual Result |
|:---|:---|:---|:---|:---|
| TC_LOGIN_007 | Verify login with problem user | Low | Pass | Login successful but product images were broken/replaced with placeholder icons. Product names and prices displayed correctly. |
| TC_LOGIN_008 | Verify login with performance glitch user | Medium |  Pass | Login took approximately 5-8 seconds to complete. User eventually navigated to Products page successfully. |
| TC_LOGIN_009 | Verify login with error user | Low | Pass | Login successful. Add to Cart button for Sauce Labs Backpack was missing. Some images broken. Multiple elements had incorrect styling. |
| TC_LOGIN_010 | Verify login with visual user | Low |  Pass | Login successful. Product images had different sizes/shapes. Add to Cart buttons styled differently. Overall layout distorted. |

---

## 4. Test Environment Details

### 4.1 Environment Configuration

| Component | Details |
|:---|:---|
| Application URL | https://www.saucedemo.com/ |
| Test Environment | Production (Demo Site) |
| Browser| Chrome 114.0 |
| Operating System | Windows 11 |
|Screen Resolution | 1920 x 1080 |
| Network Speed | 100 Mbps |
| Device | Desktop / Laptop |

### 4.2 Browser/OS Test Matrix

| Browser | Version | OS | Tested |
|:---|:---|:---|:---|
| Chrome | 114.0 | Windows 11 | done |
| Edge | 114.0 | Windows 11 |  Pending |
| Firefox | 113.0 | Windows 11 |  Pending |
| Safari | 16.0 | macOS 13 |  Pending |

---

## 5. Defect Summary

### 5.1 Bug Statistics

| Priority | Open | In Progress | Fixed | Closed | Total |
|:---|:---|:---|:---|:---|:---|
| High | 2 | 0 | 0 | 0 | 2 |
| Medium | 3 | 0 | 0 | 0 | 3 |
| Low | 2 | 0 | 0 | 0 | 2 |
| Total| 7 | 0 | 0 | 0 | 7 |

### 5.2 Bug Severity Distribution

```
Severity Distribution

Medium ██████████████████████████████████████████ 4 (57%)
Low    ████████████████████████████████████ 3 (43%)
High   ████████████████████ 0 (0%)
```

### 5.3 Bug Priority Distribution

```
Priority Distribution

High   ████████████████████████████████ 2 (29%)
Medium ██████████████████████████████████████████ 3 (43%)
Low    ████████████████████████████████ 2 (29%)
```

### 5.4 Detailed Bug List

| Bug ID | Title | Severity | Priority | Status | Test Case ID |
|:---|:---|:---|:---|:---|:---|
| BUG-001 | Incorrect Error Message Format for Invalid Credentials | Medium | High | Open | TC_LOGIN_002 |
| BUG-002 | Incorrect Error Message Format for Empty Credentials | Medium | High | Open | TC_LOGIN_003 |
| BUG-003 | Incorrect Error Message Format for Locked-Out User | Medium | Medium | Open | TC_LOGIN_004 |
| BUG-004 | Broken Product Images for Problem User After Login | Medium | Medium | Open | TC_LOGIN_007 |
| BUG-005 | Performance Delay When Logging in with Performance Glitch User | Low | Medium | Open | TC_LOGIN_008 |
| BUG-006 | Distorted UI and Layout for Visual User After Login | Low | Low | Open | TC_LOGIN_010 |
| BUG-007 | Typographical Error in Expected Result for TC_LOGIN_006 | Low | Low | Open | TC_LOGIN_006 |

### 5.5 Bug Impact Analysis

| Bug ID | Impact | Severity | Urgency |
|:---|:---|:---|:---|
| BUG-001 | Inconsistent user experience, user confusion | Medium | High |
| BUG-002 | Inconsistent user experience, user confusion | Medium | High |
| BUG-003 | Inconsistent user experience | Medium | Medium |
| BUG-004 | Visual regression, poor UX | Medium | Medium |
| BUG-005 | Performance issue, poor UX | Low | Medium |
| BUG-006 | Visual distortion, poor UX | Low | Low |
| BUG-007 | Documentation issue | Low | Low |

---

## 6. Test Coverage Matrix

| Feature/Scenario | Tested | Not Tested | Coverage % |
|:---|:---|:---|:---|
| Valid Login | done | - | 100% |
| Invalid Credentials |done | - | 100% |
| Empty Credentials | done | - | 100% |
| Locked-out User | done | - | 100% |
| Empty Password | done | - | 100% |
| Invalid Password | done | - | 100% |
| Problem User | done| - | 100% |
| Performance Glitch User | done | - | 100% |
| Error User | done | - | 100% |
| Visual User | done | - | 100% |
| Password Masking | done | - | 100% |
| Total| 10 | 0 | 100% |

---

## 7. Risks & Issues

### 7.1 Blocking Issues

| Issue ID | Description | Impact | Resolution Status |
|:---|:---|:---|:---|
| N/A | No blocking issues identified | N/A | N/A |

### 7.2 Risks Identified

| Risk | Probability | Impact | Mitigation |
|:---|:---|:---|:---|
| Inconsistent error messages may confuse users | High | Medium | Fix error message format (BUG-001, BUG-002) |
| Performance delay may frustrate users | Medium | Low | Optimize login performance (BUG-005) |
| Broken images may reduce user trust | High | Medium | Fix image loading (BUG-004) |
| UI distortion affects visual consistency | Medium | Low | Fix UI rendering (BUG-006) |
| Special user accounts not intended for production | Low | Low | Document as known issues |

### 7.3 Issues Found During Testing

| Issue | Description | Affected Test Cases |
|:---|:---|:---|
| Error Message Inconsistency | All error messages have "Epic sadface:" prefix | TC_LOGIN_002, 003, 004, 005, 006 |
| Image Loading Issue | Product images broken for problem_user | TC_LOGIN_007 |
| Performance Delay | 5-8 second login delay | TC_LOGIN_008 |
| Missing UI Elements | Add to Cart button missing for error_user | TC_LOGIN_009 |
| UI Distortion | Different image sizes, button styles, layout | TC_LOGIN_010 |

---

## 8. Recommendations

### 8.1 High Priority (Must Fix Before Production)

| # | Bug ID | Recommendation |
|:---|:---|:---|
| 1 | BUG-001 | Remove "Epic sadface:" prefix from invalid credentials error message |
| 2 | BUG-002 | Remove "Epic sadface:" prefix from empty credentials error message |

### 8.2 Medium Priority (Should Fix)

| # | Bug ID | Recommendation |
|:---|:---|:---|
| 3 | BUG-003 | Remove "Epic sadface:" prefix from locked-out user error message |
| 4 | BUG-004 | Fix image loading for problem_user |
| 5 | BUG-005 | Investigate and optimize performance for performance_glitch_user |

### 8.3 Low Priority (Nice to Have)

| # | Bug ID | Recommendation |
|:---|:---|:---|
| 6 | BUG-006 | Fix UI distortion issues for visual_user |
| 7 | BUG-007 | Correct typo in test data (wrong_passwprd → wrong_password) |

### 8.4 Process Improvements

| # | Recommendation |
|:---|:---|
| 1 | Implement client-side validation for empty fields |
| 2 | Add "Show/Hide Password" toggle for better UX |
| 3 | Add "Remember Me" functionality |
| 4 | Add "Forgot Password" link |
| 5 | Standardize error messages across the application |

---

## 9. Go/No-Go Decision

```
┌─────────────────────────────────────────────────────────────────┐
│                    GO / NO-GO DECISION                         │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   Test Execution Status: ✅ COMPLETED                          │
│   Pass Rate: 100%                                              │
│   Critical Bugs: 0                                             │
│   High Priority Bugs: 2                                        │
│   Blocking Issues: 0                                           │
│                                                                 │
│   ┌─────────────────────────────────────────────────────────┐  │
│   │                                                         │  │
│   │                 PROCEED WITH CAUTION                  │  │
│   │                                                         │  │
│   │    Functionality works but UI/UX issues exist          │  │
│   │    Fix high-priority bugs before production release    │  │
│   │                                                         │  │
│   └─────────────────────────────────────────────────────────┘  │
│                                                                 │
│   Decision:  PROCEED WITH CAUTION                            │
│                                                                 │
│   Justification:                                               │
│   - Core login functionality is working correctly              │
│   - No blocking issues found                                   │
│   - 100% test pass rate                                        │
│   - UI/UX issues need to be addressed                          │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---
## 11. Appendices

### Appendix A: Test Execution Log

| Date | Time | Test Case ID | Executed By | Status | Notes |
|:---|:---|:---|:---|:---|:---|
| 2026-07-14 | 10:00 AM | TC_LOGIN_001 | Rojina Adhikari | Pass | - |
| 2026-07-14 | 10:15 AM | TC_LOGIN_002 | Rojina Adhikari  | Pass | Error message has "Epic sadface:" prefix |
| 2026-07-14 | 10:30 AM | TC_LOGIN_003 | Rojina Adhikari |  Pass | Error message has "Epic sadface:" prefix |
| 2026-07-14 | 10:45 AM | TC_LOGIN_004 | Rojina Adhikari  |  Pass | Error message has "Epic sadface:" prefix |
| 2026-07-14 | 11:00 AM | TC_LOGIN_005 |Rojina Adhikari  |  Pass | Error message has "Epic sadface:" prefix |
| 2026-07-14 | 11:15 AM | TC_LOGIN_006 | Rojina Adhikari  | Pass | Error message has "Epic sadface:" prefix |
| 2026-07-14 | 11:30 AM | TC_LOGIN_007 | Rojina Adhikari | Pass | Broken images observed |
| 2026-07-14 | 11:45 AM | TC_LOGIN_008 | Rojina Adhikari |  Pass | 5-8 sec performance delay |
| 2026-07-14 | 12:15 PM | TC_LOGIN_010 | Rojina Adhikari |  Pass | UI distortion observed |

### Appendix B: Test Data Used

| Test Case ID | Username | Password |
|:---|:---|:---|
| TC_LOGIN_001 | standard_user | secret_sauce |
| TC_LOGIN_002 | invalid_user | wrong_password |
| TC_LOGIN_003 | (empty) | (empty) |
| TC_LOGIN_004 | locked_out_user | secret_sauce |
| TC_LOGIN_005 | standard_user | (empty) |
| TC_LOGIN_006 | standard_user | wrong_password |
| TC_LOGIN_007 | problem_user | secret_sauce |
| TC_LOGIN_008 | performance_glitch_user | secret_sauce |
| TC_LOGIN_009 | error_user | secret_sauce |
| TC_LOGIN_010 | visual_user | secret_sauce |

### Appendix C: Screenshots Reference

| Screenshot | Description |
|:---|:---|
| Screenshots/Loginwithstandad_user.png | Login with valid credentials |
| Screenshots/Invalidusername_invalidpassword.png | Invalid credentials error |
| Screenshots/Empty_Credentials.png | Empty credentials error |
| Screenshots/Locked_outuser.png | Locked user error |
| Screenshots/error_user.png | error user error |
| Screenshots/after_erroruser.png | After login with error_user |
| Screenshots/visual_user.png | Login in with visual_error  |
| Screenshots/Error_Message.png | "Epic sadface:" prefix issue |
| Screenshots/Broken_Images.png | Broken product images |

---

## 12. Summary Dashboard

### Test Case Status

```
┌─────────────────────────────────────────────────────────────────┐
│                     TEST CASE STATUS                           │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  Passed:  10 (100%)                                          │
│   Failed:  0   (0%)                                           │
│  Blocked: 0   (0%)                                          │
│  Not Exec: 0   (0%)                                         │
│                                                                 │
│  ┌─────────────────────────────────────────────────────────┐   │
│                                     │   │
│  │   ████████████████████████████████████████████████████ │   │
│  │   100% Pass Rate                                       │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### Bug Status

```
┌─────────────────────────────────────────────────────────────────┐
│                       BUG STATUS                                │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  Open:          7                                           │
│   In Progress:   0                                           │
│   Fixed:         0                                           │
│   Closed:        0                                           │
│                                                                 │
│  Total Bugs Found: 7                                           │
│                                                                 │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │                                                         │   │
│  │  Priority Distribution                                  │   │
│  │  ████████████████████████████████  High   (2)          │   │
│  │  ██████████████████████████████████████████  Medium (3) │   │
│  │  ████████████████████████████████  Low    (2)          │   │
│  │                                                         │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---

## 13. Quick Reference Card

### Test Execution Summary

| Total Test Cases | 10 |
|:---|:---|
| Executed | 10 |
| Passed | 10 |
|Failed | 0 |
| Pass Rate | 100% |
| Bugs Found | 7 |
| Blocking Issues | 0 |

### Key Recommendations

| Priority | Action |
|:---|:---|
|  High | Fix error message formats (BUG-001, BUG-002) |
|  Medium | Fix broken images (BUG-004), Optimize performance (BUG-005) |
|  Low | Fix UI distortion (BUG-006), Fix typo (BUG-007) |


