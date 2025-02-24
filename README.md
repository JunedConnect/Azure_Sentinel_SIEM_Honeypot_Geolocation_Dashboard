# Azure Sentinel SIEM Honeypot Geolocation Dashboard  

<br>

## Description  
- Set up an **Azure Workspace** with **vulnerable VMs**, **Log Analytics Workspace**, and **Sentinel**.  
- Deployed a **PowerShell script** and **API** for **Windows Event Viewer metadata extraction** (IoC Enrichment).  
- Configured **Azure Log Analytics Workspace** to **ingest and parse metadata**.  
- Pipelined parsed data into **Azure Sentinel** for **global attack data display** using a **workbook**.  

## Impact  
Enhanced **threat visibility** with **geolocation insights** (**over 3,000 attack attempts**), enabling:  
- **Effective monitoring of attacks** (threat hunting).  
- **Improved incident response**.  
- **Escalation of critical threats to stakeholders**.  

## Technology Used  
- **Azure Sentinel (Cloud Platform)**  
- **PowerShell (Scripting Language)**  
- **Log Analytics Workspace (Log Storage)**  
- **API Integration**  
- **KQL (Query Language)**


## Demo  

### **1. RDP Failed Attempts Query**
This query retrieves **failed RDP login attempts**, allowing for **threat analysis and attack pattern identification**.

<br>

![RDP Failed Attempts Query](https://raw.githubusercontent.com/JunedConnect/Azure_Sentinel_SIEM_Honeypot_Geolocation_Dashboard/main/images/RDP%20Failed%20Attempts%20Query.PNG)  

<br>

### **2. RDP Failed Attempts Report**
This report provides a **visual breakdown of failed login attempts**, offering insights into **attack frequency and geolocation data**.

<br>

![RDP Failed Attempts Report](https://raw.githubusercontent.com/JunedConnect/Azure_Sentinel_SIEM_Honeypot_Geolocation_Dashboard/main/images/RDP%20Failed%20Attempts%20Report.PNG)  
