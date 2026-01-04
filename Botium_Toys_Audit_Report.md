# Security Audit Report: Botium Toys
**Status:** Completed | **Framework:** NIST CSF

## 1. Scope & Goals
- **Scope:** Entire security program at Botium Toys, including employee equipment, internal network, and systems.
- **Goal:** Assess existing assets and complete a controls and compliance checklist to improve the company's security posture.

## 2. Risk Assessment
- **Risk Description:** Currently, there is inadequate management of assets and lack of proper controls to be fully compliant with U.S. and international regulations.
- **Risk Score:** 8/10 (High).
- **Key Vulnerabilities Identified:**
    - Lack of least privilege and separation of duties.
    - No disaster recovery plans or critical data backups.
    - Absence of an Intrusion Detection System (IDS).
    - Legacy systems requiring manual monitoring and end-of-life maintenance.

## 3. Controls Assessment Checklist
| Control | Status (Yes/No) |
| :--- | :--- |
| Least Privilege | No |
| Firewall | Yes |
| Antivirus Software | Yes |
| Intrusion Detection System (IDS) | No |
| Disaster Recovery Plans | No |
| Encryption | No |
| Password Policies | No |

## 4. Compliance Checklist
- **PCI DSS:** Not compliant. Credit card data encryption and secure environment policies are not fully implemented.
- **GDPR:** Not compliant. Lack of data classification and a 72-hour breach notification plan for E.U. customers.
- **SOC1/SOC2:** Not compliant. User access policies and data integrity controls are insufficient.

## 5. Final Recommendations
1. Implement a **Least Privilege** access model immediately.
2. Deploy an **Intrusion Detection System (IDS)** to monitor anomalous traffic.
3. Establish a formal **Disaster Recovery Plan** with regular backups.
4. Enforce a **Centralized Password Management System** with complexity requirements.
