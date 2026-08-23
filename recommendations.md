# Botium Toys – Security Recommendations

## Overview

This document provides security recommendations based on the findings
identified during the Botium Toys internal security audit.

The recommendations focus on reducing security risks, protecting
sensitive data, improving compliance, and strengthening the organization's
overall security posture.

---

## Priority 1 – Implement Access Controls

### Finding

Least privilege and separation of duties have not been implemented.
Employees may have access to internally stored data, including
cardholder data and customer PII/SPII.

### Recommendation

Implement the principle of least privilege and separation of duties.

Access should be limited to the information and systems required for
employees to perform their assigned responsibilities.

### Expected Benefit

- Reduce unauthorized access
- Reduce insider risk
- Protect sensitive customer information
- Improve confidentiality

---

## Priority 2 – Implement Encryption

### Finding

Customer credit card information is stored internally without encryption.

### Recommendation

Implement encryption to protect sensitive customer and payment
information when it is stored and handled internally.

### Expected Benefit

- Improve confidentiality
- Reduce exposure of sensitive information
- Strengthen protection of cardholder data

---

## Priority 3 – Implement Backup and Disaster Recovery

### Finding

Botium Toys does not currently have backups of critical data or a
disaster recovery plan.

### Recommendation

Establish regular backups of critical data and develop a disaster
recovery plan to support business continuity.

### Expected Benefit

- Improve data recovery
- Reduce the impact of security incidents
- Support business continuity
- Reduce potential data loss

---

## Priority 4 – Improve Password Security

### Finding

A password policy exists, but its requirements are weak. There is also
no centralized password management system.

### Recommendation

Strengthen password requirements and implement centralized password
management.

### Expected Benefit

- Reduce account compromise risk
- Improve enforcement of password requirements
- Reduce password recovery and reset issues
- Improve security and productivity

---

## Priority 5 – Implement Intrusion Detection

### Finding

Botium Toys does not currently have an intrusion detection system (IDS).

### Recommendation

Implement an IDS to help detect suspicious or anomalous network activity.

### Expected Benefit

- Improve threat detection
- Improve security monitoring
- Help identify potential security incidents

---

## Priority 6 – Improve Legacy System Management

### Finding

Legacy systems are monitored and maintained, but there is no regular
schedule and intervention methods are unclear.

### Recommendation

Establish a regular monitoring and maintenance schedule for legacy
systems and clearly document intervention procedures.

### Expected Benefit

- Reduce risks associated with outdated systems
- Improve consistency of maintenance
- Help identify vulnerabilities earlier

---

## Priority 7 – Improve Asset Classification and Inventory

### Finding

Botium Toys currently has inadequate asset management and does not have
a clear understanding of which assets would be at risk if lost.

### Recommendation

Identify, classify, and maintain an inventory of organizational assets.
Determine the potential impact of losing each asset and consider its
importance to business continuity.

### Expected Benefit

- Improve asset visibility
- Improve risk assessment
- Support better security decisions
- Improve business continuity planning

---

## Priority 8 – Improve Compliance

### Finding

Several PCI DSS, GDPR, and SOC-related best practices are not currently
met.

### Recommendation

Review applicable compliance requirements regularly and align security
controls and processes with those requirements.

Priority areas include:

- Cardholder data protection
- PII/SPII protection
- Data classification
- Access controls
- Encryption
- Password management

### Expected Benefit

- Reduce compliance risk
- Improve protection of sensitive data
- Reduce potential penalties
- Strengthen security posture

---

## Recommended Implementation Order

1. Access control and sensitive-data protection
2. Encryption
3. Backups and disaster recovery
4. Password security
5. Intrusion detection
6. Asset classification and inventory
7. Legacy system management
8. Compliance improvements

---

## Conclusion

Botium Toys has several foundational security controls in place,
including firewalls, antivirus software, CCTV, physical locks, and fire
detection/prevention systems.

However, the audit identified significant gaps in access control,
encryption, backup and recovery, password management, intrusion
detection, asset management, and compliance.

Addressing these areas in priority order will help reduce risk and
improve Botium Toys' overall security posture.