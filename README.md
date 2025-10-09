# 🛰️ SIEM Implementation in Azure Cloud – Microsoft Sentinel

## 🎯 Objective
To deploy and configure **Microsoft Sentinel** in the Azure cloud environment for real-time **threat detection**, **incident analysis**, and **automated response**, gaining hands-on experience with SIEM operations and KQL (Kusto Query Language).

---

## 🧰 Tools & Technologies Used
- **Microsoft Sentinel**
- **Azure Log Analytics Workspace**
- **Azure Security Center**
- **Kusto Query Language (KQL)**
- **Azure Monitor**
- **Microsoft Defender for Cloud**

---

## ⚙️ Steps Performed

1. **Deployed Microsoft Sentinel**
   - Created a **Log Analytics Workspace** in Azure.
   - Onboarded **Microsoft Sentinel** and linked it to the workspace.
   - Connected Azure resources such as **VMs**, **Azure AD**, and **Defender for Cloud** for continuous log collection.

2. **Configured Data Connectors**
   - Integrated multiple log sources including:
     - Azure Activity Logs  
     - SecurityEvent (Windows Defender)  
     - Sign-in logs from Azure AD  
   - Verified incoming data through **Log Analytics Queries**.

3. **Developed Custom Analytics Rules**
   - Wrote **KQL-based rules** to detect specific patterns and anomalies such as:
     - Multiple failed login attempts  
     - Suspicious PowerShell activity  
     - New administrative role assignments  
   - Enabled **rule alerting** and **automated incident creation**.

4. **Incident Investigation & Analysis**
   - Investigated alerts via the **Sentinel Investigation Graph**.  
   - Analyzed correlated events across hosts and users.  
   - Used **entity mapping** to trace attack paths and identify root causes.

5. **Remediation and Response**
   - Implemented **playbooks** using **Logic Apps** for automatic response:
     - Blocking suspicious IPs  
     - Disabling compromised user accounts  
     - Sending email notifications for critical alerts  
   - Verified that remediation actions executed correctly.

6. **Enhanced Threat Detection**
   - Configured advanced detection techniques including:
     - Scheduled analytics rules for pattern matching  
     - UEBA (User and Entity Behavior Analytics) for behavioral insights  
     - Threat intelligence feeds integration  

---

## 📸 Screenshots

Include **4–6 professional screenshots** that demonstrate deployment, detection, and response:

| Screenshot | Description |
|-------------|--------------|
| ![Sentinel Overview](./images/sentinel-overview.png) | Microsoft Sentinel workspace in Azure |
| ![Log Analytics Workspace](./images/log-analytics.png) | Linked Log Analytics workspace |
| ![KQL Analytics Rule](./images/kql-rule.png) | Custom KQL rule for failed login detection |
| ![Incident Investigation Graph](./images/incident-graph.png) | Sentinel incident investigation view |
| ![Logic App Automation](./images/logic-app.png) | Automated remediation playbook |
| ![UEBA Dashboard](./images/ueba-dashboard.png) | Behavior-based threat detection dashboard |

💡 *Ensure screenshots hide sensitive data such as usernames, IPs, or tenant IDs.*

---

## 🔒 Security & Operational Highlights

- Established a **centralized SIEM environment** in Azure for continuous monitoring.  
- Designed and implemented **custom KQL analytics rules** to detect targeted threats.  
- Automated incident response using **Azure Logic Apps** for faster remediation.  
- Strengthened cloud security posture through **Defender for Cloud integration**.

---

## 🧩 Key Takeaways

- Gained practical, hands-on experience in **SIEM deployment and management**.  
- Learned to **detect, investigate, and respond** to incidents using Sentinel.  
- Improved skills in **KQL scripting**, **log correlation**, and **incident automation**.  
- Built a scalable, cloud-based framework for enterprise-grade threat monitoring.

---

## 🚀 Next Steps (Optional Enhancements)

- Integrate Sentinel with **external threat intelligence feeds** (MSTICPy, AlienVault OTX).  
- Automate **report generation** for recurring security events.  
- Implement **SOC-style dashboards** using custom workbooks.  
- Combine Sentinel with **Power BI** for visualization and reporting.
