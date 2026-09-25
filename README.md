# End-to-End Active Directory Cyberattack Detection, Containment, Eradication & Recovery Framework

**Author:** Chiamaka Odumegwu | Cybersecurity Engineer
**Tools:** Microsoft Sentinel · Microsoft Defender for Identity (MDI) · 
Microsoft Defender XDR · Azure Logic Apps (SOAR) · KQL · Active Directory

---

## Overview
This project documents a complete Active Directory cyberattack simulation 
and response framework built in Microsoft Azure. It covers the full NIST 
SP 800-61 Incident Response lifecycle — from attack simulation through to 
detection, containment, eradication, and recovery.

---

## What Was Built
- 3-VM Azure lab environment (Domain Controller, Client Machine, Kali Linux attacker)
- Password Spray and Kerberoasting attack simulation
- Real-time attack detection using Microsoft Defender for Identity and Microsoft Sentinel
- 3 custom SOAR playbooks in Azure Logic Apps for automated incident containment
- Full account recovery and Kerberos encryption hardening (RC4 → AES128+AES256)

---

## Key Outcomes
- Achieved first centralised, real-time visibility into identity-based attacks 
  across the Active Directory environment
- Automated incident response — compromised accounts contained and disabled 
  without manual intervention
- Hardened domain against future Kerberoasting attempts through encryption upgrade
- Produced full technical documentation aligned to incident response standards

---

## Certifications
SC-200 · AZ-500 · SC-300 · SC-401 · ISC2 CC

---

## Full Documentation
See the PDF report uploaded in this repository for the complete 
implementation walkthrough, screenshots, and lessons learned.
