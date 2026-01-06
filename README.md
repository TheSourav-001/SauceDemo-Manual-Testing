# SauceDemoTestCases

# Project Overview
This repository contains a comprehensive, end-to-end manual testing suite for the SauceDemo (Swag Labs) E-Commerce Application.
The project demonstrates real-world QA test case design, analytical thinking, and structured documentation following industry best practices.

The repository is intentionally test-case centric, focusing on depth of testing, functional coverage, negative and edge-case validation,
rather than automation code.

# Application Under Test (AUT)
- Application Name: SauceDemo (Swag Labs)
- Application Type: Web-based E-Commerce Application
- URL: https://www.saucedemo.com

# Testing Scope
The test coverage includes the following functional and non-functional areas:

- Login & Authentication
- Session Management
- Inventory (Product Listing)
- Product Details Page
- Cart Functionality
- Checkout & Order Flow
- End-to-End User Journeys
- System & Edge Case Scenarios
- Basic Security & Backend Validation (manual)

# Repository Structure

```
TestCase-saucedemo/
│
├── Test Case/
│   ├── Authentication & Session Management.xlsx
│   ├── Inventory Page (Product Listing).xlsx
│   ├── Product Detail.xlsx
│   ├── Cart Functionality.xlsx
│   ├── Checkout.xlsx
│   ├── End-to-End & System Edge Cases.xlsx
│   └── TestCase_All_in_One.xlsx
│
├── Test Plan/
│   └── Test_Plan_SauceDemo_E-Commerce_Application.pdf
│
├── Test Scenarios/
│   └── Test_Scenarios_SauceDemo_E-Commerce_Application.pdf
│
├── Test Execution Report/
│   └── Test Execution Report.pdf
│
├── Bug List/
│   └── Bug_List_SauceDemo.xlsx
│
├── Screenshots/
│   ├── Test_Execution_Screenshots/
│   └── Bug_Screenshots/
│
└── README.md
```


# Test Artifacts Included

# Test Plan
Defines the overall testing strategy, scope, objectives, test types, test environment,
entry and exit criteria, risks, and assumptions.

# Test Scenarios
High-level scenarios derived from application requirements to ensure complete functional
coverage before detailed test case creation.

# Test Cases
Detailed, step-by-step manual test cases written in Excel format covering:
- Functional scenarios
- Negative scenarios
- Edge and boundary cases
- End-to-end user flows

# Test Execution Report
Provides execution metrics including:
- Total test cases executed
- Passed and failed test cases
- Pass percentage
- Defect summary
- Overall testing conclusion

# Bug List
Contains all identified defects with:
- Bug ID
- Severity
- Priority
- Status
- Affected module
- Description and reproduction steps

# Screenshots
Includes visual evidence for:
- Test execution results
- Reported defects

# Test Case Design Format
All test cases follow a JIRA-style manual testing format with the following columns:

- Test Case ID
- Prerequisites
- Test Case Title / Description
- Test Steps
- Expected Result
- Actual Result
- Pass / Fail Status
- Comments

This format aligns with industry-standard QA documentation practices.

# Testing Approach
- Manual Functional Testing
- Negative Testing
- Boundary Value & Edge Case Testing
- End-to-End Flow Validation
- Session & Access Control Testing
- Basic Security Testing (manual OWASP-style checks)
- Backend inspection using browser DevTools

# Tools & Skills Demonstrated
- Manual Software Testing
- Test Case Design & Documentation
- Test Scenario Analysis
- Defect Reporting
- JIRA-style QA Documentation
- E-Commerce Domain Testing
- Quality Assurance Best Practices

# Purpose of This Repository
- QA portfolio demonstration
- Practice of real-world manual testing workflows
- Interview and technical assessment reference
- Showcasing structured QA thinking and documentation skills

# Notes
- This repository intentionally excludes automation scripts.
- The focus is on depth, coverage, accuracy, and quality of manual test cases.
- Test cases are written assuming the application is treated as a production-level system.

# Author
Sourav Dipto Apu
