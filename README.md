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

1. **Microsoft Sentinel workspace in Azure** <img width="2545" height="1490" alt="Screenshot 2025-10-19 001244" src="https://github.com/user-attachments/assets/31233b3c-df76-4e3f-92f5-8acd7c591008" />


2. **Custom KQL rule for failed login detection**  <img width="2539" height="1391" alt="Screenshot 2025-10-19 002014" src="https://github.com/user-attachments/assets/b416b0dd-f830-4e4a-8477-ea7c14e54d79" />

3. **Sentinel incident investigation view**  <img width="2543" height="980" alt="Screenshot 2025-10-19 112520" src="https://github.com/user-attachments/assets/66f5dd7b-5f95-4dfb-80e5-c43debf858c6" />

4. **Closing tickets** <img width="2553" height="1288" alt="Screenshot 2025-10-19 121047" src="https://github.com/user-attachments/assets/1d893c8d-f85c-4a43-9660-bddd90eab5b4" />

---

## 🧩 Key Takeaways

- Gained practical, hands-on experience in **SIEM deployment and management**.  
- Learned to **detect, investigate, and respond** to incidents using Sentinel.  
- Improved skills in **KQL scripting**, **log correlation**, and **incident automation**.  
- Built a scalable, cloud-based framework for enterprise-grade threat monitoring.
