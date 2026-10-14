# JPetStore Defect Report

## Summary

During the first test execution round, three defects were identified and reported in Jira.

| Defect | Severity | Priority | Final Status |
|--------|----------|----------|--------------|
| IP-65  |   High   | Highest  |    Closed    |
| IP-66  |   Low    | Medium   |    Open      |
| IP-67  |  Medium  | Medium   |    Open      |

---

## IP-65 – Purchase Allowed After Incomplete Registration

**Severity:** High  
**Priority:** Highest  
**Status:** Closed

### Description
A user who did not complete all required registration details was still able to continue to the purchase process.

### Expected Result
The user should not be able to proceed with the purchase until all required registration information is completed correctly.

### Actual Result
The user was able to proceed to the order process despite incomplete registration details.

### Retest Result
The defect was fixed and the related test passed during retesting.

---

## IP-66 – Automatic Login Does Not Occur

**Severity:** Low  
**Priority:** Medium  
**Status:** Open

### Description
A previously registered user is not automatically recognized when returning to the application without signing out.

### Expected Result
The application should recognize the returning user and automatically restore the logged-in session.

### Actual Result
The user is required to sign in again.

### Retest Result
The defect remained reproducible during the second test round.

---

## IP-67 – Product Subcategory Cannot Be Opened by Name

**Severity:** Medium  
**Priority:** Medium  
**Status:** Open

### Description
The name of the product subcategory is not clickable, preventing the user from navigating to the subcategory through its name.

### Test Data
Amazon Parrot

### Expected Result
Clicking the subcategory name should open the selected product subcategory.

### Actual Result
The subcategory name is not clickable, and the user remains on the category page.

### Retest Result
The defect remained reproducible during the second test round.

---

## Final Defect Status

- Total defects reported: 3
- Closed: 1
- Open: 2
- High-severity defects remaining: 0
