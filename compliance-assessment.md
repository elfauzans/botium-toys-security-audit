# Botium Toys – Compliance Assessment

## Overview

This document summarizes the compliance assessment conducted for
Botium Toys as part of an internal security audit.

The assessment reviewed selected compliance best practices related to
PCI DSS, GDPR, and SOC.

---

## 1. Payment Card Industry Data Security Standard (PCI DSS)

| Compliance Best Practice | Status | Finding |
|---|---|---|
| Only authorized users have access to customers' credit card information | ❌ Not Met | All employees have access to internally stored data and may be able to access cardholder data. |
| Credit card information is stored, accepted, processed, and transmitted internally in a secure environment | ❌ Not Met | Credit card information is stored internally without encryption. |
| Implement data encryption procedures | ❌ Not Met | Encryption is not currently used to protect customer credit card information. |
| Adopt secure password management policies | ❌ Not Met | The password policy is weak and there is no centralized password management system. |

### PCI DSS Assessment Summary

Botium Toys has several gaps related to protecting cardholder information.
The most significant issues are excessive access, lack of encryption,
and weak password management.

---

## 2. General Data Protection Regulation (GDPR)

| Compliance Best Practice | Status | Finding |
|---|---|---|
| E.U. customers' data is kept private/secured | ❌ Not Met | All employees have access to internally stored data and may be able to access PII/SPII. |
| Plan to notify E.U. customers within 72 hours of a breach | ✅ Met | Botium Toys has established a plan to notify E.U. customers within 72 hours. |
| Ensure data is properly classified and inventoried | ❌ Not Met | Asset management is inadequate and assets have not been properly identified and classified. |
| Enforce privacy policies, procedures, and processes | ✅ Met | Privacy policies, procedures, and processes have been developed and enforced. |

### GDPR Assessment Summary

Botium Toys has established privacy policies and a 72-hour breach
notification plan, but improvements are needed in data protection,
classification, inventory, and access controls.

---

## 3. System and Organizations Controls (SOC)

| Compliance Best Practice | Status | Finding |
|---|---|---|
| User access policies are established | ❌ Not Met | Least privilege and separation of duties have not been implemented. |
| Sensitive data (PII/SPII) is confidential/private | ❌ Not Met | Employees may have access to internally stored PII/SPII. |
| Data integrity ensures data is consistent, complete, accurate, and validated | ✅ Met | The IT department has implemented controls to ensure data integrity. |
| Data is available to individuals authorized to access it | ✅ Met | The IT department has ensured data availability. |

### SOC Assessment Summary

Botium Toys has controls supporting data integrity and availability,
but user access and sensitive-data confidentiality require improvement.

---

## Overall Compliance Findings

The assessment identified several compliance gaps:

- Excessive access to sensitive information
- Lack of encryption for credit card information
- Weak password requirements
- No centralized password management system
- Inadequate asset classification and inventory
- Insufficient controls for PII/SPII confidentiality

## Recommended Compliance Improvements

1. Implement least privilege.
2. Restrict access to cardholder data.
3. Encrypt sensitive and payment information.
4. Strengthen password requirements.
5. Implement centralized password management.
6. Properly classify and inventory organizational assets.
7. Improve protection of PII/SPII.
8. Regularly review compliance requirements and security controls.

## Conclusion

Botium Toys has several security and compliance practices in place,
but significant gaps remain. Addressing access control, encryption,
password management, asset classification, and sensitive-data protection
should be prioritized to improve the organization's security posture.