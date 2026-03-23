# Day 40 - Hands-On Incident Response

**Focus:** Deep dive into the Incident Response (IR) process through a TryHackMe lab.

## Overview
Returned to cybersecurity practice after a short break, focusing on real-world application of the Incident Response lifecycle. The lab emphasized subtle, realistic scenarios without flashy alerts, highlighting the importance of observation, investigation, and system knowledge.

## Incident Response Phases Practiced
1. **Preparation** – Set up response plans, communication protocols, and toolkits.  
2. **Identification** – Detected unusual activity and confirmed an incident.  
3. **Containment** – Isolated affected systems to prevent further damage.  
4. **Eradication** – Removed malware and closed exploited vulnerabilities.  
5. **Recovery** – Restored operations from clean backups and monitored for reinfection.  
6. **Lessons Learned** – Reviewed logs and response steps to improve future readiness.

## Lab Scenario
- Escalated suspicious case: workstation with high CPU usage, unexplained slowness.  
- No EDR or SIEM alerts, but firewall logs showed persistent outbound connections to a single IP every second.  
- Highlighted the importance of detecting subtle indicators in a noisy environment.

## Actions Taken
- Collected evidence using Windows native tools (Task Manager, Resource Monitor, netstat).  
- Identified suspicious processes and network connections.  
- Queried autoruns, PowerShell history, and prefetch data.  
- Correlated user activity and anomalies via Windows Event Logs.  
- Developed containment and eradication plan.  
- Documented all stages of the IR process.

## Key Takeaways
- Realistic incident response requires more than alerts — it demands structured investigation and keen observation.  
- Practicing in a controlled lab helps build skills needed for ambiguous and subtle real-world attacks.  
- Effective IR combines technical expertise, careful analysis, and disciplined documentation.

