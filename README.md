# JPetStore Manual QA Testing Project

## Overview

This repository presents a complete Manual QA testing project performed on the JPetStore web application.

The project covers the full manual testing process, including test planning, test design, test execution, defect reporting, retesting, regression testing, and final test reporting.

## Project Documents

- [Software Test Plan (STP)](01_STP_JPetStore.pdf)
- [Manual Test Cases](02_Test_Cases_JPetStore.pdf)
- [Defect Report](03_Defect_Report_JPetStore.md)
- [Software Test Results (STR)](04_STR_JPetStore.pdf)

## Screenshots

- [QA Dashboard](Screenshots/QA-Dashboard.png)
- [Test Plan](Screenshots/Test-Plan.png)
- [Test Executions](Screenshots/Test-Executions.png)

## Tools

- Jira
- Xray
- Google Chrome
- GitHub

## Testing Techniques

The following black-box testing techniques were used during the project:

- Equivalence Partitioning
- Boundary Value Analysis
- Decision Tables
- State Transition Testing
- Pairwise Testing

## Test Process

The testing process included:

- Designing and executing 20 manual test cases
- Managing test cases and executions using Jira and Xray
- Performing two testing rounds
- Reporting and tracking software defects
- Retesting failed test cases after fixes
- Performing regression testing
- Creating STP and STR documentation
- Building a QA dashboard for test and defect tracking

## Areas Tested

The tested functionality included:

- User registration
- Login functionality
- User session behavior
- Product and category navigation
- Search functionality
- Shopping cart and purchase flow
- Required field validation
- System behavior after defect fixes

## Test Results

### First Test Round

| Result | Test Cases |
|---|---:|
| Passed | 16 |
| Failed | 4 |
| Total | 20 |

Three defects were reported during the first testing round.

### Retesting

| Result | Test Cases |
|---|---:|
| Passed | 1 |
| Failed | 3 |
| Total | 4 |

### Regression Testing

| Result | Test Cases |
|---|---:|
| Passed | 16 |
| Failed | 0 |
| Total | 16 |

All 16 regression tests passed successfully, and no regression defects were identified.

## Final Test Status

| Result | Test Cases |
|---|---:|
| Passed | 17 |
| Failed | 3 |
| Total | 20 |

**Final pass rate: 85%**

## Defect Summary

A total of three defects were reported during testing.

| Defect | Severity | Priority | Final Status |
|---|---|---|---|
| IP-65 | High | Highest | Closed |
| IP-66 | Low | Medium | Open |
| IP-67 | Medium | Medium | Open |

The high-severity defect was fixed and successfully verified during retesting.

At the end of the project:

- 3 defects were reported
- 1 defect was closed
- 2 defects remained open
- No High-severity defects remained open

## Project Outcome

Most of the tested functionality operated as expected.

The remaining issues were related to user session behavior and navigation within product categories. The high-severity purchase-flow defect was resolved successfully, while all regression tests passed after the fix.

## Skills Demonstrated

- Manual Web Testing
- Test Planning
- Test Design
- Test Execution
- Defect Reporting
- Retesting
- Regression Testing
- Jira
- Xray
- Software Test Documentation
