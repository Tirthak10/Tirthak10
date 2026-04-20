

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
