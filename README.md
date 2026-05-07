# Software Quality Assurance: RBAC Manual Testing Suite

## 📌 Project Overview
This repository contains a comprehensive manual testing suite designed to validate the Role-Based Access Control (RBAC) architecture of OrangeHRM, an enterprise-level open-source HR management system. 

The objective of this project is to define and maintain quality standards by systematically testing the security boundaries between Global Administrators and standard Employee Self Service (ESS) users. 

## 🎯 Testing Scope & Methodologies
Leveraging a strong foundation in system architecture and deployment life cycles, this testing suite applies rigorous quality inspection workflows. Testing methodologies applied include:
* **Boundary Value & Equivalence Partitioning:** Validating input constraints.
* **Negative & Security Testing:** Attempting horizontal and vertical privilege escalation via direct URL manipulation.
* **End-to-End Workflow Validation:** Ensuring cross-functional features (like leave approval loops) operate flawlessly.

## 📂 Key Deliverables

### 1. Role Requirements Matrix
A foundational document defining the access rules and logic boundaries for different user tiers.
* [📄 View Requirements Matrix (PDF) ->](<OrangeHRM's - Role Requirements Matrix.pdf>)

### 2. Test Execution Log
A Jira-style execution log containing 11 structured test cases, detailing pre-conditions, steps to reproduce, and expected vs. actual results.
* [📄 View Test Execution Log (PDF) ->](<OrangeHRM's RBAC - Test Execution Log.pdf>) 

### 3. Formal Defect Report
A professional, industry-standard bug report documenting a simulated critical security vulnerability (Broken Access Control). 
* [📄 View Defect Report: BUG-001 (PDF) ->](<Defect Bug Report  - Muhammad Kaif.pdf>) 

## 🛠️ Tools & Environment
* **Application Under Test:** OrangeHRM (Live Demo Environment)
* **Testing Type:** Manual Functional, Security, and UI Testing
* **Test Documentation:** Spreadsheet/Jira-style defect tracking formats
* **Environment:** Windows 10, Google Chrome v120
