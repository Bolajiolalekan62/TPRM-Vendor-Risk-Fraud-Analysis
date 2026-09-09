# TPRM: Vendor Risk Analysis & Fraud Intelligence System

### Applied to the Fintech & Digital Payments Industry

## Overview
Organizations across industries rely on third party vendors for technology, infrastructure, professional services, financial services, logistics, compliance, and other critical business functions. Each relationship can introduce operational, cybersecurity, financial, compliance, and reputational risk.

I built this project to demonstrate how data analytics can support a structured, data driven approach to Third Party Risk Management (TPRM).

Using 1,000 simulated vendor records, I combined MySQL, SQL risk analysis, fraud indicator screening, data quality validation, and Power BI to assess vendor exposure, identify potential risk indicators, and highlight areas requiring further investigation.

The project uses a fintech and digital payments environment as the case study context, while the underlying analytical approach can be applied across industries where organizations manage third party relationships, operational risk, compliance requirements, and financial exposure.

> **Note:** This is a self-directed portfolio project using simulated data. Fraud related results are indicators for further investigation, not confirmed fraud cases.

---

## Key Findings

* **48.1%** of vendors were classified as **High or Critical risk**
* **47** duplicate audit records identified
* **544** vendors flagged by the defined high contract value screening rule
* **9** round number financial anomalies identified
* **1** bulk onboarding event detected
* **0** vendors met the defined ghost vendor screening condition

### Risk Distribution

**Low 26% | Medium 25% | High 22% | Critical 23%**

---

## Risk Model

| Risk Dimension   |  Weight |
| ---------------- | ------: |
| Cybersecurity    | **50%** |
| Financial Health | **30%** |
| Compliance       | **20%** |

Vendors were classified into **Low, Medium, High, and Critical** risk tiers based on the project's weighted assessment model.

---

## What I Built

### SQL Analysis

* Database and relational tables
* Data cleaning and validation
* Vendor risk scoring
* Risk tier analysis
* Fraud indicator screening
* Stored procedures for recurring reporting

### Power BI Dashboard

* Executive risk overview
* Vendor risk distribution
* Industry/category risk analysis
* Fraud indicator tracking
* KPI monitoring
* Findings and recommendations

---

## Key Fraud Indicator Scenarios

The analysis screened for:

* High contract values
* Missing country information
* Bulk vendor onboarding
* Low risk vendors with high incident counts
* Round number contract patterns
* Financial anomaly indicators

These indicators are intended to **prioritize further investigation**, not establish fraud.

---

## Business Value

The analysis demonstrates how organizations could use data to:

* Prioritize high risk vendors
* Strengthen vendor due diligence
* Identify data quality weaknesses
* Flag unusual patterns for investigation
* Improve risk reporting and decision-making

---

## Tools & Skills

**MySQL | SQL | Power BI | Excel | Data Cleaning | Risk Scoring | Fraud Analytics | TPRM | Risk & Compliance Analysis**

---

## Project Files

```text
01_Database_Setup.sql
02_Data_Cleaning.sql
03_Risk_Analysis_Reports.sql
04_Fraud_Intelligence.sql
05_Stored_Procedures.sql

TPRM_Dashboard.pbix
TPRM_Dashboard.pdf
TPRM_Fintech_Report_Final.docx
TPRM_Technical_Appendices.docx
```

---

## Regulatory & Risk Framework Context

The analysis references relevant Nigerian and international regulatory and risk management frameworks, including:

**CBN | FATF/GIABA | NDPA 2023 | PCI DSS | FCA Operational Resilience | GDPR | ISO 31000**

These frameworks provide context for the types of cybersecurity, compliance, data protection, financial crime, operational, and third-party risks considered in the project.

---

## Limitations

This project uses simulated data. Risk scores and fraud indicators are designed for analytical demonstration and would require additional validation, external intelligence, and organization-specific risk criteria before production use.

