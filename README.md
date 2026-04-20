

<div align="center">

```
██████████████████████████████████████████████████████████
█                                                        █
█   [SECURE CONNECTION ESTABLISHED]                      █
█   USER: TIRTHAK GIRISH LIKHAR                          █
█   ROLE: SOC ANALYST — BLUE TEAM                        █
█   STATUS: ACTIVE                                       █
█                                                        █
██████████████████████████████████████████████████████████
```

</div>

<div align="center">

![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=1000&color=00FF41&background=000000&center=true&vCenter=true&width=700&lines=SOC+Analyst+in+the+Making;18-Week+Wazuh+SIEM+Lab+%E2%80%94+9+Simulations+Completed;MITRE+ATT%26CK+%7C+Threat+Detection+%7C+Incident+Response;Currently+Grinding+Security%2B+SY0-701;Blue+Team+%7C+Detection+Engineering+%7C+Compliance)

</div>

---

## 👨‍💻 Who Am I

Hey — I'm **Tirthak Girish Likhar**, a final-year B.Tech Computer Science and Engineering student at **Symbiosis Institute of Technology, Nagpur** (Symbiosis International Deemed University).

I'm building a career in **blue team cybersecurity** with a specific focus on SOC operations, threat detection, and detection engineering. I don't just study security theory — I build labs, run real attack simulations, analyze alerts, and write detection rules. Everything I learn goes into a structured **Obsidian knowledge vault** and gets reinforced with **Anki spaced repetition**.

In early 2026, I attended **Nullcon Goa 2026** — one of India's premier security research conferences — where I attended sessions on AIS spoofing and SCADA attacks on maritime systems, and advanced Windows 11 evasion techniques including memory injection and AMSI bypass. That experience locked in my direction: blue team, SOC operations, and eventually threat intelligence and detection engineering at scale.

I just completed an **18-week industry internship at SS Infotech Pvt. Ltd., Nagpur** where I designed, deployed, and operated a fully functional Simulated SOC environment from the ground up — no pre-built labs, no guided walkthroughs, just real engineering decisions on real tools. The project is documented week-by-week in this repository.

Currently grinding **CompTIA Security+ SY0-701** with a late-May 2026 exam target, using Mike Myers video course, Ian Neil's study guide, and Jason Dion practice tests.


<br>


<p align="center">
  <img src="https://i.pinimg.com/originals/dc/4d/b1/dc4db1c340e223ef56883a33df40e00b.gif" alt="Alt text" width="700"/>
</p>


<br>

## 🧭 Active Learning Path

> Old path: done. New phase: building real depth.

I've moved past the beginner certificate grind. The focus now is on building **genuine technical depth** — strong Linux and networking fundamentals as the base, a structured certification ladder mapped to actual SOC analyst job requirements, and hands-on projects that produce real evidence of capability.

---

### 🏗️ Layer 1 — Foundations (Ongoing, Parallel to Everything)

Before certifications mean anything, the fundamentals have to be solid. I'm actively strengthening two core areas in parallel with everything else:

#### Linux
- File system hierarchy, permissions model, user/group management
- Log analysis — `auth.log`, `syslog`, `journalctl`, `grep` pipelines
- Process management, `systemctl`, service enumeration
- Networking tools — `ip`, `ss`, `netstat`, `tcpdump`
- Bash scripting for automation and log parsing
- Everything I use gets documented in Obsidian with commands, examples, and real context from lab work

#### Networking
- TCP/IP model — how packets actually move, not just what the layers are called
- DNS, HTTP/S, SSH, FTP — protocol-level understanding for traffic analysis
- Subnetting, routing basics, NAT vs Bridged networking (learnt this the hard way in the SOC lab)
- Firewall behaviour — UFW, iptables rules, default-deny policies
- Reading packet captures, understanding what normal vs anomalous traffic looks like

 
---

### 🎯 Layer 2 — CompTIA Security+ SY0-701 ← MAIN FOCUS RIGHT NOW

> **Target exam date: Late May 2026 | Voucher expiry: July 20, 2026 — hard deadline**

Security+ is the primary objective. Everything else is secondary until this is done.


**Domains being covered:**
```
├── General Security Concepts
├── Threats, Vulnerabilities & Mitigations
├── Security Architecture
├── Security Operations          ← heaviest focus (most relevant to SOC work)
└── Security Program Management & Oversight
```

---

### 🔵 Layer 3 — TryHackMe SEC0 + SEC1 (Queued, Running Parallel)

> **Both purchased. Starting alongside Security+ theory where relevant.**

SEC0 and SEC1 are TryHackMe's structured SOC analyst learning paths. I'm using them to reinforce Security+ concepts with hands-on labs — so theory and practical run together rather than sequentially.

| Course | Focus | Status |
|--------|-------|--------|
| **SEC0** | SOC fundamentals, alert triage, log analysis, SIEM basics | 🟡 In progress alongside Security+ |
| **SEC1** | Threat detection, incident response, threat intelligence, detection engineering | 🔵 Queued after SEC0 |

**Why both:** Security+ gives me the theory. SEC0/SEC1 puts me in front of actual SIEM interfaces, real alert queues, and triage workflows. The combination is what closes the gap between knowing concepts and being able to operate.

---

### 🟣 Layer 4 — SAL1: SOC Analyst Level 1 (TryHackMe) ← Post Security+

> **TryHackMe voucher active. Target: after Security+ is cleared.**

SAL1 is TryHackMe's dedicated SOC Analyst certification — built around the actual daily workflow of an L1 analyst. This is where I go after Security+ is done.

**What it covers:**
- Phishing analysis and email triage
- SIEM alert investigation
- Endpoint log analysis
- Network traffic analysis
- Threat intelligence application
- Writing SOC investigation reports

The report-writing component is something I'm specifically focused on — being able to clearly document what happened, what was found, and what was done is as important as the technical detection work itself.

---

### ⚫ Layer 5 — PSAA: Practical SOC Analyst Associate (TCM Security) ← Final Target

> **TCM Security courses owned. This is the destination cert for this phase.**

PSAA is the most hands-on SOC analyst credential in the stack — built by TCM Security around real SOC operations rather than multiple-choice knowledge testing. This is what I'm building toward.

**What it covers:**
- Real SOC environment simulation
- Alert triage and escalation workflows
- Threat hunting fundamentals
- Daily SOC reporting and shift handover documentation
- Incident documentation that would hold up in a real enterprise context

**Why PSAA over alternatives:** It signals to employers that I can sit in an actual SOC seat and perform — not just pass an exam. The combination of Security+ (baseline knowledge) + SAL1 (platform skills) + PSAA (operational practicals) is a complete entry-level SOC analyst credential stack.

---


### 🔨 Upcoming Projects (Building the Portfolio)

> Certifications without evidence are just paper. Projects are what make the difference.

```
IN PLANNING / BUILDING NEXT:

├── 🔵 Expand the SOC Lab
│   ├── Add a Linux endpoint agent (Ubuntu) alongside Windows
│   ├── Simulate lateral movement and C2 traffic
│   └── Build detection coverage for T1021, T1071, T1041 (current gaps)
│
├── 🔵 Detection-as-Code
│   ├── Write Sigma rules for all 9 simulations
│   └── Maintain a personal detection rule library on GitHub
│
├── 🔵 Threat Intelligence Integration
│   ├── Connect MITRE ATT&CK STIX/TAXII feed to Wazuh
│   └── Proactive rule tuning based on live threat data
│
└── 🔵 Cloud Security Foundations (Post-Security+)
    ├── Stéphane Maarek AWS course (owned, queued)
    └── Build a basic cloud security monitoring lab on AWS free tier
```
---

## 🏗️ Flagship Project — 18-Week Simulated SOC Lab

> **"Design and Implementation of a Simulated Security Operations Center (SOC) Environment for Threat Detection and Incident Response"**
> Industry Internship at **SS Infotech Pvt. Ltd., Nagpur** | January 2026 – May 2026
> Under: **Mr. Viraj Patle** (Industry Mentor) | **Dr. Shreyas Hole** (Institute Mentor)

This is the most significant technical project I have completed to date. Over 18 weeks, I built a production-grade SOC monitoring environment entirely from open-source tooling on consumer hardware, executed 9 distinct attack simulations mapped to MITRE ATT&CK, wrote custom detection rules, implemented automated active response, performed compliance assessment, and built a custom security dashboard — all documented in weekly progress reports.

### 🖥️ Lab Architecture

```
╔══════════════════════════════════════════════════════════════════════╗
║           Oracle VirtualBox 7.x — Bridged Adapter Mode              ║
║                  Home Network — 192.168.1.0/24                       ║
╠══════════════════╦═══════════════════════╦═══════════════════════════╣
║   WAZUH SERVER   ║   WINDOWS ENDPOINT    ║       ATTACKER VM         ║
║                  ║                       ║                           ║
║ Ubuntu 24.04 LTS ║ Windows 11 Home       ║ Ubuntu 22.04 LTS          ║
║ 192.168.1.6      ║ 192.168.1.x (DHCP)    ║ 192.168.1.7 (DHCP)        ║
║ (Static/Netplan) ║                       ║                           ║
║ Wazuh v4.7.5     ║ Wazuh Agent v4.7.5    ║ Hydra v9.5                ║
║ ├─ Manager       ║ Agent ID: 002         ║ Nmap 7.94SVN              ║
║ ├─ Indexer       ║ LAPTOP-MS9PL5OA       ║ Medusa v2.2               ║
║ └─ Dashboard     ║ ├─ Security Events    ║                           ║
║                  ║ ├─ FIM (syscheck)     ║ Attack Simulation         ║
║ 6GB RAM / 25GB   ║ ├─ SCA               ║ Platform                  ║
║ Port 1514 (agent)║ ├─ Syscollector       ║                           ║
║ Port 443 (dash)  ║ └─ Rootcheck         ║ 4GB RAM / 20GB            ║
╚══════════════════╩═══════════════════════╩═══════════════════════════╝

Host Machine: Windows 11 | AMD Ryzen 7 6800H | 16GB RAM | 500GB NVMe SSD
```

---

### 📅 18-Week Project Timeline

| Phase | Weeks | What I Did |
|-------|-------|------------|
| **Foundations** | 1–4 | Linux CLI proficiency, filesystem hierarchy, network config tools (ip, ss, netstat), log analysis with grep/journalctl, SOC analyst hierarchy (L1/L2/L3), incident response lifecycle, MITRE ATT&CK Enterprise Matrix deep-dive |
| **SIEM Deployment** | 5–7 | Studied Wazuh's 8 internal daemons, deployed Wazuh v4.7.5 via all-in-one script, resolved RAM and vm.max_map_count issues, switched VirtualBox from NAT to Bridged mode, registered Windows 11 agent, fixed version mismatch and ossec.conf issues |
| **Conference** | 8 | Nullcon Goa 2026 — attended sessions on maritime SCADA attacks and Windows 11 EDR evasion techniques, completed TryHackMe SIEM Fundamentals and Windows Event Logs rooms |
| **Attack Simulations** | 9–13 | EICAR malware detection, failed login detection, FIM validation, SSH brute force with Hydra, custom frequency-based detection rule authoring |
| **Advanced Features** | 14–17 | Automated iptables IP blocking via Active Response, Nmap reconnaissance detection, CIS Windows 11 SCA (32% compliance), custom OpenSearch MITRE ATT&CK dashboard |
| **Final Demo** | 18 | Full consolidation, live demonstration of 5 recorded + 4 referenced simulations, report completion |

---

### ⚔️ All 9 Simulations — Full Detail

<details>
<summary><b>Simulation 1 — EICAR Malware Detection (T1204.002)</b></summary>

**Objective:** Verify that Wazuh can ingest Microsoft Defender AV alerts from a Windows endpoint.

**Method:** Created the EICAR Standard Anti-Virus Test File on the Windows 11 endpoint via PowerShell:
```powershell
echo 'X5O!P%@AP[4\PZX54(P^)7CC)7}$EICAR-STANDARD-ANTIVIRUS-TEST-FILE!$H+H*' `
  > "$env:USERPROFILE\Documents\eicar.txt"
```

**Detection Chain:** EICAR string written → Microsoft Defender detected as `Virus:DOS/EICAR_Test_File` (Severe) → Event ID 1116 generated in Windows Defender Operational log → Wazuh Agent forwarded event → **Rule 87105 (Level 12) triggered**

**MITRE Mapping:** T1204.002 — User Execution: Malicious File
**Result:** ✅ Level 12 Critical alert confirmed in Wazuh Dashboard

</details>

<details>
<summary><b>Simulation 2 — Failed Windows Login Detection (T1078)</b></summary>

**Objective:** Detect repeated failed authentication attempts on the Windows endpoint.

**Method:** Triggered 6 consecutive failed logins on the locked Windows 11 screen (Win+L). Each generated Event ID 4625 with SubStatus 0xC000006A (wrong password).

**Alert Metadata:**

| Field | Value |
|-------|-------|
| Event ID | 4625 — Windows Logon Failure |
| Rule | 60122 (per-attempt) + 18152 (accumulation) |
| Rule Level | 5 (Medium) |
| Logon Type | 2 — Interactive |
| MITRE | T1078 — Valid Accounts |
| Compliance | GDPR, HIPAA, PCI-DSS, NIST 800-53 |

**Result:** ✅ Alert confirmed, 6 separate Rule 60122 events + Rule 18152 accumulation alert

</details>

<details>
<summary><b>Simulation 3 — File Integrity Monitoring (T1565)</b></summary>

**Objective:** Validate real-time FIM detection on a sensitive Windows system directory.

**Method:**
```powershell
New-Item -Path "C:\Windows\System32\drivers\etc\test-wazuh.txt" -ItemType File
```

**Detection:** Wazuh syscheck module detected the new file creation in **real-time mode** (not scheduled scan), capturing MD5 hash, file owner, and full path metadata.

| Field | Value |
|-------|-------|
| Rule | 554 — File added to system |
| Level | 5 (Medium) |
| Detection Mode | realtime |
| MD5 Hash | d41d8cd98f00b204e9800998ecf8427e |
| Compliance | GDPR II 5.1.f, HIPAA 164.312.c.1, PCI-DSS 11.5, NIST SI.7 |

**Result:** ✅ Real-time FIM alert confirmed

</details>

<details>
<summary><b>Simulation 4 — SSH Brute Force via Hydra (T1110)</b></summary>

**Objective:** Simulate a credential brute force attack and validate SIEM-level multi-event correlation.

**Method:** Installed Hydra v9.5 on attacker VM, created 9-entry password wordlist (correct password last):
```bash
hydra -l tirthak -P ~/passwords.txt ssh://192.168.1.6 -t 4 -V
```

**Attack completed in ~7 seconds:** 8 failed attempts + 1 success across 4 parallel threads (ports 46184, 46192, 46198, 46212).

**Wazuh Correlation:**

| Rule | Description | Level |
|------|-------------|-------|
| 5760 | sshd: authentication failed (per-attempt) | 5 |
| **5763** | **sshd: brute force trying to get access** | **10 (High)** |
| 5715 | sshd: authentication success | 3 |

Rule 5763 demonstrates **true SIEM-level multi-event correlation** — Wazuh correlated events across all 4 parallel Hydra threads into a single high-severity incident.

**Compliance Tags:** GDPR IV 35.7.d | HIPAA 164.312.b | PCI-DSS 11.4 | NIST SI.4, AU.14, AC.7
**Result:** ✅ Rule 5763 Level 10 alert confirmed

</details>

<details>
<summary><b>Simulation 5 — Custom Detection Rule 100002 (T1078)</b></summary>

**Objective:** Author and deploy a custom frequency-based correlation rule in Wazuh's local ruleset.

**Rule authored in `/var/ossec/etc/rules/local_rules.xml`:**
```xml
<group name="local,windows,authentication,">
  <rule id="100002" level="10" frequency="5" timeframe="120">
    <if_matched_sid>60122</if_matched_sid>
    <description>Custom Rule: Multiple failed login attempts detected
    on Windows endpoint (Event ID 4625)</description>
    <mitre>
      <id>T1078</id>
    </mitre>
    <group>authentication_failed,windows,</group>
  </rule>
</group>
```

**Logic:** Triggers at Level 10 when 5 or more Rule 60122 events occur within a 120-second window from the same source.

**Test:** Ran `runas /user:FakeUser cmd` six times within two minutes on Windows endpoint.
**Result:** ✅ Rule 100002 Level 10 alert confirmed in dashboard

</details>

<details>
<summary><b>Simulation 6 — Automated Active Response — IP Blocking (T1110)</b></summary>

**Objective:** Implement automated firewall response triggered by brute force detection.

**Configuration added to `ossec.conf`:**
```xml
<active-response>
  <command>firewall-drop</command>
  <location>local</location>
  <rules_id>5763</rules_id>
  <timeout>180</timeout>
</active-response>
```

**Verification:**
```bash
sudo iptables -L INPUT -n | grep 192.168.1
# Output: DROP all -- 192.168.1.7 0.0.0.0/0
```

**Behaviour:** Within seconds of Rule 5763 firing, `wazuh-execd` daemon triggered `firewall-drop`, adding an iptables DROP rule for the attacker IP. Rule automatically removed after 180 seconds. This mirrors enterprise SOAR platform behaviour — pre-approved automated playbook reducing Mean Time to Respond (MTTR).

**Result:** ✅ Automated IP block confirmed via iptables and active-responses.log

</details>

<details>
<summary><b>Simulation 7 — Nmap Port Scan Detection (T1046)</b></summary>

**Objective:** Detect network reconnaissance activity via firewall log analysis.

**Attack:**
```bash
sudo nmap -sT 192.168.1.6
```

Nmap reported port 22/tcp open, 999 filtered. UFW's default-deny policy generated hundreds of BLOCK entries in `/var/log/syslog`.

**Custom Rule 100003 authored:**
```xml
<group name="firewall,">
  <rule id="100003" level="7">
    <if_sid>4151</if_sid>
    <match>UFW BLOCK</match>
    <description>Possible port scan detected via UFW BLOCK entries</description>
    <mitre>
      <id>T1046</id>
    </mitre>
  </rule>
</group>
```

**MITRE Mapping:** T1046 — Network Service Discovery
**Result:** ✅ Rule 100003 Level 7 alert confirmed via syslog evidence

</details>

<details>
<summary><b>Simulation 8 — Security Configuration Assessment (CIS Windows 11)</b></summary>

**Objective:** Assess the Windows 11 endpoint's security posture against the CIS Microsoft Windows 11 Enterprise Benchmark v1.0.0.

**Results:**

| Parameter | Value |
|-----------|-------|
| Policy | CIS Microsoft Windows 11 Enterprise Benchmark v1.0.0 |
| Total Checks | 395 |
| Passed | 127 (32%) |
| Failed | 259 (65%) |
| Not Applicable | 9 (3%) |

**Key Failed Checks (immediately exploitable):**
- No password history enforcement (Check 26000)
- No minimum password length requirement (Check 26003)
- No account lockout threshold — endpoint vulnerable to brute force (Check 26007)
- Password complexity not enforced (Check 26004)

The 32% score is a realistic baseline for a default Windows 11 Home installation. The failed lockout threshold directly correlated with the brute force vulnerability demonstrated in Simulation 4.

**Result:** ✅ SCA scan completed, 32% compliance documented

</details>

<details>
<summary><b>Simulation 9 — Custom OpenSearch Security Dashboard</b></summary>

**Objective:** Build a custom SOC situational awareness dashboard from scratch using live alert data.

**Three visualisations created from `wazuh-alerts-*` index:**

| Panel | Chart Type | Data Field | Key Finding |
|-------|-----------|-----------|-------------|
| Alerts by Rule Level | Vertical Bar | rule.level | 10,800 alerts at Level 5; 780 at Level 10; 25 at Level 12 |
| Top Rules by Description | Pie Chart | rule.description | Top rule: Windows System error events |
| Top MITRE ATT&CK Tactics | Data Table | rule.mitre.tactic | Defense Evasion (1,151) dominated |

**MITRE Tactic Distribution:**
```
Defense Evasion   ████████████████████  1,151 alerts (42.4%)
Impact            ████████              444   alerts (16.4%)
Privilege Esc.    ███████               400   alerts (14.7%)
Initial Access    ███████               359   alerts (13.2%)
Persistence       ███████               359   alerts (13.2%)
```

**Result:** ✅ Dashboard saved as "SOC Lab – Security Overview", 3 panels operational

</details>

---

### 📊 Project Results Summary

```
Total Alerts Generated:     12,605
Simulations Completed:      9  (5 recorded + 4 referenced)
Custom Rules Authored:      2  (Rule 100002 + Rule 100003)
MITRE Techniques Covered:   5  (T1078, T1204.002, T1565, T1110, T1046)
MITRE Tactics Covered:      4  (Initial Access, Credential Access, Execution, Discovery/Impact)
SCA Compliance Score:       32% — CIS Windows 11 Enterprise Benchmark (395 checks)
Active Response:            Automated iptables DROP in <5 seconds, 180s auto-unblock
Compliance Frameworks:      GDPR, HIPAA, PCI-DSS, NIST 800-53
```

---

## 🗺️ Certification Roadmap

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  2026 Q2  ▶  CompTIA Security+ SY0-701
               Resources: Mike Myers | Ian Neil | Jason Dion
               Target: Late May 2026 | Voucher Expiry: July 20, 2026
               Why: Industry baseline. Required for every SOC role.

  2026 Q3  ▶  BTL1 — Blue Team Labs Level 1
               Platform: Security Blue Team
               Why: First hands-on blue team credential.

  2026 Q4  ▶  SAL1 — SOC Analyst Level 1
               Platform: TryHackMe (voucher active)
               Why: Platform-native SOC analyst cert, employer-recognized

  2027 Q1  ▶  SEC0 + SEC1  (TryHackMe bundle — purchased)
               Why: Progressive SOC skills ladder

  2027 Q2  ▶  PSAA — Practical SOC Analyst Associate
               Platform: TCM Security
               Why: Hands-on employer-signal cert

  2027+    ▶  CDSA — Certified Defensive Security Analyst
               Platform: HackTheBox
               Why: Elite-tier blue team credential

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

<br>

## Technical Foundation:
- **Operating Systems:** Linux (Ubuntu), Windows, Kali Linux
- **Networking:** TCP/IP fundamentals, network security protocols
- **Tools:** VirtualBox, cybersecurity tooling
- **Programming:** Python for security automation
- **Lab Environment:** Personal home lab with multiple VMs

<br>

## Next Milestone: 
- CompTIA Security+ certification - (Target 2025)
- Start AWS Cloud Foundations  

<br>

## Background:
Discovered my passion for cybersecurity after exploring various tech domains including full-stack development and AI/ML.
Committed to continuous learning and hands-on practice in both offensive and defensive security domains. Looking to contribute to security-focused projects and connect with the cybersecurity community.

<br>

## 🖥️ Tech Stack

![Git](https://img.shields.io/badge/GIT-E44C30?logo=git&logoColor=white&style=for-the-badge)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white&style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=for-the-badge)
![C](https://img.shields.io/badge/C-00599C?logo=c&logoColor=white&style=for-the-badge)
![C++](https://img.shields.io/badge/C++-004482?logo=c%2B%2B&logoColor=white&style=for-the-badge)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=java&logoColor=white&style=for-the-badge)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?logo=visual-studio-code&logoColor=white&style=for-the-badge)
![Windows](https://img.shields.io/badge/Windows-0078D6?logo=windows&logoColor=white&style=for-the-badge)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black&style=for-the-badge)
![VirtualBox](https://img.shields.io/badge/VirtualBox-183A61?logo=virtualbox&logoColor=white&style=for-the-badge)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?logo=ubuntu&logoColor=white&style=for-the-badge)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?logo=kalilinux&logoColor=white&style=for-the-badge)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?logo=powershell&logoColor=white&style=for-the-badge)
![Bash](https://img.shields.io/badge/Bash_Script-121011?logo=gnubash&logoColor=white&style=for-the-badge)
![Windows Terminal](https://img.shields.io/badge/Windows_Terminal-4D4D4D?style=for-the-badge)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?logo=latex&logoColor=white&style=for-the-badge)



## 🧰 Productivity & Note-Taking

![VS Code](https://img.shields.io/badge/VS_Code-007ACC?logo=visual-studio-code&logoColor=white&style=for-the-badge)
![Markdown](https://img.shields.io/badge/Markdown-000000?logo=markdown&logoColor=white&style=for-the-badge)
![Obsidian](https://img.shields.io/badge/Obsidian-purple?logo=obsidian&logoColor=white&style=for-the-badge)


## 🔐 Security Learning Platforms

![TryHackMe](https://img.shields.io/badge/TryHackMe-6f42c1?logo=tryhackme&logoColor=white&style=for-the-badge)
![TCM Security](https://img.shields.io/badge/TCM_Security-343a40?logo=hackthebox&logoColor=white&style=for-the-badge)
![Coursera](https://img.shields.io/badge/Coursera-0056D2?logo=coursera&logoColor=white&style=for-the-badge)
![CompTIA](https://img.shields.io/badge/CompTIA-ED1C24?logo=comptia&logoColor=white&style=for-the-badge)



## 💡 Personal Learning Journey

![Still Learning](https://img.shields.io/badge/Still_Learning-E67E22?style=for-the-badge)
![Hands-On Labs](https://img.shields.io/badge/Hands--On_Labs-007ec6?style=for-the-badge)
![Road to Cloud Security](https://img.shields.io/badge/Road_to_Cloud_Security-purple?style=for-the-badge)


<br>

# 📊 GitHub Stats:
![Tirthak's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Tirthak10&show_icons=true&theme=dark&hide=prs)
<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=Tirthak10&theme=dark&hide_border=false&include_all_commits=true&count_private=false&layout=compact)

<br>

## 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tirthak-likhar-8808a8255/) 
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:tirthak.likhar.10@gmail.com)


<br>
<!-- Snake Game Repo View -->
<div align="center">

  ![snake gif](https://github.com/Tirthak10/Tirthak10/blob/output/github-snake-dark.svg)

</div>

<br>

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
