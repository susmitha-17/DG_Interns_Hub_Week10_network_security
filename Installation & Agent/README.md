## 🔐 Wazuh SIEM Installation & Agent Configuration

This section documents the installation and configuration of the **Wazuh Agent** on an Ubuntu Linux virtual machine as part of the Week 10 Cybersecurity Internship assessment — *SOC: Wazuh SIEM Setup & Alert Monitoring*.

### ⚙️ Installation & Setup
- Installed the Wazuh Agent package (`wazuh-agent_4.14.8-1_amd64.deb`) on Ubuntu Linux.
- Verified the agent service status using `systemctl` to confirm that the service was running.
- Reviewed the agent configuration file at `/var/ossec/etc/ossec.conf` to understand endpoint monitoring settings.
- Examined the connection between the endpoint agent and the central Wazuh Manager.

### 🛡️ Agent Monitoring & Configuration
- Reviewed **File Integrity Monitoring (FIM)** settings, including monitored directories, scan frequency, and scan-on-start configuration.
- Inspected Ubuntu system and authentication logs to understand endpoint activity and troubleshooting evidence.
- Created a harmless test file in the monitored home directory to support FIM testing.
- Investigated agent-to-manager connectivity and documented the limitations caused by the terminated Wazuh Cloud environment.

### 📌 Key Learning Outcomes
- Understood the role of the Wazuh Agent in collecting endpoint security data.
- Learned to verify service status, review configuration files, and interpret Linux system logs.
- Recognized that an active agent service does not necessarily confirm successful communication with the central SIEM.
- Practiced evidence-based troubleshooting and documented which monitoring results were verified and which remained unconfirmed.

**🧰 Technologies:** Wazuh Agent | Ubuntu Linux | SIEM | FIM | Linux System Logs | VirtualBox

**🎯 Focus:** Endpoint Monitoring • Security Event Analysis • SOC Fundamentals • Troubleshooting • Technical Documentation
