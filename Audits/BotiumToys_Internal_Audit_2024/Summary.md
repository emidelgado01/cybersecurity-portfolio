# Internal Security Audit – Botium Toys (2024)

## Context

This project was completed as part of the Google Cybersecurity Professional Certificate.  
The scenario is based on a fictional U.S. company, **Botium Toys**, which is experiencing rapid online growth and is concerned about compliance, security risks, and business continuity.

## Objective

Conduct an internal IT audit by reviewing the company’s scope, goals, and risk assessment, then complete a security controls and compliance checklist to assess the company’s current security posture.

## Methodology

- Reviewed the IT manager’s documentation regarding assets, scope, and goals.
- Applied the NIST Cybersecurity Framework as a baseline.
- Completed a controls and compliance checklist, marking which controls and compliance best practices are currently in place.
- Provided actionable recommendations to address gaps.

## Key Findings

- The company has implemented some essential controls (e.g., fire detection, locks, firewall, backups), but has critical gaps in areas such as **Least Privilege**, **password policies**, **disaster recovery**, and **encryption**.
- There are multiple compliance requirements (PCI DSS, GDPR, SOC) that are only partially met, especially regarding **data classification**, **user access policies**, and **incident response**.

You can review the completed checklist [here](./Botium_Toys_Checklist_Completed.pdf).

## Recommendations

Key recommendations include:

- Implement Least Privilege access controls and proper separation of duties.
- Develop and maintain a disaster recovery plan.
- Enforce strong password policies and deploy a password management system.
- Adopt an Intrusion Detection System (IDS) and ongoing monitoring for legacy systems.
- Ensure data encryption for sensitive and payment information.
- Properly classify assets and maintain up-to-date privacy and compliance documentation.
- Conduct regular security awareness training for staff.

Full recommendations and details can be found [here](./recommendations.md).

---

> **Reflection:**  
> This exercise provided hands-on first experience in applying audit frameworks, identifying compliance gaps, and articulating recommendations to improve an organization’s security infrastructure.
