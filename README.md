# 🛡️ SOC Detection Lab — Cloud-Native SIEM & EDR

A hands-on Blue Team project demonstrating cloud-native security monitoring using Wazuh SIEM, AWS EC2, Sysmon, and Atomic Red Team attack simulations.

## 🏗️ Architecture

| Component | Instance | OS | Role |
|---|---|---|---|
| Wazuh Manager | c7i-flex.large | Ubuntu 22.04 | SIEM, Dashboard, Rules Engine |
| Ubuntu Agent | t3.micro | Ubuntu 22.04 | Linux Endpoint |
| Windows Agent | t3.micro | Windows Server 2022 | Windows Endpoint + Sysmon |

## 📁 Repository Structure
