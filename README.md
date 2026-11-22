# NIST CSF 2.0 Enterprise Cybersecurity Risk Assessment

## Project Overview

This project is a simulated enterprise cybersecurity risk assessment for a fictional organization, **Pine Ridge Logistics, Inc.**, developed to demonstrate practical skills in:

- Cybersecurity risk assessment
- NIST Cybersecurity Framework (CSF) 2.0
- Risk register development
- Risk treatment planning
- Executive risk reporting
- Cybersecurity governance, risk, and compliance (GRC)

The project models how a junior cybersecurity risk analyst or GRC analyst might identify enterprise assets, assess cybersecurity risks, map findings to NIST CSF 2.0, and recommend remediation priorities.

> **Important:** This is a fictional simulation created for portfolio and educational purposes. No real production environment was assessed, and no live systems were accessed or tested.

---

## Objectives

- Identify critical business assets and technology dependencies
- Develop a cybersecurity risk assessment methodology
- Document risk scenarios affecting enterprise systems
- Evaluate inherent and residual risk
- Assign risk owners and treatment priorities
- Map risks to NIST CSF 2.0 categories
- Build a preliminary current-state and target-state framework profile
- Produce an executive-facing cybersecurity risk summary

---

## Organization Scenario

**Pine Ridge Logistics, Inc.** is a fictional regional logistics and distribution company with:

- 250 employees
- 3 warehouse locations
- Microsoft 365 and Microsoft Azure usage
- Windows-based systems and business applications
- Third-party vendors
- Fleet telematics and warehouse operations

---

## Frameworks and Guidance Used

- **NIST Cybersecurity Framework (CSF) 2.0**
- **NIST SP 800-30 Rev. 1** – Guide for Conducting Risk Assessments

---

## Tools Used

- **PowerShell** – project automation and documentation generation
- **CSV files** – asset inventory, risk register, treatment plan, and framework mappings
- **Markdown** – GitHub documentation
- **HTML** – visual cybersecurity risk heatmap
- **Text reports** – executive summary and project documentation

---

## Project Deliverables

### 1. Project Scope
- `01_Project_Scope/Project_Charter.txt`

### 2. Enterprise Asset Inventory
- `02_Asset_Inventory/Enterprise_Asset_Inventory.csv`

### 3. Risk Assessment Methodology and Scenario Inventory
- `03_Risk_Assessment/Risk_Assessment_Methodology.txt`
- `03_Risk_Assessment/Risk_Scenario_Inventory.csv`

### 4. NIST CSF 2.0 Profiles and Gap Analysis
- `04_NIST_CSF_Profiles/NIST_CSF_2.0_Category_Baseline.csv`
- `04_NIST_CSF_Profiles/Risk_to_NIST_CSF_Category_Mapping.csv`
- `04_NIST_CSF_Profiles/NIST_CSF_2.0_Preliminary_Gap_Analysis.csv`

### 5. Enterprise Risk Register
- `05_Risk_Register/Enterprise_Risk_Register.csv`

### 6. Risk Treatment Plan
- `06_Risk_Treatment/Risk_Treatment_Plan.csv`

### 7. Executive Reporting
- `07_Executive_Report/Executive_Risk_Summary.txt`
- `07_Executive_Report/Enterprise_Risk_Heatmap.html`

---

## Risk Assessment Summary

### Assets Documented
- 20 enterprise assets

### Risk Scenarios Assessed
- 10 cybersecurity risk scenarios

### Residual Risk Distribution
- 1 Critical
- 8 High
- 1 Moderate

### Highest-Priority Residual Risk
**RSK-008 – Backup data is deleted or encrypted during a ransomware incident**

This remained the highest-priority residual risk because backup protection was assumed, but immutable or offline recovery protections were not established.

---

## NIST CSF 2.0 Coverage Summary

### Framework Structure Used
- 6 Functions
- 22 Categories

### Preliminary Current-State Assessment
- 8 categories with assumed practices (unverified)
- 4 categories with insufficient evidence
- 10 categories requiring broader assessment coverage

### Target Profile
Proposed target outcomes were defined for all 22 NIST CSF 2.0 categories.

---

## Key Skills Demonstrated

- Enterprise asset identification
- Cybersecurity risk scenario development
- Likelihood and impact scoring
- Inherent vs. residual risk analysis
- Risk ownership and treatment prioritization
- NIST CSF 2.0 category mapping
- Preliminary gap analysis
- Executive risk communication
- PowerShell-based project automation

---

## Key Takeaways

This project demonstrates a structured approach to enterprise cybersecurity risk analysis using NIST CSF 2.0. It shows how cybersecurity risks can be identified, prioritized, linked to governance and operational controls, and communicated to business leadership.

It also demonstrates the importance of documenting assessment assumptions and limitations instead of overstating control effectiveness or compliance conclusions.

---

## How to Discuss This Project in an Interview

Example talking points:

- I developed a simulated enterprise cybersecurity risk assessment using NIST CSF 2.0.
- I created an asset inventory, risk methodology, risk register, and treatment plan.
- I assessed both inherent and residual risk for 10 enterprise cybersecurity scenarios.
- I mapped risks to NIST CSF 2.0 categories and developed a preliminary current-state and target-state profile.
- I created an executive summary and visual risk heatmap to communicate cybersecurity priorities to leadership.
- I used PowerShell to automate the creation of multiple project deliverables.

---

## Author

**Mohamed Thomas**
CompTIA Security+
M.S. Cybersecurity Technology Candidate
GitHub Portfolio Project

## Hands-On Nessus Vulnerability Assessment

This project includes a technical vulnerability assessment
performed using Tenable Nessus Essentials against an
isolated Metasploitable 2 training VM.

### Technical Assessment Highlights

- Network vulnerability scanning using Nessus Essentials
- TCP service discovery and vulnerability analysis
- Five documented findings: four Critical and one High
- CVE research and remediation recommendations
- Scanner evidence supporting each documented finding
- Mapping of selected findings to NIST CSF 2.0

The assessment includes weaknesses involving VNC
authentication, an exposed bind shell, legacy SSL
protocols, an unsupported operating system, and Samba.

These findings are from an intentionally vulnerable
training VM, not Pine Ridge Logistics. No remediation
or post-remediation validation is claimed.

### Explore the Technical Assessment

[View the Nessus Vulnerability Assessment](10_Lab_Vulnerability_Assessment/README.md)
