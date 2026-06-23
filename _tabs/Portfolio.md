---
layout: page
icon: fas fa-id-badge
order: 1
title: Portfolio
---

<div class="portfolio" markdown="1">

## Srivathsan-VKN

**`@Pillow`** · CTF player & security enthusiast
{: .lead }

Entry-level cybersecurity professional with foundational knowledge in SOC operations, SIEM monitoring, log analysis, incident response, and network security. Familiar with Windows and Linux environments, alert triage, threat detection, and basic scripting for automation.

<div class="pf-actions">
  <a class="pf-btn" href="mailto:vknsrivathsancareer@gmail.com"><i class="fas fa-envelope"></i> Email</a>
  <a class="pf-btn" href="https://github.com/Srivathsan-VKN"><i class="fab fa-github"></i> GitHub</a>
  <a class="pf-btn" href="https://www.linkedin.com/in/srivathsan-vkn-315028277"><i class="fab fa-linkedin"></i> LinkedIn</a>
</div>

---

## Projects

<div class="pf-grid">

<div class="card pf-card" markdown="1">
####  AI SOC Alert Triage Assistant 
- Built an end-to-end AI-powered SOC triage pipeline integrating Wazuh SIEM with a local Llama 3.1:8b LLM via Ollama. 
- Implemented grounded prompting + post-LLM validation against offline MITRE ATT&CK + NVD CVE databases to eliminate hallucinated security identifiers. 
- SIEM-agnostic architecture using abstract base classes and ECS-aligned schemas. 
- 70+ tests with pytest + pytest-httpx. Python 3.11+, Pydantic v2, structlog, hatchling. 
<br>**Stack:** 
<br>[<i class="fab fa-github"></i> Repo](https://github.com/Srivathsan-VKN/SOC-PERSONAL-POJECTS)
</div>

<div class="card pf-card" markdown="1">
####  Defensive Network Architecture & Hardening (pfSense/VirtualBox)
- Designed a multi-segmented enterprise network topology utilizing VirtualBox to simulate production-leveltraffic isolation.
- Configured pfSense firewall rules, NAT, and IDS/IPS modules to defend against simulated externalreconnaissance and attacks.
- Utilized Wireshark for deep packet inspection (DPI) to identify protocol anomalies and potential data exfiltration attempts.
<!--br>**Stack:** Splunk, Wireshark, Sysmon, Kali Linux.-->
<!--<br>[<i class="fab fa-github"></i> Repo](https://github.com/USERNAME/project-two)-->
</div>

<div class="card pf-card" markdown="1">
####  Splunk SOC lab project
- Built and tested 5+ security use cases using Splunk.
- Simulated SOC alerts for brute force, lateral movement, and beaconing in Splunk.
<br>**Stack:** Splunk, Wireshark, Sysmon, Kali Linux.
<!--<br>[<i class="fab fa-github"></i> Repo](https://github.com/USERNAME/project-two)-->.
</div>

</div>



---

## Skills

<div class="pf-grid">

<div class="card pf-card" markdown="1">
#### SOC & Security Operations
Alert triage · incident response · log analysis · threat detection · escalation · documentation.
</div>

<div class="card pf-card" markdown="1">
#### Networking
 TCP/IP · DNS · DHCP · HTTP/HTTPS · SMTP · ports · protocols.
</div>

<div class="card pf-card" markdown="1">
#### Endpoint & Network Security
 EDR/XDR · IDS/IPS · firewalls · email security · VPN · proxy
</div>

<div class="card pf-card" markdown="1">
#### Frameworks
 MITRE ATT&CK · NIST · ISO 27001 · CIS.
</div>

<div class="card pf-card" markdown="1">
#### SIEM & Monitoring
Splunk · Wazuh · Microsoft Sentinel.
</div>

<div class="card pf-card" markdown="1">
#### Platforms
 AWS (GuardDuty · CloudTrail · IAM) · Linux (Ubuntu) · Docker · GitHub · VirtualBox
</div>

<div class="card pf-card" markdown="1">
#### Operating Systems
 Windows Event Logs · Linux Syslog · Ubuntu · Windows Server basics.
</div>

<div class="card pf-card" markdown="1">
#### Scripting & Automation
 Python · PowerShell · Bash.
</div>

<div class="card pf-card" markdown="1">
#### Frameworks
 MITRE ATT&CK · NIST · ISO 27001 · CIS.
</div>

<div class="card pf-card" markdown="1">
#### Tools
nmap · Burp Suite · Ghidra · Wireshark · Metasploit · gobuster · John · hashcat · Splunk · Wazuh 
</div>

</div>


## Certifications
- IBM Cyber Security & Forensics Graduate
- TryHackMe Pre-Security Path
- AWS Cloud Practitioner Certificate
  
---

## Contact

Reach me at **[vknsrivathsancareer@gmail.com](mailto:vknsrivathsancareer@gmail.com)** or via the icons below.

<div class="pf-actions">
  <a class="pf-btn" href="https://github.com/Srivathsan-VKN"><i class="fab fa-github"></i> GitHub</a>
  <a class="pf-btn" href="https://www.linkedin.com/in/srivathsan-vkn-315028277"><i class="fab fa-linkedin"></i> LinkedIn</a>
</div>

</div>

<style>
.portfolio .lead { font-size: 1.05rem; opacity: .85; margin-top: -.3rem; }
.portfolio .pf-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 1rem;
  margin: 1rem 0;
}
.portfolio .pf-card { padding: 1rem 1.2rem; }
.portfolio .pf-card h4 { margin-top: 0; }
.portfolio .pf-actions { display: flex; flex-wrap: wrap; gap: .6rem; margin: 1rem 0; }
.portfolio .pf-btn {
  display: inline-flex;
  align-items: center;
  gap: .4rem;
  padding: .4rem .9rem;
  border-radius: 8px;
  border: 1px solid var(--card-border-color, #d8dee4);
  background: var(--card-bg, rgba(127,127,127,.06));
  text-decoration: none;
  font-size: .9rem;
}
.portfolio .pf-btn:hover { background: var(--tag-hover, rgba(127,127,127,.18)); }
</style>