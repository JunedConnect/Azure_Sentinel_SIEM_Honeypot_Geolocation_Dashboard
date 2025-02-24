# Azure Sentinel SIEM Honeypot Geolocation Dashboard  

## Description  
Set up an **SCCM/MECM Server** to facilitate **centralized system management** and **streamline software deployment** across my home network. Additionally, three separate systems were configured:  

- **DHCP/NAT Server** to manage **internet connectivity** and dynamically assign **IP addresses** to all devices.  
- **Domain Controller Server** to administer **Active Directory**, ensuring **secure access** to network resources.  
- **Windows 10 VM** as a **test system** for software deployment.  

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
