# OWASP Juice Shop Manual Testing Project

## Project Overview
This project demonstrates end-to-end manual testing performed on the OWASP Juice Shop application using TestRail. The objective of this project was to validate the application's functionality, identify defects, execute test cases, and document the overall testing process.

## Application Details
- Application Name: OWASP Juice Shop
- Application URL: https://preview.owasp-juice.shop/
- Testing Type: Manual Testing
- Test Management Tool: TestRail
- Browser Used: Google Chrome
- Operating System: Windows 11

## Testing Scope
The following testing activities were performed:

### Smoke Testing
Verified the critical functionalities of the application before detailed testing.

### Functional Testing
Tested individual modules including:
- Login
- Registration
- Search
- Cart
- Checkout
- Forgot Password
- Logout
- User Profile
- Order History
- Navigation Menu
- Contact Us
- About Us

### Integration Testing
Verified the interaction between modules such as:
- Registration → Login
- Search → Basket
- Checkout → Order History
- Forgot Password → Login

### System Testing
Validated complete end-to-end user journeys across the application.

## Test Execution Summary

| Testing Type | Passed | Failed |
|--------------|---------|---------|
| Smoke Testing | 18 | 2 |
| Functional Testing | 110 | 5 |
| Integration Testing | 29 | 1 |
| System Testing | 6 | 1 |
| **Total** | **163** | **9** |

## Defect Summary
- Total Bugs Identified: 9
- Critical: 1
- High: 4
- Medium: 2
- Low: 2

## Repository Structure

```
OWASP-Juice-Shop-Manual-Testing
│
├── Test_Cases
├── Test_Execution_Reports
├── Bug_Reports
├── Test_Summary_Report
└── Screenshots
```

## Project Artifacts
This repository contains:
- Test Case Documents
- Test Execution Reports
- Bug Report
- Test Summary Report
- TestRail Execution Screenshots

## Key Learning Outcomes
Through this project, I gained hands-on experience in:
- Writing test scenarios and test cases
- Executing manual test cases
- Logging and tracking defects
- Preparing bug reports and test summary reports
- Using TestRail for test management
- Managing testing artifacts using GitHub

## Author
**Aruna B.**

Manual Testing Enthusiast
