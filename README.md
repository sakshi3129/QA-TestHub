# QA-TestHub - Web-Based QA Test Management Platform

QA-TestHub is a lightweight web-based QA Test Management Platform created to demonstrate a complete software testing workflow.

The project covers requirement management, test case management, test execution, defect tracking, RTM, API testing and AI-assisted QA activities.

---

## Project Objective

The main objective of QA-TestHub is to demonstrate how a QA tester can manage the testing lifecycle from requirements to test execution and defect tracking.

### QA Workflow

Requirement → Test Case → Execution → Bug → Retesting → RTM

---

## Technologies Used

- HTML
- CSS
- JavaScript
- Browser LocalStorage
- Postman
- Git
- GitHub
- GitHub Pages

---

## Project Modules

### 1. Dashboard

Provides an overview of:

- Total test cases
- Passed test cases
- Failed test cases
- Blocked test cases
- Testing activities

---

### 2. Requirements Management

The Requirements module allows testers to manage project requirements.

Features:

- Requirement ID
- Requirement title
- Description
- Priority
- Requirement list

Example requirements:

- REQ-001 - User Login
- REQ-002 - User Registration
- REQ-003 - Password Reset
- REQ-004 - User Logout

---

### 3. Test Case Management

The Test Case module is used to create and manage test cases.

Test cases include:

- Test Case ID
- Requirement
- Test Scenario
- Test Type
- Priority
- Expected Result
- Execution Status

Test types covered:

- Functional
- Negative
- Validation
- Smoke
- Boundary
- Regression

---

### 4. Test Execution

The Test Execution module allows testers to record test execution results.

Execution statuses:

- Pass
- Fail
- Blocked

The module also stores execution history using browser LocalStorage.

---

### 5. Bug Management

The Bug Management module is used to report and track software defects.

Bug information includes:

- Bug ID
- Bug Title
- Related Test Case
- Description
- Steps to Reproduce
- Expected Result
- Actual Result
- Severity
- Priority
- Status

Bug lifecycle:

Open → Fixed → Retest → Closed

---

### 6. Requirement Traceability Matrix

RTM maps project requirements with their corresponding test cases and execution status.

Example:

REQ-001 → TC-001 → Execution Status

The RTM helps verify requirement coverage throughout the testing process.

---

### 7. API Testing

API testing was performed using Postman.

API scenarios tested:

| API | Method | Expected Status | Result |
|-----|--------|-----------------|--------|
| /users/1 | GET | 200 | PASS |
| /users/9999 | GET | 404 | PASS |
| /posts | POST | 201 | PASS |

Postman test scripts were also used to validate API responses.

---

### 8. AI-Assisted QA

The project includes an AI-assisted QA module that generates structured prompts for:

- Test case generation
- Test scenario generation
- Negative test cases
- Boundary test cases
- Bug analysis

AI-generated results are manually reviewed before being used for testing.

The project does not contain a locally developed AI model. It demonstrates structured AI-assisted QA prompt generation.

---

## Testing Types Covered

- Functional Testing
- Negative Testing
- Validation Testing
- Smoke Testing
- Boundary Testing
- Regression Testing
- UI Testing
- API Testing
- Cross-Browser Testing

---

## Documentation

Project documentation includes:

- Test Plan
- Test Strategy
- Test Summary Report

Documentation is available inside the `docs` folder.

---

## Project Structure

```text
QA-TestHub/
│
├── index.html
├── dashboard.html
├── requirements.html
├── test-cases.html
├── test-execution.html
├── bugs.html
├── rtm.html
├── api-testing.html
├── ai-assistant.html
├── bug-analyzer.html
│
├── docs/
│   ├── Test-Plan.md
│   ├── Test-Strategy.md
│   └── Test-Summary.md
│
├── postman/
│   └── QA-TestHub-API-Collection.json
│
├── screenshots/
│
└── README.


## Key QA Skills Demonstrated
Test Case Design
Test Scenario Design
Functional Testing
Negative Testing
Validation Testing
Regression Testing
Smoke Testing
Boundary Testing
API Testing
Defect Reporting
Severity and Priority
Requirement Traceability
Test Execution
Retesting
AI-Assisted Testing
Postman
Git and GitHub

## How to Run the Project
Clone or download the repository.
Open the project folder.
Open index.html in a browser.

For local development, the project can also be opened using VS Code Live Server.


GitHub Repository:

https://github.com/sakshi3129/QA-TestHub

Live Project

GitHub Pages:

https://sakshi3129.github.io/QA-TestHub/

Conclusion

QA-TestHub demonstrates a structured QA testing workflow from requirement management to test execution, defect tracking, retesting and requirement traceability.

The project also demonstrates API testing using Postman, Git/GitHub usage and AI-assisted QA activities.