# HisabDo – Day 12 Capstone QA Testing

## Software Quality Assurance Internship

**Tester:** Esha Tur Razia  
**Project:** HisabDo  
**Day:** 12  
**Testing Focus:** Validation, Negative Testing & Defect Verification  

---

## 📌 Project Overview

This repository contains the QA testing work completed for **Day 12 of the HisabDo SQA Capstone Project**.

The primary focus of Day 12 was to perform validation and negative testing across the HisabDo Mobile Application and Website, identify reproducible defects, assign severity and priority, and prepare defect verification/retesting documentation.

---

## 🎯 Objectives

The main objectives of this testing phase were:

- Verify required-field validation.
- Test invalid and incorrect input formats.
- Verify duplicate data handling.
- Perform boundary value testing.
- Test empty states.
- Verify error messages and error handling.
- Test Delete and Cancel operations.
- Verify internal and external navigation.
- Identify and document reproducible defects.
- Assign Severity and Priority to defects.
- Perform defect verification/retesting.
- Maintain a professional defect summary.

---

## 🔍 Testing Scope

### Mobile Application

The following modules were tested:

- Customer Management
- Transactions
- Registration
- Login
- Forgot Password
- Navigation
- Delete Operations
- Cancel Operations

### Website

The following modules were tested:

- Registration
- Contact
- Footer
- Privacy Policy
- Founder
- Careers
- Navigation
- External Links
- Form Validation

---

## 🧪 Testing Types

The following testing techniques were applied:

- Required Field Validation
- Negative Testing
- Invalid Input Testing
- Data Format Validation
- Duplicate Data Testing
- Boundary Value Testing
- Empty State Testing
- Error Handling
- Delete Operation Testing
- Cancel Operation Testing
- Navigation Testing
- External Link Testing
- Defect Verification / Retesting

---

## 📊 Test Execution Summary

Based on the current executed test cases:

| Metric | Mobile App | Website | Total |
|---|---:|---:|---:|
| Total Test Cases | 20 | 14 | 34 |
| Passed | 8 | 1 | 9 |
| Failed | 12 | 12 | 24 |
| Blocked | 0 | 0 | 0 |
| Not Run | 0 | 1 | 1 |
| Pass Percentage | 40% | 7.14% | 26.47% |
| Fail Percentage | 60% | 85.71% | 70.59% |

> **Note:** The Day 12 requirement is 20 Mobile App and 15 Website test cases. The current Website execution contains 14 test cases, so one additional Website test case should be executed to complete the required 35 test cases.

---

## 🐞 Defect Summary

A total of **24 reproducible defects** were identified from the executed test cases.

| Severity | Count |
|---|---:|
| Critical | 0 |
| High | 4 |
| Medium | 18 |
| Low | 2 |
| **Total** | **24** |

### Defect Status

| Status | Count |
|---|---:|
| Open | 24 |
| Closed | 0 |
| Reopened | 0 |

All currently reported defects remain open because no fixed/retested defects have been recorded yet.

---

## 🚨 Major Defects Identified

Some of the major issues identified during testing include:

### Mobile Application

1. Phone number required validation is missing.
2. Customer Name accepts numeric input.
3. Customer Name accepts special characters.
4. Invalid email format is accepted.
5. Duplicate customers can be created without warning.
6. Zero amount is not properly handled.
7. Negative transaction amounts are accepted.
8. Required customer/category validation is missing.
9. Weak password such as `123456` is accepted.
10. Duplicate accounts can be created.
11. Invalid email is accepted during registration.
12. Forgot Password flow results in a localhost connection error.

### Website

1. Invalid email format is accepted.
2. Name field accepts numeric input.
3. Name field accepts special characters.
4. Phone field accepts alphabetic characters.
5. Invalid city values are accepted.
6. Unsupported file types are accepted.
7. Contact email button is not clickable.
8. Footer support email action does not work.
9. Privacy Policy Contact/Support link is not working.
10. Founder GitHub link returns a 404 error.
11. Careers Open Roles section has no proper empty-state message.
12. Careers page contains contradictory hiring information.

---

## 🔁 Defect Verification / Retesting

Each identified defect has been mapped to its original test case for verification.

The verification process includes:

- Original Test Case ID
- Bug ID
- Defect Description
- Expected Result
- Actual Result
- Verification Status

### Verification Status Definitions

| Status | Meaning |
|---|---|
| Pass – Fixed | Defect has been fixed and verified successfully |
| Fail – Reproducible | Defect still occurs during verification |
| Open | Defect has not yet been fixed |
| Closed | Defect has been fixed and successfully retested |
| Reopened | Previously fixed defect has appeared again |

Currently, the identified defects are marked as **Fail – Reproducible / Open** based on the available execution results.

---

## 📋 Bug Reporting

Every reproducible defect is documented with:

- Bug ID
- Module
- Bug Title
- Severity
- Priority
- Description
- Reproduction Steps
- Expected Result
- Actual Result
- Evidence
- Defect Status

Screenshots and other evidence should be attached to the corresponding bug reports.

---

## 📁 Repository Structure

```text
HisabDo-Day-12-SQA/
│
├── README.md
│
├── Test-Cases/
│   ├── Mobile-App-Test-Cases.xlsx
│   └── Website-Test-Cases.xlsx
│
├── Bug-Reports/
│   └── Bug-Report-Register.xlsx
│
├── Defect-Verification/
│   └── Defect-Verification-Retest.xlsx
│
├── Reports/
│   └── Defect-Summary-Report.xlsx
│
└── Evidence/
    ├── BUG-001/
    ├── BUG-002/
    ├── BUG-003/
    └── ...
