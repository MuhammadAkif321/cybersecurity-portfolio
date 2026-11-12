# Compliance Assessment

The checklist asks whether Botium Toys currently follows each stated best practice. The judgments below are based on the supplied fictional scenario.

## 1. Payment Card Industry Data Security Standard (PCI DSS)

PCI DSS is a payment-card industry security standard intended to protect payment account data.

| # | Best practice | Yes / No | Scenario-based reason |
|---:|---|:---:|---|
| 1 | Only authorized users have access to customers' credit card information. | No | All employees can access internally stored data and may be able to access cardholder information. |
| 2 | Credit card information is handled internally in a secure environment. | No | The report says card information is processed and stored locally without encryption, while access is too broad. |
| 3 | Implement data encryption procedures to secure card transaction touchpoints and data. | No | Encryption is not currently used for the described credit card information. |
| 4 | Adopt secure password management policies. | No | The password policy has weak requirements and there is no centralized password management system. |

## 2. General Data Protection Regulation (GDPR)

GDPR is an EU data protection and privacy regulation.

| # | Best practice | Yes / No | Scenario-based reason |
|---:|---|:---:|---|
| 1 | E.U. customers' data is kept private and secured. | No | All employees have broad access to internal data, and the report identifies missing protections for sensitive information. |
| 2 | A plan exists to notify E.U. customers within 72 hours if their data is compromised. | Yes | The report explicitly says a 72-hour notification plan has been established. |
| 3 | Ensure data is properly classified and inventoried. | No | Asset management is inadequate, and the report says the organization needs to identify and classify its assets. |
| 4 | Enforce privacy policies, procedures, and processes to document and maintain data. | Yes | The report says privacy policies, procedures, and processes have been developed and are enforced. |

**Regulatory clarification:** The course scenario describes a plan to notify E.U. customers within 72 hours. Under GDPR, the general 72-hour notification requirement applies to notifying the relevant supervisory authority of a personal-data breach when notification is required. Individuals must be informed without undue delay when the breach is likely to result in a high risk to their rights and freedoms. This checklist answer reflects the scenario's wording, not a legal determination that Botium Toys meets GDPR.

## 3. System and Organization Controls (SOC Type 1 / Type 2) checklist

SOC reports concern controls at service organizations. The following are the scenario-based answers to the course checklist statements; they do not establish that the company has a SOC report or has passed a SOC examination.

| # | Best practice | Yes / No | Scenario-based reason |
|---:|---|:---:|---|
| 1 | User access policies are established. | No | The report says least privilege and separation of duties have not been implemented, and all employees have broad access to internal data. |
| 2 | Sensitive data (PII/SPII) is confidential/private. | No | Broad employee access means sensitive customer information is not adequately restricted. |
| 3 | Data integrity ensures data is consistent, complete, accurate, and validated. | Yes | The report says the IT department has integrated controls to ensure data integrity. |
| 4 | Data is available to individuals authorized to access it. | Yes | The report says availability is ensured. |

## Overall observation

The scenario indicates gaps in access restriction, confidentiality, encryption, password management, and asset classification. Some practices are reported as present, including a breach-notification plan, enforced privacy procedures, data integrity controls, and availability controls. A Yes answer is limited to what the scenario states and is not independent proof of regulatory compliance.
