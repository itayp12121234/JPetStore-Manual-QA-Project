# JPetStore Manual QA Testing Project

## Overview

This repository presents a complete Manual QA testing project performed on the JPetStore web application as part of my Software Quality Assurance studies.

The project covers the full manual testing process, including test planning, test design, test execution, defect reporting, retesting, regression testing, and final test reporting.

## Project Documents

- [Software Test Plan (STP)](docs/STP איתי פלג חנות חיות.docx)
- [Software Test Results (STR)](docs/JPetStore-STR.pdf)
- [Manual Test Cases](Test-Cases/JPetStore-Test-Cases.xlsx)
- [Defect Report](Defects/Defect-Report.md)

## Screenshots

- [QA Dashboard](Screenshots/QA-Dashboard.png)
- [Test Plan](Screenshots/Test-Plan.png)
- [Test Executions](Screenshots/Test-Executions.png)

## Tools

- Jira
- Xray
- Google Chrome

## Testing Techniques

The following black-box testing techniques were used during the project:

- Equivalence Partitioning
- Boundary Value Analysis
- Decision Tables
- State Transition Testing
- Error Guessing

## Test Process

The testing process included:

- Designing and executing 20 manual test cases
- Managing tests using Jira and Xray
- Performing two testing rounds
- Reporting and tracking software defects
- Retesting failed test cases after fixes
- Performing regression testing
- Creating an STP document
- Creating an STR document
- Building a QA dashboard for test and defect tracking

## Areas Tested

The tested functionality included:

- User registration
- Login functionality
- User session behavior
- Product and category navigation
- Purchase flow
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

### Second Test Round

#### Retesting

| Result | Test Cases |
|---|---:|
| Passed | 1 |
| Failed | 3 |
| Total | 4 |

#### Regression Testing

| Result | Test Cases |
|---|---:|
| Passed | 16 |
| Failed | 0 |
| Total | 16 |

## Final Test Status

| Result | Test Cases |
|---|---:|
| Passed | 17 |
| Failed | 3 |
| Total | 20 |

**Final pass rate: 85%**

## Defect Summary

A total of three defects were reported during testing.

| Defect | Severity | Final Status |
|---|---|---|
| IP-65 | High | Closed |
| IP-66 | Low | Open |
| IP-67 | Medium | Open |

### Final Defect Status

- 3 defects reported
- 1 defect closed
- 2 defects remained open

The high-severity defect discovered during the first testing round was successfully fixed and verified.

## Regression Results

All 16 regression tests passed successfully after the defect fixes.

No regression defects were discovered during the second testing round.

## Project Outcome

Most of the tested functionality operated as expected.

At the end of the testing process:

- 17 of 20 test cases passed
- 3 test cases remained failed
- The high-severity defect was fixed
- One medium-severity defect remained open
- One low-severity defect remained open
- All regression tests passed

The remaining issues were related to user session behavior and navigation within the product categories.

## Skills Demonstrated

- Manual Testing
- Test Design
- Test Execution
- Defect Reporting
- Regression Testing
- Retesting
- Jira
- Xray
- Software Test Documentation
