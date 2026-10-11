# ParaBank Manual QA Testing Project

## Project Overview
A manual software testing portfolio project for the ParaBank demo banking application. The project covers functional testing of core banking features, including positive and negative test scenarios.

## Objectives
- Validate core banking workflows.
- Execute and document manual test cases.
- Compare actual results with expected results.
- Record defects with supporting screenshots.
- Track defects in Jira.

## Application Scope
- User Registration
- Login and Login Recovery
- Account Overview and New Account Creation
- Funds Transfer
- Bill Payment
- Find Transactions
- Update Contact Information
- Loan Requests
- Logout and Session Access

## Tools Used
- ParaBank Demo Application
- Microsoft Excel
- Jira
- GitHub
- Google Chrome
- Snipping Tool

## Testing Deliverables
- Test Plan
- Test Scenarios
- Test Cases
- Test Execution Results
- Test Data
- Defect Reports
- Screenshot Evidence

## Defect Tracking
Defects were recorded in Jira under the project prefix `PQT` and documented in the `03-Defect-Reports` folder.

The documented issues include:
- Phone number validation accepts alphabetic and alphanumeric input.
- Previously valid login credentials are rejected after several hours.
- Zero-amount funds transfers are accepted.
- Zero-amount bill payments are accepted.
- Searching for a non-existing transaction ID displays an internal server error.

## Testing Approach
Test scenarios and test cases were maintained in an Excel workbook. Selected test cases were executed manually, results were recorded, and screenshots were captured as evidence. Observed issues were logged in Jira.

## Disclaimer
This project uses a public demo application for learning and portfolio purposes. Application behavior and test results may vary due to demo-environment instability. Observed behavior does not necessarily establish the underlying technical cause or a confirmed business-rule violation.

## Project Structure
- `01-Test-Plan/` — Test plan
- `02-Test-Cases/` — Test scenarios, test cases, execution results, and test data
- `03-Defect-Reports/` — Individual defect reports
- `04-Screenshots/` — Test evidence