# AZURE-SENTINEL-HONEYPOT-LAB
This project demonstrates the deployment of a Windows 10 honeypot in Microsoft Azure and the collection of security telemetry using Microsoft Sentinel. The environment was configured to intentionally expose a virtual machine to the internet, collect failed authentication attempts, enrich attack data with geographic information, and visualize attack activity on a global map.

## Objectives:
1. Create a Resource Group
2. Create Virtual Network
3. Create Virtual Machine (Honeypot/Attack Surface)
4. Make Network Security Group Vulnerable (Open Firewall to public internet)
   - Deleted Remote Desktop Inbound Rule
   - Added a ANY connection Inbound Rule (DANGEROUS)
5. Disable VM internal Firewall
6. Test Public Access by Pinging VM Public IP Address with Local Machine
7. Explore some VM Event Logs after deliberately failing to Login into the VM
8. 

## Skills Demonstrated:

- Microsoft Azure
- Microsoft Sentinel
- SIEM Operations
- Log Analytics Workspace
- Kusto Query Language (KQL)
- Windows Event Logs
- Security Monitoring
- Threat Detection
- Log Forwarding
- Attack Surface Exposure
- GeoIP Enrichment
- Incident Investigation
- Cloud Security

## Technologies Used:
- Azure Virtual Machines
- Microsoft Sentinel
- Log Analytics Workspace
- Windows 11
- Azure Monitor Agent (AMA)
- Data Collection Rules (DCR)
- KQL
- GeoIP Watchlists
- Azure Network Security Groups
