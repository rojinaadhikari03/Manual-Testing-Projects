#  Login Page UI Testing Checklist - SauceDemo

**Module:** Login Page  
**Test Environment:** Chrome 114.0, Windows 11  
**Date:** July 17, 2026  
**Tester:** Rojina Adhikari  
**Status:** Completed

---

## Visual Elements Checklist

| # | Element | Expected | Actual | Status |
|:---|:---|:---|:---|:---|
| 1 | Page Title | "Swag Labs" displayed at top | "Swag Labs" displayed at top | Pass |
| 2 | Logo | Sauce Labs logo/brand name visible | Sauce Labs logo/brand name visible | Pass |
| 3 | Username Field Label | "Username" placeholder text | "Username" placeholder text | Pass |
| 4 | Username Field Input | Accepts text input | Accepts text input | Pass |
| 5 | Password Field Label | "Password" placeholder text | "Password" placeholder text | Pass |
| 6 | Password Field Input | Accepts text input, masked (dots) | Accepts text input, masked (dots) | Pass |
| 7 | Login Button | Red/orange button with "Login" text | Red/orange button with "Login" text | Pass |
| 8 | Login Button Hover | Hover effect on button | Hover effect works | Pass |
| 9 | Error Messages | Red text displayed above login form | Red text displayed above login form | Pass |
| 10 | Background | White/gray background with centered login box | White/gray background with centered login box | Pass |

---

##  Layout & Alignment Checklist

| # | Element | Expected | Actual | Status |
|:---|:---|:---|:---|:---|
| 11 | Page Alignment | Login box centered on page | Login box centered on page | Pass |
| 12 | Field Alignment | Username and Password fields aligned vertically | Username and Password fields aligned vertically | Pass |
| 13 | Field Width | Both fields have same width | Both fields have same width | Pass |
| 14 | Spacing | Proper spacing between logo, fields, and button | Proper spacing between logo, fields, and button | Pass |
| 15 | Button Alignment | Login button centered below fields | Login button centered below fields | Pass |
| 16 | Error Message Position | Error message appears above the username field | Error message appears above the username field | Pass |
| 17 | Consistent Margins | Consistent margins around elements | Consistent margins around elements | Pass |

---

##  Typography Checklist

| # | Element | Expected | Actual | Status |
|:---|:---|:---|:---|:---|
| 18 | Logo Font | Bold, professional font | Bold, professional font | Pass |
| 19 | Field Labels | Consistent font family and size | Consistent font family and size | Pass |
| 20 | Button Text | White, readable, consistent font | White, readable, consistent font | Pass |
| 21 | Error Messages | Red, readable, consistent font | Red, readable, consistent font | Pass |
| 22 | Font Size | Appropriate font sizes for all elements | Appropriate font sizes for all elements | Pass |

---

##  Color & Styling Checklist

| # | Element | Expected | Actual | Status |
|:---|:---|:---|:---|:---|
| 23 | Login Button Color | Red/orange (#e2231a or similar) | Red/orange (#e2231a) | Pass |
| 24 | Button Text Color | White | White | Pass |
| 25 | Error Message Color | Red | Red | Pass |
| 26 | Field Background | White | White | Pass |
| 27 | Field Border | Gray border | Gray border | Pass |
| 28 | Page Background | White/gray | White/gray | Pass |

---

##  Interactive Elements Checklist

| # | Element | Expected | Actual | Status |
|:---|:---|:---|:---|:---|
| 29 | Username Field Focus | Cursor appears, focus indicator visible | Cursor appears, focus indicator visible | Pass |
| 30 | Password Field Focus | Cursor appears, focus indicator visible | Cursor appears, focus indicator visible | Pass |
| 31 | Login Button Click | Triggers login action | Triggers login action | Pass |
| 32 | Enter Key Support | Pressing Enter triggers login | Pressing Enter triggers login | Pass |
| 33 | Tab Navigation | Tab moves through fields in correct order | Tab moves through fields in correct order | Pass |

---

##  Functional Validation Checklist

| # | Test | Steps | Expected | Actual | Status |
|:---|:---|:---|:---|:---|:---|
| 34 | Valid Login | Enter valid credentials → Click Login | Redirect to Products page | Redirected to Products page | Pass |
| 35 | Invalid Login | Enter invalid credentials → Click Login | Error message displayed | Error message displayed | Pass |
| 36 | Empty Credentials | Leave fields empty → Click Login | "Username is required" message | "Username is required" message | Pass |
| 37 | Empty Password | Enter username only → Click Login | "Password is required" message | "Password is required" message | Pass |
| 38 | Locked User Login | Enter locked_out_user → Click Login | Error message about locked user | Error message about locked user | Pass |
| 39 | Password Masking | Type in password field | Characters hidden (dots) | Characters hidden (dots) | Pass |

---

##  Responsive Behavior Checklist

| # | Screen Size | Expected | Actual | Status |
|:---|:---|:---|:---|:---|
| 40 | Desktop (1920x1080) | Login box centered, proper size | Login box centered, proper size | Pass |
| 41 | Laptop (1366x768) | Login box centered, proper size | Login box centered, proper size | Pass |
| 42 | Tablet (1024x768) | Login box centered, scaled properly | Login box centered, scaled properly | Pass |
| 43 | Tablet Portrait (768x1024) | Login box centered, scaled properly | Login box centered, scaled properly | Pass |
| 44 | Mobile (375x667) | Login box centered, scaled properly | Login box centered, scaled properly | Pass |

---

##  Cross-Browser Checklist

| # | Browser | Expected | Actual | Status |
|:---|:---|:---|:---|:---|
| 45 | Chrome | All elements display correctly | All elements display correctly | Pass |
| 46 | Firefox | All elements display correctly | All elements display correctly | Pass |
| 47 | Brave | All elements display correctly | All elements display correctly | Pass |

---

##  Issues Found

| # | Issue | Severity | Priority | Status |
|:---|:---|:---|:---|:---|
| 1 | Error messages contain "Epic sadface:" prefix | Medium | High | Open |
| 2 | No "Show/Hide Password" toggle | Low | Medium | Open |

---

##  Summary

| Category | Total | Passed | Failed | Pass % |
|:---|:---|:---|:---|:---|
| Visual Elements | 10 | 10 | 0 | 100% |
| Layout & Alignment | 7 | 7 | 0 | 100% |
| Typography | 5 | 5 | 0 | 100% |
| Color & Styling | 6 | 6 | 0 | 100% |
| Interactive Elements | 5 | 5 | 0 | 100% |
| Functional Validation | 6 | 6 | 0 | 100% |
| Responsive Behavior | 5 | 5 | 0 | 100% |
| Cross-Browser | 3 | 3 | 0 | 100% |
| **Total** | **47** | **47** | **0** | **100%** |

---

## Final Status

| Aspect | Status |
|:---|:---|
| **Visual Appearance** | Passed |
| **Layout & Alignment** | Passed |
| **Functionality** | Passed |
| **Responsive Design** | Passed |
| **Cross-Browser** | Passed |
| **Overall Status** | **PASSED (with minor issues)** |

---

## Related Documents

| Document | Link |
|:---|:---|
| Test Plan | [./Test_Plan/Test_Plan.md](./Test_Plan/Test_Plan.md) |
| Test Scenarios | [./Test_Scenarios/Test_Scenarios.xlsx](./Test_Scenarios/Test_Scenarios.xlsx) |
| Test Cases | [./Test_Cases/SauceDemo_TestCases.xlsx](./Test_Cases/SauceDemo_TestCases.xlsx) |
| Bug Reports | [./Bug_Reports/Bug_Report.xlsx](./Bug_Reports/Bug_Report.xlsx) |

---

**End of Login Page UI Testing Checklist**

**Version:** 1.0  
**Last Updated:** July 17, 2026  
**Status:** Completed

---

**Thank you for reviewing this document!**
