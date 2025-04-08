# 🛡️ Bug Report - Security Rounding System

This repository contains a structured QA bug report for the **Security Rounding System** used in the One Finance ecosystem. The goal of this testing effort is to ensure the application's reliability, security, and ease of use by identifying critical and minor bugs across various features of the system.

---

## 📋 Project Overview

The **Security Rounding System** is designed to track and manage security personnel rounds across designated checkpoints. It ensures that rounds are logged properly, deviations are flagged, and real-time monitoring is enabled. This report includes functional, UI, and logical bugs discovered during testing.

---

## ✅ Test Summary

| Category              | Count   |
|-----------------------|---------|
| Total Test Cases      | 30      |
| Test Cases Passed     | 23      |
| Test Cases Failed     | 7      |
| Total Bugs Reported   | 7      |
| Critical Bugs         | 4      |
| Minor Bugs            | 3      |
| Test Coverage         | ~100%    |

---

## 📁 File Structure

- `Bug report of Security Rounding System.xlsx`  
  Contains:
  - Bug ID
  - Bug Summary
  - Module Name
  - Steps to Reproduce
  - Expected vs Actual Results
  - Severity (Critical / Minor)
  - Status (Open / Fixed)
  - Screenshots (if applicable)
  - Reported Date

---

## 🔍 Sample Bug Entry

| Field              | Example Value                                           |
|-------------------|---------------------------------------------------------|
| **Bug ID**         | BUG-SR-004                                              |
| **Module**         | Checkpoint Monitoring                                   |
| **Summary**        | user info missing in round to check the routes of security guard per round   |
| **Severity**       | Critical                                                |
| **Steps to Reproduce** | 1. Start a security round <br>2. Reach a checkpoint <br>3. Disconnect internet mid-check-in |
| **Expected Result** | Round data is cached and synced once connection is back|
| **Actual Result**   | Round is lost with no error or retry option            |
| **Status**         | Open                                                    |

---

## 🔧 Modules Tested

- Checkpoint Management
- Guard Round Tracking
- Alert Notifications
- Round Summary Reports
- Admin Settings Panel
- Location & Time Validation

---

## 🎯 Purpose

This report was created to:
- Capture and document all known issues in the Security Rounding System
- Provide reproducible steps and expected outcomes for each issue
- Aid developers in resolving bugs more efficiently
- Improve operational safety and system accuracy

---

## 🙋‍♂️ Author

**Name**: Md. Sadman Shahrieal Pieal  
**Role**: QA Engineer  
**Email**: sadmanpieal@gmail.com  
**Date**: March 2025

---

## 🧭 Future Enhancements

- Add offline sync validation to ensure round data isn’t lost
- Perform stress testing with multiple simultaneous check-ins
- Link bugs to issue tracker (e.g., GitHub Issues or JIRA)
- Integrate test automation for round validations and logs

---

## 📌 Disclaimer

This bug report is confidential and intended solely for the One Finance QA and development teams. All information within is for testing and improvement purposes only.

