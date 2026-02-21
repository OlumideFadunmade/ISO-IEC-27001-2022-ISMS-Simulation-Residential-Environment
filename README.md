# ISO/IEC 27001:2022 ISMS Simulation – Residential Environment
## Project Overview
This project simulates the design and implementation of an ISO/IEC 27001:2022-aligned Information Security Management System (ISMS) within a residential household of three individuals.

The objective was to demonstrate core Governance, Risk & Compliance (GRC) competencies, including:
- Asset identification
- CIA-based risk assessment
- Risk treatment planning
- Annex A control mapping
- Statement of Applicability creation
- Internal audit simulation
- Management review documentation
- Continual improvement tracking
  
Although scaled to a domestic setting, the methodology mirrors enterprise ISO 27001 implementation practices

## 1 Context and Scope (Clause 4)
**Internal Context**
- Two remote working adults
- One child using digital learning tools
- Dependence on online banking and cloud storage
  
**External Context**
- Cybercrime threats (phishing, ransomware, fraud)
- Third-party cloud service reliance
- Internet service provider dependency
## Scope
The ISMS covers:
- Personal computing devices
- Home Wi-Fi network
- Financial accounts
- Cloud storage services
- Smart home devices
- Physical identity documents
## 2 Information Security Policy (Clause 5)
**Policy Statement**
The household is committed to:
- Protecting confidentiality of personal and financial data
- Ensuring integrity of digital records
- Maintaining availability of critical online services
- Implementing proportionate and risk-based controls
- Reviewing risks annually

**Policy Owner: Adult Household Member**

**Review Frequency: Annual**
## 3 Risk Assessment Methodology (Clause 6.1.2)
Risk Assessment Approach

i. Identify assets

ii. Identify threats and vulnerabilities

iii. Assign CIA impact (1–5)
| Score | Description                                                          |
| ----- | -------------------------------------------------------------------- |
| 1     | Low – Minimal inconvenience                                          |
| 2     | Minor – Limited disruption                                           |
| 3     | Moderate – Noticeable operational impact                             |
| 4     | Major – Significant disruption or financial loss                     |
| 5     | Severe – Identity theft, major financial loss, or legal consequences |


iv. Calculate Criticality = MAX(C,I,A)

v.  Assess Likelihood (1–5)

Likelihood reflects the probability of a threat exploiting a vulnerability.
| Score | Description                          |
| ----- | ------------------------------------ |
| 1     | Rare – Highly unlikely               |
| 2     | Unlikely – Has occurred infrequently |
| 3     | Possible – Could occur               |
| 4     | Likely – Occurs regularly            |
| 5     | Almost Certain – Highly probable     |

vi. Risk Score = Impact × Likelihood

**Where:**

Impact = Asset Criticality

Likelihood = Probability score

vii. Categorise:
- High (16–25)
- Medium (9–15)
- Low (1–8)
## 4 Asset Register
| Asset ID | Asset          | Type        | Owner     | C | I | A | Criticality |
| -------- | -------------- | ----------- | --------- | - | - | - | ----------- |
| H1       | Laptop         | Hardware    | Adult 1   | 5 | 4 | 4 | 5           |
| H2       | Router         | Network     | Household | 4 | 4 | 5 | 5           |
| H3       | Online Banking | Information | Adult 1   | 5 | 5 | 4 | 5           |
| H4       | Smartphone     | Hardware    | Adult 2   | 5 | 4 | 4 | 5           |
| H5       | Paper IDs      | Physical    | Household | 5 | 5 | 3 | 5           |

## 5 Risk Register
| Risk ID | Asset         | Threat           | Likelihood | Impact | Risk Score | Level  |
| ------- | ------------- | ---------------- | ---------- | ------ | ---------- | ------ |
| R1      | Banking       | Credential Theft | 4          | 5      | 20         | High   |
| R2      | Router        | Network Breach   | 4          | 5      | 20         | High   |
| R3      | Laptop        | Malware          | 3          | 5      | 15         | Medium |
| R4      | Paper IDs     | Theft            | 3          | 5      | 15         | Medium |
| R5      | Smart Devices | Privacy Breach   | 3          | 4      | 12         | Medium |

## 6  Risk Treatment Plan (Clause 6.1.3)
**High Risks**
- Enable MFA on financial accounts
- Change default router credentials
- Enable WPA3 encryption
- Full disk encryption on laptops
## Medium Risks
- Quarterly firmware updates
- Password manager implementation
- Secure physical document storage

## 7 Statement of Applicability (SoA)
| Control | Title                      | Applicable | Justification             | Status      |
| ------- | -------------------------- | ---------- | ------------------------- | ----------- |
| A.5.17  | Authentication Information | Yes        | Protect banking accounts  | Implemented |
| A.8.13  | Backup                     | Yes        | Ensure data recovery      | Implemented |
| A.7.2   | Physical Entry Controls    | Yes        | Protect ID documents      | Planned     |
| A.5.9   | Asset Inventory            | Yes        | Maintain asset visibility | Implemented |
| A.8.8   | Vulnerability Management   | Yes        | Manage device updates     | Implemented |

## 8 Internal Audit Report (Clause 9.2)
**Audit Scope**
- Asset register accuracy
- Risk treatment effectiveness
- Backup verification
- MFA implementation status
## Findings
- Asset register complete
- MFA enabled on all financial accounts
- Backup tested successfully
- Router firmware update overdue (Minor Finding)

**Conclusion**
ISMS controls are proportionate and functioning with minor improvement required.
## 9  Review Minutes (Clause 9.3)

Date: 12/01/26

Attendees: Adult 1, Adult 2

**Agenda**

- Risk review
- Audit findings
- Improvement opportunities

**Decisions**

- Approve firmware update schedule
- Review password strength annually
- Implement secure document safe
  
## 10 Continual Improvement Log (Clause 10)
| Date | Issue               | Action                     | Status    |
| ---- | ------------------- | -------------------------- | --------- |
| Q1   | Weak password reuse | Implement password manager | Completed |
| Q2   | No document safe    | Purchase lockbox           | Planned   |
| Q3   | Firmware delay      | Set reminder system        | Completed |

## Conclusion

This ISO/IEC 27001:2022 ISMS simulation demonstrates that structured information security governance can be applied effectively at any scale. While implemented in a residential environment, the framework reflects enterprise-grade risk management discipline.

The exercise confirms several key insights:

1. Financial systems and identity assets present the highest confidentiality and fraud risks.

2. Network infrastructure represents a critical availability and systemic risk point.

3. Remote working significantly increases dependency on device integrity and secure connectivity.

4. Formal documentation strengthens accountability and traceability, even in small environments.

5. Continual improvement is essential to maintaining security posture over time.

The ISMS lifecycle from risk identification through to audit and management review illustrates core GRC competencies, including:

- Risk-based decision making
- Control justification and mapping
- Governance documentation
- Audit awareness
- Proportionate risk treatment
- Continuous monitoring and improvement


