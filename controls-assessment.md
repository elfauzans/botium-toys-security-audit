# Botium Toys – Controls Assessment

## Overview

This document summarizes the security controls assessment conducted for
Botium Toys as part of an internal security audit.

The assessment reviewed whether existing security controls were currently
implemented and identified areas requiring improvement.

## Assessment Results

| Security Control | Status | Finding |
|---|---|---|
| Least Privilege | ❌ Not Implemented | Access is not restricted based on minimum required privileges. |
| Disaster Recovery Plans | ❌ Not Implemented | No disaster recovery plan is currently in place. |
| Password Policies | ✅ Implemented | A password policy exists, but its requirements are weak. |
| Separation of Duties | ❌ Not Implemented | Separation of duties has not been implemented. |
| Firewall | ✅ Implemented | A firewall is configured to block unwanted traffic based on security rules. |
| Intrusion Detection System (IDS) | ❌ Not Implemented | No IDS has been installed. |
| Backups | ❌ Not Implemented | Critical data is not currently backed up. |
| Antivirus Software | ✅ Implemented | Antivirus software is installed and regularly monitored. |
| Legacy System Monitoring | ✅ Implemented | Legacy systems are monitored and maintained, but there is no regular schedule. |
| Encryption | ❌ Not Implemented | Encryption is not currently used to protect customer credit card information. |
| Password Management System | ❌ Not Implemented | No centralized password management system is available. |
| Physical Locks | ✅ Implemented | Offices, storefront, and warehouse have sufficient locks. |
| CCTV Surveillance | ✅ Implemented | Up-to-date CCTV surveillance is in place. |
| Fire Detection/Prevention | ✅ Implemented | Fire detection and prevention systems are functioning. |

## Key Findings

The assessment identified several security gaps:

- Least privilege is not implemented.
- Separation of duties is not implemented.
- Sensitive customer information is not encrypted.
- No intrusion detection system is deployed.
- Critical data is not backed up.
- No disaster recovery plan exists.
- Password requirements are weak.
- No centralized password management system exists.
- Legacy system maintenance does not have a regular schedule.

## Positive Controls

The organization currently has several controls in place:

- Firewall
- Antivirus software
- Physical locks
- CCTV surveillance
- Fire detection and prevention
- Data availability controls
- Data integrity controls

## Risk Considerations

The overall risk assessment for Botium Toys was rated **8/10 (fairly high)**.

The most important areas for improvement are access control, data protection,
incident detection, backup and recovery, and password management.

## Recommended Priorities

1. Implement least privilege.
2. Implement separation of duties.
3. Encrypt sensitive customer and payment information.
4. Deploy an IDS.
5. Implement regular backups.
6. Develop a disaster recovery plan.
7. Implement centralized password management.
8. Strengthen password requirements.
9. Establish a regular legacy-system maintenance schedule.