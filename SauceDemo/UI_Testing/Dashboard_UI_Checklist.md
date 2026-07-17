# Dashboard/Products Page UI Testing Checklist - SauceDemo

**Module:** Dashboard / Products Page  
**Test Environment:** Chrome 114.0, Windows 11  
**Date:** July 17, 2026  
**Tester:** Rojina Adhikari  
**Status:** Completed

---

## Header Elements Checklist

| # | Element | Expected | Actual | Status |
|:---|:---|:---|:---|:---|
| 1 | Sauce Labs Logo | Logo displayed at top left | Logo displayed at top left | Pass |
| 2 | Page Title | "Products" title displayed | "Products" title displayed | Pass |
| 3 | Cart Icon | Shopping cart icon at top right | Shopping cart icon at top right | Pass |
| 4 | Cart Badge | Badge shows number of items in cart (0 initially) | Badge shows "0" initially | Pass |
| 5 | Cart Badge Update | Badge updates when items added/removed | Badge updates correctly | Pass |
| 6 | Hamburger Menu | Menu icon (☰) at top left | Menu icon (☰) at top left | Pass |
| 7 | Hamburger Menu Options | All Items, About, Logout, Reset App State | All options displayed | Pass |
| 8 | Filter Dropdown | Dropdown at top right | Dropdown at top right | Pass |

---

## Product Grid Checklist

| # | Element | Expected | Actual | Status |
|:---|:---|:---|:---|:---|
| 9 | Grid Layout | Products displayed in grid layout | Products displayed in grid layout | Pass |
| 10 | Desktop Columns | 2 columns on desktop | 2 columns on desktop | Pass |
| 11 | Tablet Columns | 1-2 columns on tablet | 1-2 columns on tablet | Pass |
| 12 | Mobile Columns | 1 column on mobile | 1 column on mobile | Pass |
| 13 | Product Count | Exactly 6 products displayed | 6 products displayed | Pass |
| 14 | Consistent Spacing | Uniform spacing between product cards | Uniform spacing between product cards | Pass |

---

## Product Card Checklist

| # | Element | Expected | Actual | Status |
|:---|:---|:---|:---|:---|
| 15 | Card Border | Each product has a card with border | Each product has a card with border | Pass |
| 16 | Card Padding | Consistent padding inside cards | Consistent padding inside cards | Pass |
| 17 | Card Shadow | Cards have shadow effect | Cards have shadow effect | Pass |
| 18 | Card Alignment | All cards aligned properly | All cards aligned properly | Pass |
| 19 | Product Image | Image displayed for each product | Image displayed for each product | Pass |
| 20 | Image Size | Images are consistent size | Images are consistent size | Pass |
| 21 | Product Title | Title displayed in blue, bold, clickable | Title displayed in blue, bold, clickable | Pass |
| 22 | Product Description | Description text displayed | Description text displayed | Pass |
| 23 | Product Price | Price displayed with "$" prefix, bold | Price displayed with "$" prefix, bold | Pass |
| 24 | Add to Cart Button | Green "Add to cart" button | Green "Add to cart" button | Pass |
| 25 | Remove Button | Red "Remove" button (after adding) | Red "Remove" button (after adding) | Pass |

---

## Filter/Sort Checklist

| # | Element | Expected | Actual | Status |
|:---|:---|:---|:---|:---|
| 26 | Dropdown Visibility | Filter dropdown visible | Filter dropdown visible | Pass |
| 27 | Option 1 | Name (A to Z) | Name (A to Z) | Pass |
| 28 | Option 2 | Name (Z to A) | Name (Z to A) | Pass |
| 29 | Option 3 | Price (low to high) | Price (low to high) | Pass |
| 30 | Option 4 | Price (high to low) | Price (high to low) | Pass |
| 31 | Sort A to Z | Products sorted alphabetically | Products sorted alphabetically | Pass |
| 32 | Sort Z to A | Products sorted reverse alphabetically | Products sorted reverse alphabetically | Pass |
| 33 | Sort Low to High | Products sorted by price ascending | Products sorted by price ascending | Pass |
| 34 | Sort High to Low | Products sorted by price descending | Products sorted by price descending | Pass |

---

## Button Behavior Checklist

| # | Element | Expected | Actual | Status |
|:---|:---|:---|:---|:---|
| 35 | Add to Cart Click | Button changes to "Remove" | Button changes to "Remove" | Pass |
| 36 | Add to Cart Color | Green button | Green button | Pass |
| 37 | Remove Click | Button changes to "Add to cart" | Button changes to "Add to cart" | Pass |
| 38 | Remove Color | Red button | Red button | Pass |
| 39 | Cart Badge Count | Number increases when item added | Number increases when item added | Pass |
| 40 | Cart Badge Decrease | Number decreases when item removed | Number decreases when item removed | Pass |
| 41 | Multiple Items | Badge shows correct count for multiple items | Badge shows correct count | Pass |

---

## Navigation Checklist

| # | Element | Expected | Actual | Status |
|:---|:---|:---|:---|:---|
| 42 | Cart Icon Click | Navigates to Cart page | Navigates to Cart page | Pass |
| 43 | Product Title Click | Navigates to Product detail page | Navigates to Product detail page | Pass |
| 44 | Hamburger Menu Click | Side menu slides in | Side menu slides in | Pass |
| 45 | All Items Link | Navigates to Products page | Navigates to Products page | Pass |
| 46 | About Link | Navigates to About page | Navigates to About page | Pass |
| 47 | Logout Link | Logs out, navigates to Login page | Logs out, navigates to Login page | Pass |
| 48 | Reset App State | Resets cart and state | Resets cart and state | Pass |

---

## Visual Consistency Checklist

| # | Element | Expected | Actual | Status |
|:---|:---|:---|:---|:---|
| 49 | Color Scheme | Consistent colors throughout | Consistent colors throughout | Pass |
| 50 | Font Family | Consistent font family | Consistent font family | Pass |
| 51 | Font Sizes | Consistent heading and text sizes | Consistent heading and text sizes | Pass |
| 52 | Button Styling | All buttons have consistent styling | All buttons have consistent styling | Pass |
| 53 | Image Quality | All images clear and properly sized | All images clear and properly sized | Pass |

---

## Special User Testing Checklist

| # | User | Element | Expected | Actual | Status |
|:---|:---|:---|:---|:---|:---|
| 54 | problem_user | Product Images | All images displayed correctly | Images broken/placeholder | Fail (Issue) |
| 55 | problem_user | Page Load | Page loads successfully | Page loads successfully | Pass |
| 56 | error_user | Product Display | All products displayed | All products displayed | Pass |
| 57 | error_user | Add to Cart Buttons | All buttons visible | Missing button for Sauce Labs Backpack | Fail (Issue) |
| 58 | visual_user | UI Layout | Consistent layout | Distorted layout | Fail (Issue) |
| 59 | visual_user | Button Styling | Consistent styling | Different colors and margins | Fail (Issue) |
| 60 | performance_glitch_user | Page Load | Fast load time | 5-8 second delay | Fail (Issue) |

---

## Responsive Design Checklist

| # | Screen Size | Expected | Actual | Status |
|:---|:---|:---|:---|:---|
| 61 | Desktop (1920x1080) | 2 columns, full size | 2 columns, full size | Pass |
| 62 | Laptop (1366x768) | 2 columns, scaled | 2 columns, scaled | Pass |
| 63 | Tablet Landscape (1024x768) | 2 columns, responsive | 2 columns, responsive | Pass |
| 64 | Tablet Portrait (768x1024) | 1-2 columns, responsive | 1-2 columns, responsive | Pass |
| 65 | Mobile Portrait (375x667) | 1 column, stacked | 1 column, stacked | Pass |
| 66 | Mobile Landscape (667x375) | 1-2 columns, responsive | 1-2 columns, responsive | Pass |
| 67 | Text Readability | Text readable on all sizes | Text readable on all sizes | Pass |
| 68 | Button Resizing | Buttons resize appropriately | Buttons resize appropriately | Pass |
| 69 | Image Scaling | Images scale properly | Images scale properly | Pass |

---

## Cross-Browser Checklist

| # | Browser | Expected | Actual | Status |
|:---|:---|:---|:---|:---|
| 70 | Chrome | All elements display correctly | All elements display correctly | Pass |
| 71 | Firefox | All elements display correctly | All elements display correctly | Pass |
| 72 | Brave | All elements display correctly | All elements display correctly | Pass |

---

## Issues Found

| # | Issue | Severity | Priority | Status |
|:---|:---|:---|:---|:---|
| 1 | Broken product images for problem_user | Medium | Medium | Open |
| 2 | Missing Add to Cart button for error_user | High | High | Open |
| 3 | Distorted UI for visual_user | Low | Low | Open |
| 4 | Performance delay for performance_glitch_user | Low | Medium | Open |

---

## Summary

| Category | Total | Passed | Failed | Pass % |
|:---|:---|:---|:---|:---|
| Header Elements | 8 | 8 | 0 | 100% |
| Product Grid | 6 | 6 | 0 | 100% |
| Product Card | 11 | 11 | 0 | 100% |
| Filter/Sort | 9 | 9 | 0 | 100% |
| Button Behavior | 7 | 7 | 0 | 100% |
| Navigation | 7 | 7 | 0 | 100% |
| Visual Consistency | 5 | 5 | 0 | 100% |
| Special User Testing | 7 | 3 | 4 | 43% |
| Responsive Design | 9 | 9 | 0 | 100% |
| Cross-Browser | 3 | 3 | 0 | 100% |
| **Total** | **72** | **68** | **4** | **94.44%** |

---

## Final Status

| Aspect | Status |
|:---|:---|
| **Visual Appearance** | Passed |
| **Layout & Grid** | Passed |
| **Functionality** | Passed |
| **Navigation** | Passed |
| **Special Users** | Failed (4 issues) |
| **Responsive Design** | Passed |
| **Cross-Browser** | Passed |
| **Overall Status** | PASSED (with issues) |

---

## Recommendations

### High Priority (Must Fix)

| # | Recommendation |
|:---|:---|
| 1 | Fix missing Add to Cart button for error_user |

### Medium Priority (Should Fix)

| # | Recommendation |
|:---|:---|
| 2 | Fix broken images for problem_user |
| 3 | Optimize performance for performance_glitch_user |

### Low Priority (Nice to Have)

| # | Recommendation |
|:---|:---|
| 4 | Fix UI distortion for visual_user |

---

## Related Documents

| Document | Link |
|:---|:---|
| Test Plan | [./Test_Plan/Test_Plan.md](./Test_Plan/Test_Plan.md) |
| Test Scenarios | [./Test_Scenarios/Test_Scenarios.xlsx](./Test_Scenarios/Test_Scenarios.xlsx) |
| Test Cases | [./Test_Cases/SauceDemo_TestCases.xlsx](./Test_Cases/SauceDemo_TestCases.xlsx) |
| Bug Reports | [./Bug_Reports/Bug_Report.xlsx](./Bug_Reports/Bug_Report.xlsx) |

---

**End of Dashboard/Products Page UI Testing Checklist**

**Version:** 1.0  
**Last Updated:** July 17, 2026  
**Status:** Completed

---

**Thank you for reviewing this document!**
