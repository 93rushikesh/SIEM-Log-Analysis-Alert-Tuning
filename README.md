# SIEM Log Analysis & Alert Tuning Lab

## 🎯 Project Objective
Deployed a standalone SIEM environment to absorb and correlate log data across the network environment. The primary focus was on analyzing security events and sharpening alert thresholds ("Alert Tuning") to cut down background noise (false positives) and surface real threats faster.

## 🛠️ Tools & Technologies Used
* **SIEM Platform:** Splunk / Wazuh / ELK Stack (तुमचे टूल निवडा)
* **Log Sources:** Windows Security Logs, Firewall Logs, Syslog
* **Key Concept:** Alert Tuning & Noise Reduction

## 🚀 Key Learning & Practical Steps Done
* **Log Ingestion & Correlation:** Collected log data from multiple sources across the environment and correlated events to track suspicious activity.
* **Baseline Traffic Analysis:** Monitored normal network and system behavior to understand baseline logs and identify what triggers non-threatening alerts.
* **Alert Tuning (Sharpening Thresholds):** * Identified high-volume rules creating false positives (e.g., standard admin actions triggering brute force alerts).
  * Adjusted alert criteria and thresholds to reduce "Alert Fatigue" for SOC analysts.
* **True Threat Visibility:** Optimized the correlation rules so that only high-confidence indicators of compromise (IoCs) trigger critical alerts, speeding up real incident response time.

## 📈 Project Outcomes
* Successfully reduced false positive alert volume by adjusting rule thresholds.
* Enhanced visibility into critical security incidents by eliminating system log noise.
