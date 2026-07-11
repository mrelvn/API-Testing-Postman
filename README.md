# API Testing – Restful Booker API

A comprehensive Manual API Testing project for the **Restful Booker API**, demonstrating an end-to-end Software Testing Life Cycle (STLC) using industry-standard QA documentation and Postman.

---

## Project Overview

This repository showcases a complete API Testing project built around the Restful Booker REST API. The project covers the entire testing lifecycle—from requirement analysis and test planning to execution, defect reporting, traceability, and test closure.

All project artifacts are synchronized to ensure complete consistency between requirements, test scenarios, test cases, execution results, and defect tracking.

---

## Project Objective

- Validate the functional behavior of all in-scope REST API endpoints.
- Verify request and response correctness.
- Perform positive and negative API testing.
- Validate authentication and authorization.
- Ensure complete requirement traceability.
- Document defects using industry-standard bug reporting practices.
- Demonstrate a structured STLC workflow suitable for enterprise QA projects.

---

## Application Under Test

| Item | Details |
|------|---------|
| Project | Restful Booker API |
| Base URL | https://restful-booker.herokuapp.com |
| Testing Type | Manual API Testing |
| API Style | REST |
| Authentication | Token-Based Authentication |

---

## Scope

### In Scope

- Authentication (`/auth`)
- Booking Management (`/booking`)
- Booking Details (`/booking/{id}`)
- Booking Update (PUT)
- Partial Update (PATCH)
- Delete Booking
- Health Check (`/ping`)
- End-to-End API Workflow

### Out of Scope

- GUI Testing
- Performance Testing (except basic latency validation)
- Database Validation
- Security/Penetration Testing

---

## Testing Types Performed

- API Testing
- Functional Testing
- Manual Testing
- Positive Testing
- Negative Testing
- Smoke Testing
- Integration Testing
- Regression Testing
- Boundary Value Validation
- Response Validation
- Status Code Validation

---

## Tools & Technologies

- Postman
- REST API
- JSON
- Microsoft Excel
- Microsoft Word
- Git
- GitHub

---

# Repository Structure

```text
API_Testing_RestfulBooker
│
├── README.md
│
├── Requirements
│   └── Functional Requirements Specification.docx
│
├── Test Plan
│   └── Test Plan.docx
│
├── Test Design
│   ├── API_Test_Scenarios.xlsx
│   └── API_Test_Cases.xlsx
│
├── Traceability Matrix
│   └── RTM.xlsx
│
├── Test Execution
│   └── Test Execution Report.docx
│
├── Bug Report
│   └── Bug_Tracking_Report.xlsx
│
├── Test Closure
│   └── Test Closure Report.docx
│
└── Postman Collections
    ├── RestfulBooker_Collection.json
    └── RestfulBooker_Environment.json
```

---

# Project Documentation

## Functional Requirements Specification (FRS)

Defines all functional and non-functional requirements for the Restful Booker API, including authentication, booking management, health checks, business rules, constraints, assumptions, and requirement mappings.

---

## Test Plan

Describes the testing strategy, objectives, scope, test approach, entry and exit criteria, environment setup, risk analysis, defect management process, and approval workflow.

---

## Test Scenarios

Contains high-level test scenarios mapped directly to the functional requirements to ensure complete business coverage.

---

## Test Cases

Includes detailed executable test cases with preconditions, test steps, expected results, execution status, and requirement mapping.

---

## Requirements Traceability Matrix (RTM)

Maintains end-to-end traceability between Functional Requirements, Test Scenarios, Test Cases, Execution Status, and Defects, ensuring complete requirement coverage.

---

## Bug Tracking Report

Documents all identified defects with severity, priority, reproduction steps, expected results, actual results, status, and associated test cases.

---

## Test Execution Report

Summarizes the execution cycle, including test execution statistics, pass/fail analysis, defect metrics, exit criteria evaluation, and overall execution status.

---

## Test Closure Report

Provides the final testing summary, quality assessment, defect status, risk evaluation, exit criteria review, and formal project closure.

---

## Postman Collections

Contains the Postman Collection and Environment files used for API execution and validation.

---

# Testing Workflow

```text
Functional Requirements Specification
                │
                ▼
           Test Plan
                │
                ▼
         Test Scenarios
                │
                ▼
          Test Cases
                │
                ▼
      API Execution (Postman)
                │
                ▼
         Bug Identification
                │
                ▼
      Requirements Traceability
                │
                ▼
     Test Execution Report
                │
                ▼
      Test Closure Report
```

---

# Project Highlights

- Enterprise-style QA documentation
- End-to-end STLC implementation
- Complete requirement traceability
- Structured API validation
- Defect lifecycle management
- Professional documentation standards
- Organized repository structure
- Industry-standard QA deliverables

---

# Skills Demonstrated

- Manual Testing
- API Testing
- REST API Validation
- Requirement Analysis
- Test Planning
- Test Scenario Design
- Test Case Design
- Test Execution
- Defect Reporting
- Requirement Traceability
- QA Documentation
- Postman
- SDLC
- STLC
- Git & GitHub

---

# Deliverables

- Functional Requirements Specification (FRS)
- Test Plan
- Test Scenarios
- Test Cases
- Requirements Traceability Matrix (RTM)
- Bug Tracking Report
- Test Execution Report
- Test Closure Report
- Postman Collection
- Postman Environment

---

# Project Outcome

The project successfully demonstrates a structured API testing process aligned with industry-standard QA practices. It provides complete documentation covering requirement analysis, planning, test design, execution, defect management, traceability, and test closure, making it suitable as a professional QA portfolio project.

---

# Author

**Farzan Ahmad**

This repository has been developed as a portfolio project to demonstrate practical knowledge of Manual API Testing, QA documentation, and Software Testing Life Cycle (STLC) using the Restful Booker REST API.