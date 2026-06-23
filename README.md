Incident Response End-to-End


SCENARIO 
Microsoft Defender Alert

Device: FINANCE-LAPTOP-07

Severity: High

Alert:
Trojan:Win32/RedLineStealer detected.

SHA256:
a84f9f1d75e2d43dba4d9f7f11e60b72c4c7f80cf3d5a22d54e11fbe0191aa12

User:
finance.user

Path:
C:\Users\finance.user\AppData\Roaming\updater.exe

Outbound Connection:
185.225.69.44:443



Overview

This project demonstrates a complete Incident Response lifecycle for a simulated malware compromise affecting a Windows workstation.

The investigation follows the NIST Incident Response process:

1. Triage
2. Scoping
3. Containment
4. Eradication
5. Recovery
6. After-Action Review

The scenario involves a Microsoft Defender alert identifying a RedLine Stealer infection on a finance department laptop.

The objective was to investigate the alert, determine impact, contain the threat, eradicate malicious artefacts, restore business operations, and document lessons learned.

Skills Demonstrated

- Incident Triage
- Threat Analysis
- Malware Investigation
- Evidence Preservation
- Containment
- Eradication
- Recovery Planning
- Executive Reporting
- After Action Review

Tools Referenced

- Microsoft Defender
- Windows Event Viewer
- PowerShell
- VirusTotal
- Sysinternals Autoruns

Outcome

The infected workstation was isolated, malware removed, credentials reset, persistence eliminated, and the system returned to production with no evidence of lateral movement.
