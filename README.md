# Azure-SIEM-Project-Threat-Detection-with-Sentinel-AMA
This repository contains my Azure SIEM Project, where I configured a cloud-based Security Operations Center (SOC) using Microsoft Sentinel, Log Analytics, and the Azure Monitor Agent (AMA). The environment includes multiple virtual machines connected via a virtual network, simulating attacker and victim scenarios. Logs were analyzed using Kusto Query Language (KQL), visualized through Sentinel workbooks, and enriched with geolocation data to track real-time attack sources.



## 📸 Screenshots

| Screenshot | Description |
|-------------|-------------|
| ![Sentinel Logs] | Running KQL queries in Microsoft Sentinel to analyze logon events (4624/4625). |
| ![Workbook Chart] | Custom workbook visualizing logon activity over time. |
| ![Attack Map] | Workbook map showing geographic source of login attempts. |
| ![Virtual Machine]| Azure Virtual Machine used as the log source in the SIEM setup. |
