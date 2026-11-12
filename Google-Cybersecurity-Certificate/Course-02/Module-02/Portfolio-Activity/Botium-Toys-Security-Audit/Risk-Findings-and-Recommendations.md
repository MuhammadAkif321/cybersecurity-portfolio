# Risk Findings and Recommendations

## 1. Overall risk

The supplied risk assessment assigns Botium Toys a risk score of **8 out of 10**, described as fairly high.

The report rates the potential impact from the loss of an asset as medium because the IT department does not know which assets would be at risk. It rates the risk of asset loss or fines from governing bodies as high because necessary controls and compliance best practices are missing.

## 2. Key findings

### Finding 1: Excessive access to sensitive information

**Evidence:** All employees have access to internally stored data and may be able to access cardholder data and customers' PII/SPII.

**Risk:** An employee account could expose more information than is necessary for that employee's role. A compromised account could also have a wider impact.

**Recommendation:** Implement role-based access and least privilege. Review access regularly, remove unnecessary permissions, and separate incompatible duties.

### Finding 2: Sensitive payment data is not encrypted

**Evidence:** The report says encryption is not used for customer credit card information accepted, processed, transmitted, and stored locally.

**Risk:** Exposed payment information could harm customers and create financial, legal, and reputational consequences.

**Recommendation:** Review the payment-card data flow, minimize stored card data, and implement appropriate encryption and other PCI DSS security requirements. Use qualified payment and security professionals to validate the design.

### Finding 3: No backups or disaster recovery plan

**Evidence:** The company has no backups of critical data and no disaster recovery plans.

**Risk:** A ransomware attack, hardware failure, or other incident could cause prolonged disruption or permanent data loss.

**Recommendation:** Establish tested, protected backups and a documented disaster recovery and business continuity plan. Define recovery priorities and test restoration regularly.

### Finding 4: No intrusion detection system

**Evidence:** The IT department has not installed an IDS.

**Risk:** Suspicious or malicious network activity may be harder to identify promptly.

**Recommendation:** Evaluate and deploy suitable detection capabilities, configure alerts, and establish procedures for reviewing and responding to alerts.

### Finding 5: Weak password practices

**Evidence:** A password policy exists but has weak requirements. There is no centralized password management system.

**Risk:** Weak or reused passwords can increase the likelihood of account compromise. Manual password resets may also affect productivity.

**Recommendation:** Improve authentication policy, use secure centralized password management, and consider multi-factor authentication where appropriate.

### Finding 6: Incomplete asset management and legacy-system procedures

**Evidence:** Asset management is inadequate. Legacy systems are monitored and maintained, but there is no regular schedule and intervention methods are unclear.

**Risk:** The organization may not know which systems are most important or which outdated systems need urgent attention.

**Recommendation:** Create and maintain an asset inventory, classify assets by sensitivity and business impact, assign owners, and schedule legacy-system reviews and documented interventions.

## 3. Recommended priority order

1. Restrict access to cardholder data and customer PII/SPII.
2. Protect payment and sensitive data using appropriate encryption and payment-security practices.
3. Create protected backups and test disaster recovery.
4. Strengthen password and authentication practices.
5. Improve monitoring and detection capabilities.
6. Complete asset inventory and classification.
7. Document, test, and regularly review security procedures and compliance obligations.

## 4. Existing controls worth maintaining

The scenario reports that Botium Toys already has a firewall, antivirus software, physical locks, CCTV, and fire detection/prevention systems. It also has a password policy, legacy-system monitoring, privacy procedures, a breach-notification plan, and controls supporting integrity and availability.

The organization should maintain these safeguards while improving the weaknesses identified above. Existing controls should be periodically reviewed to confirm that they continue to work as intended.

## 5. Conclusion

Botium Toys has some important safeguards, but the scenario reveals significant weaknesses in access control, payment-data protection, backup and recovery, detection, password management, and asset management. Addressing these gaps in a risk-based order can improve the company's security posture and support business continuity.

*Recommendations are educational suggestions based on the fictional scenario, not legal advice or a formal remediation plan.*
