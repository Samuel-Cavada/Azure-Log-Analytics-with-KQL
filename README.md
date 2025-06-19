<p align="center">
  <a href="https://github.com/Samuel-Cavada" target="_blank">
    <img src="https://img.shields.io/badge/Back_to_Main_Page-000000?style=for-the-badge&logo=github&logoColor=white" alt="Back to Main Page"/>
  </a>
</p>

<h1 align="center">Querying Logs in Azure Log Analytics Workspace</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Cloud Platform" />
  <img src="https://img.shields.io/badge/OS-Windows_10-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="OS" />
  <img src="https://img.shields.io/badge/Tool-Log_Analytics-00B388?style=for-the-badge&logo=azuredevops&logoColor=white" alt="Tool" />
  <img src="https://img.shields.io/badge/Focus-Log_Analysis-orange?style=for-the-badge" alt="Focus Area" />
</p>

---

## Project Objective
> Learn how to access and run KQL-based queries in Azure Log Analytics Workspace for security or operational insights.

---

## Tools & Technologies
- **Platform:** Azure
- **OS:** Windows 10
- **Tools:** Azure Log Analytics
- **Languages/Scripts:** KQL (Kusto Query Language)

---

## Skills Gained / Focus Areas
- Navigated Azure Log Analytics Workspaces
- Switched query mode from default to KQL
- Executed KQL queries for log data analysis

---

## Environment Setup
> Accessed the Azure Portal with proper permissions to utilize Log Analytics Workspaces and run queries against ingested log data.

![Entra ID Authentication Success](https://github.com/Samuel-Cavada/Azure-Log-Analytics-with-KQL/raw/main/images/Entra%20ID%20(Azure)%20Authentication%20Success.jpg)





---

## Walkthrough
1. [Step 1: Search for Log Analytics Workspace](#step-1-search-for-log-analytics-workspace)
2. [Step 2: Open Logs and Set Query Mode](#step-2-open-logs-and-set-query-mode)
3. [Step 3: Run Queries Using KQL](#step-3-run-queries-using-kql)

---

### Step 1: Search for Log Analytics Workspace

→ Navigate to: `Azure Portal → Search → Log Analytics Workspaces → [Select Workspace]`

![Step 1](https://github.com/Samuel-Cavada/Azure-Log-Analytics-with-KQL/blob/main/images/ALAK1.png)

---

### Step 2: Open Logs and Set Query Mode

→ Navigate to: `Workspace → Logs → Query Editor → Change to KQL`

![Step 2](https://github.com/Samuel-Cavada/Azure-Log-Analytics-with-KQL/blob/main/images/ALAK2.png)

---

### Step 3: Run Queries Using KQL

→ Navigate to: `Query Editor → Type Query → Run`  
→ Use proper KQL syntax to explore log data  
→ Note: `Azure uses KQL, not SQL`

![Step 3](https://github.com/Samuel-Cavada/Azure-Log-Analytics-with-KQL/blob/main/images/ALAK3.png)

---

## Examples of Outputs

### Entra ID (Azure) Authentication Failures
<img src="https://github.com/Samuel-Cavada/Azure-Log-Analytics-with-KQL/raw/main/images/Entra%20ID%20(Azure)%20Authentication%20Failures.jpg" width="1000"/>

### Malicious Traffic Entering the Network
<img src="https://github.com/Samuel-Cavada/Azure-Log-Analytics-with-KQL/raw/main/images/Malicious%20Traffic%20Entering%20the%20Network.jpg" width="1000"/>

### VM Authentication Failures
<img src="https://github.com/Samuel-Cavada/Azure-Log-Analytics-with-KQL/raw/main/images/VM%20Authentication%20Failures.jpg" width="1000"/>


---

## Outcomes and Lessons Learned
- **Technical Insight:** Gained hands-on experience querying logs using KQL.
- **Configuration Skills:** Learned how to navigate to and prepare the workspace for querying.
- **Troubleshooting:** Understood the importance of correct query mode.
- **Takeaway:** Azure Log Analytics requires a shift from traditional SQL to KQL for effective querying.

---

## References
- [Microsoft Learn – Log Analytics](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/log-analytics-overview)
- [KQL Documentation](https://learn.microsoft.com/en-us/azure/data-explorer/kusto/query/)
