# Test Scenarios - SauceDemo Manual Testing

**Version:** 1.0  
**Date:** July 17, 2026  
**Author:** Rojina Adhikari  
**Status:** Completed

---

##  Test Scenarios Summary

| Scenario ID | Module | Scenario Name | Description | Priority | Test Cases Count | Status |
|:---|:---|:---|:---|:---|:---|:---|
| TS-001 | Login | Verify Login Functionality | Test all login scenarios including valid, invalid, empty credentials | High | 6 | Completed |
| TS-002 | Login | Verify Locked User Handling | Test locked_out_user login behavior | High | 1 | Completed |
| TS-003 | Login | Verify Special User Accounts | Test problem_user, error_user, visual_user, performance_glitch_user | Medium | 4 | Completed |
| TS-004 | Login | Verify UI Elements | Test login page UI elements and layout | Medium | 10 | Completed |
| TS-005 | Products | Verify Product Display | Test product grid, images, titles, descriptions, prices | High | 6 | Completed |
| TS-006 | Products | Verify Add to Cart | Test add to cart functionality and button behavior | High | 4 | Completed |
| TS-007 | Products | Verify Remove from Cart | Test remove from cart functionality | High | 3 | Completed |
| TS-008 | Products | Verify Filter/Sort | Test product sorting options | Medium | 4 | Completed |
| TS-009 | Products | Verify Navigation | Test hamburger menu, cart navigation | Medium | 3 | Completed |
| TS-010 | Products | Verify UI Elements | Test products page UI elements and layout | Medium | 8 | Completed |
| TS-011 | Cart | Verify Cart Display | Test cart page item display and details | High | 3 | Completed |
| TS-012 | Cart | Verify Cart Actions | Test remove from cart, continue shopping | High | 3 | Completed |
| TS-013 | Checkout | Verify Checkout Information | Test checkout form and validation | High | 4 | Completed |
| TS-014 | Checkout | Verify Checkout Overview | Test order overview and total calculation | High | 3 | Completed |
| TS-015 | Checkout | Verify Order Completion | Test order completion and confirmation | High | 2 | Completed |
| TS-016 | UI/Responsive | Verify Responsive Design | Test application on different screen sizes | Medium | 6 | Completed |
| TS-017 | UI/Cross-Browser | Verify Cross-Browser Compatibility | Test application on different browsers | Medium | 4 | Completed |

---

## Statistics

### Module-wise Summary

| Module | Scenarios | High Priority | Medium Priority | Low Priority | Status |
|:---|:---|:---|:---|:---|:---|
| Login | 4 | 2 | 2 | 0 | Completed |
| Products | 6 | 3 | 3 | 0 | Completed |
| Cart | 2 | 2 | 0 | 0 | Completed |
| Checkout | 3 | 3 | 0 | 0 | Completed |
| UI/Responsive | 2 | 0 | 2 | 0 | Completed |
| **Total** | **17** | **10** | **7** | **0** | **Completed** |

---

### Priority Distribution

| Priority | Count | Percentage |
|:---|:---|:---|
| High | 10 | 59% |
| Medium | 7 | 41% |
| Low | 0 | 0% |
| **Total** | **17** | **100%** |

---

### Status Distribution

| Status | Count | Percentage |
|:---|:---|:---|
| Completed | 17 | 100% |
| In Progress | 0 | 0% |
| Pending | 0 | 0% |
| **Total** | **17** | **100%** |

---

##  Detailed Test Scenarios

### TS-001: Verify Login Functionality

| Field | Details |
|:---|:---|
| **Scenario ID** | TS-001 |
| **Module** | Login |
| **Scenario Name** | Verify Login Functionality |
| **Description** | Test all login scenarios including valid credentials, invalid credentials, and empty credentials |
| **Priority** | High |
| **Preconditions** | User is on SauceDemo login page |
| **Test Data** | standard_user, invalid_user, empty fields |
| **Expected Result** | Valid credentials redirect to Products page; Invalid/empty credentials show error messages |
| **Test Cases** | TC_LOGIN_001, TC_LOGIN_002, TC_LOGIN_003, TC_LOGIN_005, TC_LOGIN_006 |
| **Status** | Completed |

---

### TS-002: Verify Locked User Handling

| Field | Details |
|:---|:---|
| **Scenario ID** | TS-002 |
| **Module** | Login |
| **Scenario Name** | Verify Locked User Handling |
| **Description** | Test locked_out_user login behavior and error message |
| **Priority** | High |
| **Preconditions** | User is on SauceDemo login page |
| **Test Data** | locked_out_user / secret_sauce |
| **Expected Result** | Error message displayed: "Sorry, this user has been locked out" |
| **Test Cases** | TC_LOGIN_004 |
| **Status** | Completed |

---

### TS-003: Verify Special User Accounts

| Field | Details |
|:---|:---|
| **Scenario ID** | TS-003 |
| **Module** | Login |
| **Scenario Name** | Verify Special User Accounts |
| **Description** | Test problem_user, error_user, visual_user, performance_glitch_user |
| **Priority** | Medium |
| **Preconditions** | User is on SauceDemo login page |
| **Test Data** | problem_user, error_user, visual_user, performance_glitch_user / secret_sauce |
| **Expected Result** | All users login successfully; UI/Performance issues documented |
| **Test Cases** | TC_LOGIN_007, TC_LOGIN_008, TC_LOGIN_009, TC_LOGIN_010 |
| **Status** | Completed |

---

### TS-004: Verify Login Page UI Elements

| Field | Details |
|:---|:---|
| **Scenario ID** | TS-004 |
| **Module** | Login |
| **Scenario Name** | Verify Login Page UI Elements |
| **Description** | Test login page UI elements including logo, fields, button, error messages |
| **Priority** | Medium |
| **Preconditions** | User is on SauceDemo login page |
| **Test Data** | N/A |
| **Expected Result** | All UI elements displayed correctly, consistent styling |
| **Test Cases** | MUI-LOGIN-001 to MUI-LOGIN-014 |
| **Status** | Completed |

---

### TS-005: Verify Product Display

| Field | Details |
|:---|:---|
| **Scenario ID** | TS-005 |
| **Module** | Products |
| **Scenario Name** | Verify Product Display |
| **Description** | Test product grid, images, titles, descriptions, prices |
| **Priority** | High |
| **Preconditions** | User is logged in with standard_user |
| **Test Data** | standard_user |
| **Expected Result** | 6 products displayed correctly with images, titles, descriptions, prices |
| **Test Cases** | MUI-PROD-001 to MUI-PROD-012 |
| **Status** | Completed |

---

### TS-006: Verify Add to Cart

| Field | Details |
|:---|:---|
| **Scenario ID** | TS-006 |
| **Module** | Products |
| **Scenario Name** | Verify Add to Cart |
| **Description** | Test add to cart functionality and button behavior |
| **Priority** | High |
| **Preconditions** | User is logged in with standard_user |
| **Test Data** | standard_user |
| **Expected Result** | Button changes to "Remove", cart badge updates |
| **Test Cases** | MUI-PROD-013, MUI-PROD-014, MUI-PROD-016, MUI-PROD-029 |
| **Status** | Completed |

---

### TS-007: Verify Remove from Cart

| Field | Details |
|:---|:---|
| **Scenario ID** | TS-007 |
| **Module** | Products |
| **Scenario Name** | Verify Remove from Cart |
| **Description** | Test remove from cart functionality |
| **Priority** | High |
| **Preconditions** | User has items in cart |
| **Test Data** | standard_user |
| **Expected Result** | Button changes to "Add to cart", cart badge decrements |
| **Test Cases** | MUI-PROD-015, MUI-PROD-030 |
| **Status** | Completed |

---

### TS-008: Verify Filter/Sort

| Field | Details |
|:---|:---|
| **Scenario ID** | TS-008 |
| **Module** | Products |
| **Scenario Name** | Verify Filter/Sort |
| **Description** | Test product sorting options (A-Z, Z-A, Price low-high, Price high-low) |
| **Priority** | Medium |
| **Preconditions** | User is logged in with standard_user |
| **Test Data** | standard_user |
| **Expected Result** | Products sorted correctly based on selected option |
| **Test Cases** | MUI-PROD-017, MUI-PROD-018, MUI-PROD-019, MUI-PROD-020, MUI-PROD-021 |
| **Status** | Completed |

---

### TS-009: Verify Navigation

| Field | Details |
|:---|:---|
| **Scenario ID** | TS-009 |
| **Module** | Products |
| **Scenario Name** | Verify Navigation |
| **Description** | Test hamburger menu, cart navigation |
| **Priority** | Medium |
| **Preconditions** | User is logged in with standard_user |
| **Test Data** | standard_user |
| **Expected Result** | Navigation works correctly |
| **Test Cases** | MUI-PROD-023, MUI-PROD-024 |
| **Status** | Completed |

---

### TS-010: Verify Products Page UI Elements

| Field | Details |
|:---|:---|
| **Scenario ID** | TS-010 |
| **Module** | Products |
| **Scenario Name** | Verify Products Page UI Elements |
| **Description** | Test products page UI elements including header, grid, cards, buttons |
| **Priority** | Medium |
| **Preconditions** | User is logged in with standard_user |
| **Test Data** | standard_user |
| **Expected Result** | All UI elements displayed correctly |
| **Test Cases** | MUI-PROD-001 to MUI-PROD-012 |
| **Status** | Completed |

---

### TS-011: Verify Cart Display

| Field | Details |
|:---|:---|
| **Scenario ID** | TS-011 |
| **Module** | Cart |
| **Scenario Name** | Verify Cart Display |
| **Description** | Test cart page item display and details |
| **Priority** | High |
| **Preconditions** | User has items in cart |
| **Test Data** | standard_user |
| **Expected Result** | Cart displays all items with correct details |
| **Test Cases** | MUI-CART-001, MUI-CART-002, MUI-CART-003 |
| **Status** | Completed |

---

### TS-012: Verify Cart Actions

| Field | Details |
|:---|:---|
| **Scenario ID** | TS-012 |
| **Module** | Cart |
| **Scenario Name** | Verify Cart Actions |
| **Description** | Test remove from cart, continue shopping |
| **Priority** | High |
| **Preconditions** | User is on Cart page with items |
| **Test Data** | standard_user |
| **Expected Result** | Remove works, Continue Shopping navigates back |
| **Test Cases** | MUI-CART-004, MUI-CART-005 |
| **Status** | Completed |

---

### TS-013: Verify Checkout Information

| Field | Details |
|:---|:---|
| **Scenario ID** | TS-013 |
| **Module** | Checkout |
| **Scenario Name** | Verify Checkout Information |
| **Description** | Test checkout form and validation |
| **Priority** | High |
| **Preconditions** | User has items in cart |
| **Test Data** | John Doe, 12345 |
| **Expected Result** | Form validates, navigates to Overview |
| **Test Cases** | MUI-CHK-001, MUI-CHK-002, MUI-CHK-003, MUI-CHK-004 |
| **Status** | Completed |

---

### TS-014: Verify Checkout Overview

| Field | Details |
|:---|:---|
| **Scenario ID** | TS-014 |
| **Module** | Checkout |
| **Scenario Name** | Verify Checkout Overview |
| **Description** | Test order overview and total calculation |
| **Priority** | High |
| **Preconditions** | User is on Checkout Overview page |
| **Test Data** | standard_user |
| **Expected Result** | Total calculation is correct |
| **Test Cases** | MUI-CHK-005, MUI-CHK-006, MUI-CHK-007 |
| **Status** | Completed |

---

### TS-015: Verify Order Completion

| Field | Details |
|:---|:---|
| **Scenario ID** | TS-015 |
| **Module** | Checkout |
| **Scenario Name** | Verify Order Completion |
| **Description** | Test order completion and confirmation |
| **Priority** | High |
| **Preconditions** | User is on Checkout Overview page |
| **Test Data** | standard_user |
| **Expected Result** | Order completes, confirmation shown |
| **Test Cases** | MUI-CHK-008, MUI-CHK-009 |
| **Status** | Completed |

---

### TS-016: Verify Responsive Design

| Field | Details |
|:---|:---|
| **Scenario ID** | TS-016 |
| **Module** | UI/Responsive |
| **Scenario Name** | Verify Responsive Design |
| **Description** | Test application on different screen sizes |
| **Priority** | Medium |
| **Preconditions** | User is logged in |
| **Test Data** | Desktop, Tablet, Mobile |
| **Expected Result** | Application adapts to all screen sizes |
| **Test Cases** | MUI-RESP-001 to MUI-RESP-010 |
| **Status** | Completed |

---

### TS-017: Verify Cross-Browser Compatibility

| Field | Details |
|:---|:---|
| **Scenario ID** | TS-017 |
| **Module** | UI/Cross-Browser |
| **Scenario Name** | Verify Cross-Browser Compatibility |
| **Description** | Test application on different browsers |
| **Priority** | Medium |
| **Preconditions** | User is logged in |
| **Test Data** | Chrome, Firefox, Brave |
| **Expected Result** | Application works on all browsers |
| **Test Cases** | MUI-CROSS-001 to MUI-CROSS-004 |
| **Status** | Completed |

---

##  Related Documents

| Document | Link |
|:---|:---|
| Test Plan | [./Test_Plan/Test_Plan.md](./Test_Plan/Test_Plan.md) |
| Test Cases | [./Test_Cases/SauceDemo_TestCases.xlsx](./Test_Cases/SauceDemo_TestCases.xlsx) |
| Bug Reports | [./Bug_Reports/Bug_Report.xlsx](./Bug_Reports/Bug_Report.xlsx) |
| Execution Report | [./Test_Execution_Report/Execution_Report.xlsx](./Test_Execution_Report/Execution_Report.xlsx) |

---

**End of Test Scenarios Document**

**Version:** 1.0  
**Last Updated:** July 17, 2026  
**Status:** Completed

---

**Thank you for reviewing this document!**
