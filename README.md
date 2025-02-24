# SCCM/MECM Server Management  

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
- **Windows Server 2019**  
- **SQL Server (SQL Database)**  
- **System Center Configuration Manager / Microsoft Endpoint Configuration Manager**  
- **VirtualBox (Virtualization Software)**  

## Diagram  
![Diagram](https://raw.githubusercontent.com/JunedConnect/SCCM-MECM_Server_Management/main/images/SCCM%20Project.png)  
