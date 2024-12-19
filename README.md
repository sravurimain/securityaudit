# Botium Toys Security Audit

## Overview
This project demonstrates a practical application of cybersecurity auditing principles by conducting an internal IT security audit for a fictional company, **Botium Toys**. The activity was completed as part of the Google Cybersecurity Certificate program on Coursera. This audit follows the **National Institute of Standards and Technology Cybersecurity Framework (NIST CSF)** to identify vulnerabilities, assess compliance, and recommend improvements to enhance the organization's security posture.

---

## Scenario
**Botium Toys** is a small U.S.-based toy company with growing online operations and a single physical location. Due to its expansion and increasing IT demands, an internal security audit was requested to:
- Assess existing IT infrastructure and assets.
- Identify risks, threats, or vulnerabilities.
- Evaluate compliance with relevant security frameworks and regulations, including PCI DSS and GDPR.

The goal of this audit was to mitigate risks, ensure compliance, and secure critical assets.

---

## Audit Scope and Goals

### Scope:
The audit encompasses:
- Employee devices (e.g., desktops, laptops, smartphones).
- On-premises office equipment.
- Internal networks and systems.
- Data storage and retention.
- Legacy systems.
- E-commerce operations and online payment processing systems.

### Goals:
1. Review assets managed by the IT department.
2. Complete a **Controls and Compliance Checklist**.
3. Identify areas for improvement and make recommendations to enhance security and compliance.

---

## Methodology
### Framework: 
The audit was performed using the **NIST Cybersecurity Framework (CSF)**.

### Key Tasks:
1. Reviewed the risk assessment provided by the IT manager.
2. Completed the **Controls and Compliance Checklist**.
3. Evaluated compliance with:
   - **Payment Card Industry Data Security Standards (PCI DSS)**
   - **General Data Protection Regulation (GDPR)**
   - **System and Organization Controls (SOC Type 1 & 2)**

### Tools:
- Controls and Compliance Checklist (provided by course materials).
- Supporting materials from the course.

---

## Results
### Controls Assessment Checklist:
| Control                     | Status  |
|-----------------------------|---------|
| Least Privilege             | No      |
| Disaster Recovery Plans     | No      |
| Password Policies           | No      |
| Separation of Duties        | No      |
| Firewall                    | Yes     |
| Intrusion Detection System  | No      |
| Backups                     | No      |
| Antivirus Software          | Yes     |
| Manual Monitoring Legacy Systems | No |
| Encryption                  | No      |
| Password Management System  | No      |
| Physical Locks              | Yes     |
| CCTV Surveillance           | Yes     |
| Fire Detection Systems      | Yes     |

### Compliance Checklist:
| Compliance Requirement                        | Status |
|-----------------------------------------------|--------|
| PCI DSS: Secure Credit Card Transactions      | No     |
| GDPR: Data Privacy for EU Customers           | Partial|
| SOC: Sensitive Data Confidentiality           | Partial|

### Risk Assessment:
- **Risk Score:** 8/10 (High)
- **Key Findings:**
  - Lack of encryption for sensitive data.
  - No disaster recovery plan.
  - Weak password policies.
  - Inadequate access controls (e.g., least privilege and separation of duties).

---

## Recommendations
To address these vulnerabilities, it is recommended that Botium Toys:
1. Implement encryption for all sensitive data, especially credit card information.
2. Develop and test a disaster recovery and business continuity plan.
3. Enforce stronger password policies and adopt centralized password management systems.
4. Establish access controls based on the principle of least privilege and separation of duties.
5. Deploy an Intrusion Detection System (IDS) to monitor and respond to security breaches.
6. Regularly back up critical data and store backups securely.

---

## Supporting Materials
- [Scope, Goals, and Risk Assessment Report](https://docs.google.com/document/d/1s2u_RuhRAI40JSh-eZHvaFsV1ZMxcNSWXifHDTOsgFc/template/preview#heading=h.evidx83t54sc)
