# Architecture

## SOC Lab Infrastructure

The SOC Lab consists of four virtual machines connected through an isolated VirtualBox Host-Only network (192.168.56.0/24).

### Components

* Wazuh Server (192.168.56.110)

  * Wazuh Manager
  * Wazuh Indexer
  * Wazuh Dashboard

* Linux Target (192.168.56.101)

  * Ubuntu 24.04 Desktop
  * Wazuh Agent
  * UFW Firewall

* Windows Target (192.168.56.103)

  * Windows Server 2022
  * Wazuh Agent
  * Sysmon

* Kali Attacker (192.168.56.104)

  * Nmap
  * Hydra
  * Mimikatz
  * Netcat

### Network

* Host-Only Network: 192.168.56.0/24
* Wazuh communication port: TCP 1514

### Detection Coverage

* T1046 – Network Service Discovery
* T1110.003 – Brute Force
* T1003 – Credential Dumping
* T1547.001 – Registry Run Keys
* T1041 – Exfiltration Over C2 Channel
