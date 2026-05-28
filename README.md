# Controls & Compliance Security Audit — Botium Toys

## Overview

This project documents a structured security audit of Botium Toys, a fictional toy company, assessed against industry-standard compliance frameworks. Starting from a scope, goals, and risk assessment report, I evaluated which security controls were in place, identified critical gaps, and mapped those gaps against three regulatory frameworks: **PCI DSS**, **GDPR**, and **SOC Type 1 & 2**.
---

## Objectives

- Assess which administrative, technical, and physical controls are currently implemented
- Identify compliance gaps across PCI DSS, GDPR, and SOC frameworks
- Prioritise remediation by risk level
- Produce actionable recommendations for the IT manager
---

## Priority Recommendations

### Priority 1 — Immediate Action
1. **Least Privilege & Separation of Duties** — All employees currently have access to customer and cardholder data; restrict access to role-based minimum
2. **Encryption** — Card data and PII stored/transmitted without encryption; direct PCI DSS violation
3. **Password Policy & Password Management System** — Weak credentials create easy entry points for attackers

### Priority 2 — Near Term
4. **Intrusion Detection System (IDS)** — No visibility into active breaches
5. **Backups & Disaster Recovery Plan** — No recovery path after ransomware or hardware failure
6. **Legacy System Monitoring** — Unmonitored legacy systems are prime exploit targets

### Priority 3 — Compliance Posture
7. **Data Classification & Inventory** — Required for GDPR compliance and access control enforcement
8. **Formal User Access Policies** — Required for SOC 2 compliance
---

## Skills Demonstrated

- Security controls assessment
- Compliance framework mapping (PCI DSS, GDPR, SOC)
- Risk-based prioritisation
- Security audit documentation
- Gap analysis and remediation planning

---

*Popoola Moses · Google Cybersecurity Certificate Program*
