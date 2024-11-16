# Network-Incident Response and hardening

<h2>Description</h2>
Incident Report: DNS and ICMP Traffic Analysis Leading to Port 443 Inaccessibility

Incident Overview:
This cybersecurity incident involved the inaccessibility of a secure web portal used by the HR team for employee background checks. The analysis revealed that HTTPS traffic through port 443 was unreachable, potentially indicating a web server misconfiguration or a malicious attack.

# Incident Details:
	1.	Issue Identification:
	•	HR team reported an inability to access the background check portal.
	•	Network protocol analysis using tcpdump confirmed that port 443 was unresponsive, disrupting HTTPS traffic.
	2.	Root Cause Analysis:
	•	Initial focus on potential web server or firewall misconfiguration.
	•	Further investigation into possible intentional disruption caused by an individual with a vested interest in disabling the portal, based on HR feedback.
	3.	Investigation Steps:
	•	Analyzed DNS and ICMP traffic logs for anomalies.
	•	Coordinated with system administrators to verify server integrity and check for attack signatures.

 # Proposed Remediation:
	•	Verify and adjust firewall rules to ensure proper handling of HTTPS traffic on port 443.
	•	Conduct a thorough audit of the web server to identify and mitigate potential vulnerabilities.
	•	Consider implementing anomaly detection mechanisms to identify and block suspicious traffic patterns in real-time.

 This case highlights the importance of proactive monitoring, precise traffic analysis, and collaboration across IT teams to address critical network disruptions effectively.

Keywords: #Cybersecurity #IncidentReport #TrafficAnalysis #Port443Issue #DNSLogs #FirewallManagement
