# SSH Brute Force Incident Report

## Overview
This repository contains a SOC investigation report documenting SSH brute-force activity observed against a Linux server.

## Incident Summary
- **Attack Type:** SSH Brute Force
- **Target:** Root account on Linux server (MTS-Web)
- **Source IP:** 64.190.113.134
- **Attempts Observed:** 546 failed authentication attempts
- **Successful Logins:** None
- **Severity:** Low

## Investigation Highlights
- Log analysis using authentication logs
- Correlation across extended time windows
- Verification of no lateral movement or post-authentication activity
- MITRE ATT&CK mapping

## MITRE ATT&CK
- **T1110 – Brute Force**

## Outcome
No compromise detected. Activity was limited to failed authentication attempts.

## Skills Demonstrated
- SIEM log analysis
- Incident documentation
- Timeline reconstruction
- Threat intelligence (OSINT)
- SOC reporting standards

## File
- `SSH_Brute_Force_Incident_Report.docx`

