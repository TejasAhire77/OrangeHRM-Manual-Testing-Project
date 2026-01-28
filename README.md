# OrangeHRM Manual Testing Project

## 📌 Project Overview

This repository showcases the manual functional testing performed on the **OrangeHRM (v5.7)** application. The project focuses on ensuring the stability of core HR management modules, specifically focusing on user authentication and administrative data management.

## 🛠 Modules Covered

* **Login Module:** Validation of authentication flows, including valid/invalid credentials, mandatory field checks, and session security.
* **Admin Module:** Testing the "General Information" section, focusing on data integrity, organization profile updates, and field-level validations (Zipcode, Country selection, etc.).

## 📂 Project Artifacts

* **Test Scenarios:** High-level scenarios mapping out the testing scope for Login and Admin features.
* **Test Cases:** 22 detailed test cases including preconditions, execution steps, expected results, and actual results.
* **Defect Report:** Log of identified bugs with detailed steps to reproduce, priority, and severity levels.

## 🔍 Key Testing Highlights

* **Functional Testing:** Verified that all buttons, links, and data fields operate according to requirements.
* **Negative Testing:** Validated system behavior when entering incorrect data formats (e.g., invalid zip codes or empty mandatory fields).
* **Defect Discovery:** Identified critical issues in the Admin module where the system saved information despite invalid organization names or missing country selections.


**Author:** Tejas Pravin Ahire

**Role:** QA Engineer / Software Tester
