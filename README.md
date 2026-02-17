# Azure SIEM & Honeypot SOC Lab

This lab demonstrates hands-on skills in **Azure cloud security monitoring**, **SIEM integration**, and **SOC operations**.  

The lab simulates a real-world security operations scenario using honeypots, log collection, alerting, and threat detection to demonstrate **cloud security monitoring** and **incident response capabilities**.

---

## Lab Overview

- Deployed **Azure virtual machines** acting as a honeypot environment  
- Configured **Azure Sentinel (SIEM)** to collect logs and monitor for suspicious activity  
- Implemented **alert rules** and **playbooks** for automated incident detection and response  
- Simulated attack traffic to test **visibility, detection, and SOC workflows**

**Business Problem Solved:**  
- Provides hands-on experience detecting and responding to cloud-based attacks  
- Demonstrates the ability to set up proactive monitoring and incident response  
- Helps secure cloud workloads and maintain compliance with enterprise security standards  

---

## Honeypot Deployment

- Deployed **Azure VMs** with intentionally vulnerable services to act as honeypots  
- Configured **network security groups (NSGs)** to allow controlled traffic for monitoring  
- Monitored traffic for suspicious connections, brute-force attempts, and unusual patterns  

**Business Problem Solved:**  
- Enables detection of attack patterns in a safe environment  
- Provides real-world practice for identifying threats before they impact production systems  

---

## Log Collection & SIEM Integration

- Configured **Azure Sentinel** to collect logs from honeypots and other Azure resources  
- Enabled **diagnostic settings** to send activity and security logs to a Log Analytics workspace  
- Created **custom data connectors** to ingest simulated attack traffic  

**Business Problem Solved:**  
- Centralizes security logs for visibility and monitoring  
- Supports correlation of events to detect attacks early  

---

## Alerts & Automated Response

- Created **alert rules** to detect suspicious activity such as brute-force login attempts or abnormal traffic  
- Configured **action groups** and **playbooks** to notify SOC analysts via email or Teams  
- Tested alerts by simulating attacks on the honeypots to validate detection and response  

**Business Problem Solved:**  
- Ensures timely response to security incidents  
- Reduces risk by automating detection and notification workflows  

---

## SOC Monitoring & Threat Analysis

- Visualized security events in **Sentinel dashboards** for SOC analysts  
- Analyzed alerts and log trends to identify potential threats  
- Documented attack simulation results and response procedures  

**Business Problem Solved:**  
- Provides SOC analysts with actionable insights  
- Improves incident detection and threat mitigation capabilities  

---

## Platforms & Technologies Used

Azure Virtual Machines, Azure NSGs, Azure Log Analytics, Azure Sentinel (SIEM), Action Groups, Playbooks, Diagnostic Settings, Simulated Attack Traffic, GitHub  

---

## Summary

This lab demonstrates **end-to-end cloud security monitoring and SOC operations**, highlighting:

- **Honeypot deployment** for threat simulation  
- **Log collection and SIEM integration** for real-time monitoring  
- **Automated alerts and response** for proactive security  
- Practical experience in **incident detection, analysis, and cloud SOC workflows**
