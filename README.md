# Hi, I'm Omphulusa Khavhatondwi

<a href="https://www.linkedin.com/in/omphulusa-khavhatondwi-86a907246">
    <img src="https://img.shields.io/badge/-LinkedIn-0072B1?&style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

CompTIA Security+ certified, self-taught SOC analyst. I build hands-on detection and automation labs from scratch, then document the process end to end — from raw logs to a written incident report. Background in Mechanical Engineering (Mechatronics), which is where the systems-level thinking comes from.

**Currently:** working through advanced detection engineering content and expanding my automation lab with additional detection rules.

## What I've built

### 🔍 [Detection Lab](https://github.com/Omphulusak/Detection-Lab)
An end-to-end SOC lab in Vultr Cloud simulating real attacks and engineering detections against them.
- Deployed Elastic Stack, Fleet, and Sysmon to collect and centralize Windows endpoint telemetry
- Simulated adversary activity using Mythic C2 and investigated the resulting alerts in Kibana
- Wrote custom KQL detection rules and mapped findings to the MITRE ATT&CK framework
- Documented the full build and investigation across 11 write-ups

<p align="center">
<img src="https://raw.githubusercontent.com/Omphulusak/Detection-Lab/main/screenshots/detection-lab-architecture.png" width="420"/>
<img src="https://raw.githubusercontent.com/Omphulusak/Detection-Lab/main/screenshots/sysmon-logs-in-elasticsearch.png" width="420"/>
</p>

### ⚙️ [SOC Automation with Wazuh](https://github.com/Omphulusak/SOC-Automation-with-Wazuh)
An automated SOC pipeline connecting detection, enrichment, and case management.
- Deployed Wazuh for log collection and alert generation across a Windows/Linux environment
- Built Shuffle SOAR workflows to automatically enrich alerts with VirusTotal threat intel
- Configured TheHive for case management, routing enriched alerts into actionable cases
- Validated the pipeline end to end using a live Mimikatz credential-dumping detection

<p align="center">
<img src="https://raw.githubusercontent.com/Omphulusak/SOC-Automation-with-Wazuh/main/screenshots/wazuh-dashboard-overview.png" width="420"/>
<img src="https://raw.githubusercontent.com/Omphulusak/SOC-Automation-with-Wazuh/main/screenshots/mimikatz-detection-results.png" width="420"/>
</p>

### 📊 [Splunk SOC Dashboards](https://github.com/Omphulusak/Splunk-SOC-Dashboards)
Two Splunk dashboards built to monitor and investigate security events: SSH brute-force activity against a Linux host, and Windows security events on a small AD-joined environment.
- Built an **SSH activity** dashboard tracking failed/successful login patterns, top attacking IPs, and a geographic map of brute-force attempts
- Built a **Windows events** dashboard tracking privileged logons, new account creation, and firewall rule changes
- Caught a real detection: a privileged account with 22 admin logons that day also created a new local account — a strong indicator of credential misuse or persistence

<p align="center">
<img src="https://raw.githubusercontent.com/Omphulusak/Omphulusak/main/screenshots/dash-overview.jpg" width="420"/>
<img src="https://raw.githubusercontent.com/Omphulusak/Omphulusak/main/screenshots/ssh-activity.jpg" width="420"/>
</p>
<p align="center">
<img src="https://raw.githubusercontent.com/Omphulusak/Omphulusak/main/screenshots/windows-activity.jpg" width="420"/>
</p>

## Tools I've worked with

**Network**
<div>
    <img src="https://img.shields.io/badge/-Wireshark-1679A7?&style=for-the-badge&logo=Wireshark&logoColor=white" />
    <img src="https://img.shields.io/badge/-Suricata-EF3B2D?&style=for-the-badge&logo=Suricata&logoColor=white" />
    <img src="https://img.shields.io/badge/-Zeek-777BB4?&style=for-the-badge&logo=Zeek&logoColor=white" />
</div>

**Endpoint**
<div>
    <img src="https://img.shields.io/badge/-Microsoft_Defender_for_Endpoint-00A4EF?&style=for-the-badge&logo=Microsoft&logoColor=white" />
    <img src="https://img.shields.io/badge/-Velociraptor-4B275F?&style=for-the-badge&logo=Velociraptor&logoColor=white" />
</div>

**SIEM & SOAR**
<div>
    <img src="https://img.shields.io/badge/-Splunk-000000?&style=for-the-badge&logo=Splunk&logoColor=white" />
    <img src="https://img.shields.io/badge/-Elastic-005571?&style=for-the-badge&logo=Elastic&logoColor=white" />
    <img src="https://img.shields.io/badge/-Wazuh-1A73E8?&style=for-the-badge&logo=Wazuh&logoColor=white" />
</div>

## Certifications

- **CompTIA Security+**
  - Issued by CompTIA
  - Verification: [Credly Badge](https://www.credly.com/badges/fa9fdbcb-99f7-4719-b11f-c2874f575584/public_url)

<div>
<img src="https://img.shields.io/badge/-Security%2B-FF0000?&style=for-the-badge&logo=CompTIA&logoColor=white" />
</div>
