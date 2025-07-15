# 🔐 SailPoint Identity Lifecycle Project

This simulated project demonstrates the core Identity Lifecycle Management capabilities of **SailPoint IdentityNow**, a leading Identity Governance and Administration (IGA) platform. The simulation walks through onboarding, access provisioning, access reviews, and offboarding processes — highlighting how SailPoint automates identity security across connected systems.

---

## 🚀 What This Project Covers

- ✅ User onboarding simulation (via mock HR data file)
- ✅ Automated provisioning into connected apps (e.g., AD, Okta, Workday)
- ✅ Role-based access modeling
- ✅ Access request and approval workflow
- ✅ Policy enforcement and SOD violation detection
- ✅ Access review and certification campaigns
- ✅ Offboarding and deprovisioning of user access

---

## 🧪 IAM Lab Summary

This project was completed using SailPoint IdentityNow’s sandbox environment and includes screenshots of hands-on configurations such as:

- IdentityNow Dashboard
- Identity Profile view (Identity Cube)
- Access Certification campaigns
- Role and Policy configurations
- Access Requests and Approvals
- Offboarding process and deprovisioning outcomes

---

## 🧾 Mock HR Source Data

This simulation uses a CSV file to represent data from an HR system such as Workday. When new employees are added to this file, SailPoint detects them during aggregation and automatically provisions accounts and access based on assigned roles and policies.

### Example CSV (mock_hr_data.csv)

| First Name | Last Name | Email                  | Department | Title              | Start Date  |
|------------|-----------|------------------------|------------|--------------------|-------------|
| John       | Smith     | john.smith@example.com | Finance    | Financial Analyst  | 2025-07-01  |
| Jane       | Doe       | jane.doe@example.com   | IT         | Systems Engineer   | 2025-07-02  |
| Sarah      | Lee       | sarah.lee@example.com  | HR         | Recruiter          | 2025-07-03  |

This file simulates how SailPoint imports identity records from an authoritative source. Each entry triggers lifecycle events like onboarding, access provisioning, and future offboarding.

---

# 📸 Project Screenshot Overview

The following screenshot provides a high-level view of the identity lifecycle implemented in SailPoint IdentityNow. It covers onboarding, access provisioning, certification, and offboarding.

👉 [Click here to view the full screenshot](IAM%20SailPoint%20Screenshot.png)

---

## 📂 Project Structure

The repository is organized as follows:

```bash
📁 sailpoint-lifecycle-simulation/
├── README.md                          # Project overview and documentation
├── mock_hr_data.csv                   # Sample input file to simulate HR source data
├── provisioning_steps.md              # Step-by-step notes on automated provisioning
├── access_reviews.md                  # Certification notes and screenshots
├── screenshots/
│   └── IAM SailPoint Screenshot.png   # Combined lifecycle screenshot from SailPoint
