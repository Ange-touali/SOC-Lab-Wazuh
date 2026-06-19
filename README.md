# SOC-Lab-Wazuh

Security Operations Center (SOC) laboratory built with Wazuh SIEM, Sysmon, VirtualBox and MITRE ATT&CK.

## Project Overview

This project simulates a complete SOC environment for threat detection, alert triage, incident investigation and incident response.

## Technologies

* Wazuh 4.7.5
* Sysmon
* VirtualBox
* Ubuntu 24.04
* Windows Server 2022
* Kali Linux

## MITRE ATT&CK Techniques

* T1046 - Network Service Discovery
* T1110.003 - Brute Force
* T1003 - Credential Dumping
* T1547.001 - Registry Run Keys / Startup Folder
* T1041 - Exfiltration Over C2 Channel

## Detection Capabilities

* 19 Custom Wazuh Detection Rules
* Windows & Linux Monitoring
* Incident Runbooks
* MITRE ATT&CK Mapping
* SOC Incident Reporting
* Event Correlation

## Project Team

* Tchjima KONE — SOC Engineer
* Stéphane ZUNON — Detection Analyst
* Rohon YESSOH — Incident Analyst

## My Role

As Detection Analyst, I contributed to:

* MITRE ATT&CK mapping
* Development of custom Wazuh detection rules
* Attack simulation from Kali Linux
* Alert validation and analysis in the Wazuh dashboard
* Detection tuning and verification

## Results

* Detection Rate: 95%
* Mean Time To Detect (MTTD): < 1 minute
* False Positive Rate: < 5%

## Project Status

Completed

- 95% Detection Rate
- MTTD < 1 minute
- False Positives < 5%
