# Active Directory Lab

### Objective
The Active Directory Detection Lab project involved the deployment of a virtualized domain environment integrated with Splunk, Kali Linux, and the Atomic Red Team framework. The primary objective was to engineer a robust pipeline for ingesting security events into a SIEM, enabling deep analysis of enterprise-level telemetry. By simulating adversary techniques seen in the real world, the project provided hands-on experience in correlating log data with specific attack patterns to refine detection logic and defensive posture.

### Skills Learned
- Mastered centralized log ingestion and complex data correlation within Splunk.
- Simulated real-world threat TTPs using the MITRE ATT&CK framework and Atomic Red Team.
- Analyzed and interpreted disparate data sources, including Sysmon and Windows Event Logs.
- Identified malicious traffic patterns and protocol anomalies across TCP/IP, DNS, and HTTP/S.
- Applied structured methodologies for alert triage, root-cause analysis, and threat mitigation.

### Tools Used
- Virtualization: VMware Fusion Pro (Apple Silicon Architecture).
- SIEM: Splunk Enterprise (Advanced SPL Querying).
- Operating Systems: Windows Server Core, Ubuntu Server (Headless), and Kali Linux.
- Telemetry & Logging: Sysmon, Windows Event Logs, and Splunk Universal Forwarder.
- Adversary Emulation: Atomic Red Team (MITRE ATT&CK Framework).
- Network Monitoring: Zeek (Network Metadata Analysis).
- Threat Intelligence: MISP (Indicators of Compromise Correlation).

## Steps
I started by mapping out a diagram of the network.

*Ref 1: Network Diagram* <br>
<img width="707" height="578" alt="Screenshot 2026-04-14 at 07 15 06" src="https://github.com/user-attachments/assets/950d49d4-a9d1-4e6e-a6d2-9271fc050c9d" />
