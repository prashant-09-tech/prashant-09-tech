<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:060010,30:0d0019,60:0a1628,100:060010&height=200&section=header&text=Prashant%20Rai&fontSize=68&fontColor=e2d9f3&animation=fadeIn&fontAlignY=45&desc=DFIR%20%C2%B7%20Detection%20Engineering%20%C2%B7%20Agentic%20AI%20%C2%B7%20C%2B%2B%20Systems&descSize=16&descColor=7c6f9f&descAlignY=67"/>

</div>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/prashant-rai0203)&nbsp;
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:prashantkrai765@gmail.com)&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-161b22?style=flat-square&logo=github&logoColor=white)](https://github.com/prashant-09-tech)&nbsp;
[![Views](https://komarev.com/ghpvc/?username=prashant-09-tech&style=flat-square&color=7c3aed&label=profile+views)](https://github.com/prashant-09-tech)

</div>

<br/>

---

## Who I Am

I build **security systems that operate at machine speed** — from kernel-level C++ forensic agents to agentic AI pipelines that autonomously investigate live Windows endpoints.

My work sits at the intersection of **systems engineering**, **digital forensics**, and **applied AI** — engineering platforms used in law enforcement and national security operations at Innefu Labs.

```
Domain expertise:
  ├── Digital Forensics & Incident Response (DFIR)
  ├── Detection Engineering — Sigma, behavioral rules, MITRE ATT&CK
  ├── Agentic AI — Claude, MCP, LLM orchestration, autonomous pipelines
  ├── C++ Systems — Win32, NTAPI, kernel-level, multithreading, low-latency
  ├── Forensic Dataset Engineering — 100K+ events/day → ML threat models
  ├── Memory Forensics — Volatility3, live acquisition, fileless detection
  ├── Threat Intelligence — IOC correlation, CDR/IPDR, behavioral analysis
  └── Security Automation — evidence pipelines, triage automation, reporting
```

**Production numbers:** `94% zero-day detection` &nbsp;|&nbsp; `70% analyst triage reduction` &nbsp;|&nbsp; `100K+ events/day` &nbsp;|&nbsp; `60% faster memory acquisition` &nbsp;|&nbsp; `40% endpoint overhead cut`

---

## Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=cpp,python,tensorflow,qt,django,linux,git,visualstudio,mysql,sqlite,cs,dotnet&theme=dark&perline=12"/>

</div>

<br/>

<div align="center">

**Languages**&emsp;
`C++` `Python` `C#` `SQL` `JavaScript` `PowerShell`

**Agentic AI & ML**&emsp;
`Claude AI` `LLM Orchestration` `MCP Protocol` `NATS` `TensorFlow` `Scikit-learn` `SHAP` `Isolation Forests` `Gradient Boosting` `Random Forest`

**DFIR & Detection**&emsp;
`Memory Forensics` `Disk Forensics` `Volatility3` `Osquery` `Sigma Rules` `MITRE ATT&CK` `Threat Hunting` `Incident Response` `EDR` `Chain of Custody` `Artifact Analysis` `NTFS Forensics` `Winpmem`

**Systems**&emsp;
`Win32 API` `NTAPI` `Windows Internals` `Multithreading` `WinDivert` `MFC` `FFmpeg` `NDI SDK` `TSDuck` `Qt5`

</div>

---

## Projects

<br/>

### `[01]` &nbsp; VAJRA v2 — Agentic DFIR Endpoint Investigation Platform

**The problem:** Endpoint forensic investigation requires a senior analyst to manually connect to systems, run tools, collect artifacts, and correlate evidence — a process that takes hours and doesn't scale.

**The design:** VAJRA v2 replaces that chain with an agentic loop. An analyst types a natural language question. Claude reasons over it, selects the right forensic tools through an MCP server, dispatches commands over NATS pub/sub to a lightweight C++ agent running on the live Windows endpoint, and synthesizes structured DFIR intelligence from the returned artifacts — end to end, without manual intervention.

```
 Question (Web UI)
      │
      ▼
 Python Orchestrator ──── session · routing · state
      │
      ▼
 ┌──────────────────────────────────┐
 │  Claude (Reasoning Engine)       │
 │  · chain-of-thought planning     │
 │  · forensic evidence selection   │
 │  · cross-artifact synthesis      │
 └──────────────┬───────────────────┘
                │
      ▼
 MCP Server ──── tool registry · dispatch · workflow
      │
      ▼
 NATS Message Bus ──── pub/sub · low-latency transport
      │
      ▼
 C++ Agent (Windows Endpoint)
  ├── osquery SQL: processes · network · registry · files
  ├── system health: memory · CPU · loaded modules
  └── live artifact collection
      │
      ▼
 Structured DFIR Report
```

| Layer | Technology | Responsibility |
|:--|:--|:--|
| Reasoning | Claude LLM | Plan · select tools · synthesize findings |
| Orchestration | Python | Session state · routing · response assembly |
| Tool Dispatch | MCP Server | Forensic tool registry · workflow enforcement |
| Transport | NATS | Async pub/sub · sub-millisecond delivery |
| Endpoint | C++ (Win32/NTAPI) | Live telemetry · artifact collection |
| Telemetry | Osquery | SQL queries over live system state |

**Stack:** `C++` `Python` `Claude AI` `MCP` `NATS` `Osquery` `Agentic AI` `Windows Internals` `DFIR` `Incident Response` `Security Automation` `EDR`

---

### `[02]` &nbsp; RapiDFIR — Enterprise Remote DFIR Platform

**The problem:** Enterprise incident response requires on-site forensic teams or slow remote tools that can't scale across hundreds of endpoints simultaneously.

**The design:** RapiDFIR enables remote forensic acquisition from Windows endpoints at scale. Autonomous agentic pipelines coordinate evidence collection, artifact correlation, and threat prioritization without analyst involvement at each step. Deployed at national-security operational scale.

```
 Remote Endpoint (C++ Agent · Win32/NTAPI)
  ├── Disk artifacts: MFT · prefetch · registry · event logs
  ├── Volatile: RAM dump · process list · network connections
  └── System: loaded modules · services · scheduled tasks
      │
      ▼
 Multithreaded Acquisition Engine ──── 40% overhead reduction
      │
      ▼
 JSON Ingestion Pipeline ──── structured artifact normalization
      │
      ▼
 Agentic Correlation Engine ──── autonomous reasoning · scoring
      │
      ▼
 Prioritized Threat Intelligence
```

**Scale:** Multi-endpoint parallel acquisition · E01 / DD / RAM dump format support · National-security operational deployment

**Stack:** `C++` `Python` `Agentic AI` `Win32/NTAPI` `Windows Internals` `DFIR` `Memory Forensics` `Disk Forensics` `Incident Response` `Security Automation` `Threat Intelligence`

---

### `[03]` &nbsp; Threat Intelligence Engine — Forensic ML Pipeline

**The problem:** Signature-based detection misses novel malware. Analyst-driven triage at 100K+ daily events is unsustainable. Security teams need detection that explains its own decisions.

**The design:** An end-to-end forensic dataset engineering pipeline — from raw endpoint telemetry ingestion through feature extraction to stacked ensemble ML — achieving 94% zero-day detection accuracy with full SHAP explainability so analysts can trust and audit every alert.

```
 Endpoint Telemetry (100K+ events/day)
  ├── Process execution: ancestry trees · command lines · hashes
  ├── Network: connections · DNS · TLS fingerprints
  ├── Registry: persistence keys · autorun mutations
  └── File system: creation · modification · deletion events
      │
      ▼
 Feature Engineering
  ├── MACB timestamp sequences
  ├── Process ancestry graph features
  ├── Behavioral sequence encoding
  └── Privilege escalation indicators
      │
      ▼
 Ensemble Models
  ├── Random Forest + Gradient Boosting → classification (94% accuracy)
  └── Isolation Forests → anomaly detection (unauthorized escalations)
      │
      ▼
 Output
  ├── Real-time threat scores per event
  ├── SHAP values → per-alert explainability
  └── 70% analyst triage time reduction
```

**Stack:** `Python` `TensorFlow` `Scikit-learn` `SHAP` `Isolation Forests` `Gradient Boosting` `Detection Engineering` `Threat Intelligence` `Behavioral Analysis` `MITRE ATT&CK` `Anomaly Detection` `Forensic Dataset Engineering`

---

### `[04]` &nbsp; Live RAM Forensics & Memory Acquisition Suite

**The problem:** Conventional memory acquisition requires full crash dumps — slow, high-footprint, and impractical during active incident response.

**The design:** Lightweight C++ acquisition using NTAPI that captures volatile memory without generating crash dumps. 60% faster than full-dump baseline. Integrated with Volatility3 for deep artifact extraction. Detects fileless malware, process injection, LSASS dumping, and process hollowing — threats with zero disk residue.

**Stack:** `C++` `NTAPI` `Windows Internals` `Volatility3` `Winpmem` `Memory Forensics` `Malware Analysis` `Fileless Detection` `DFIR` `Incident Response`

---

### `[05]` &nbsp; Network Tracer & Process Correlation Engine

**The problem:** Traditional network monitoring shows connections but not the process behind them — making C2 detection and lateral movement analysis slow and incomplete.

**The design:** Real-time packet interception via WinDivert with full PID/PPID process tree correlation. Every network event is linked to its originating process, parent hierarchy, and executable path. Under 0.1% packet loss at sustained production-volume traffic. C2 detection via anomalous outbound pattern analysis.

**Stack:** `C++` `WinDivert` `Win32 API` `Python Qt5` `Network Forensics` `Threat Hunting` `C2 Detection` `Incident Response` `Network Security`

---

### `[06]` &nbsp; Cipher Sentinel Imager — Forensic Acquisition

**The problem:** Evidence collected with incorrect procedures or unverified integrity is inadmissible in legal proceedings.

**The design:** Multi-format forensic imaging (E01/RAW/DD) with cryptographic chain-of-custody. SHA-256/MD5/SHA-1 hash verification at acquisition and verification stages. Remote NAS/SAN acquisition for enterprise deployments. Full evidence admissibility in legal proceedings.

**Stack:** `Python` `Qt5` `Cryptography` `Osfmount` `Digital Forensics` `Chain of Custody` `Disk Forensics` `DFIR` `Evidence Acquisition`

---

### `[07]` &nbsp; Sigma CDR/IPDR Threat Intelligence Platform

**The problem:** Investigating communication intelligence requires correlating millions of call records and IP sessions manually — weeks of analyst work with high error rates.

**The design:** Sigma rule engine driving automated detection across CDR/IPDR datasets at scale. Cross-correlation of calls, messages, and IP sessions surfaces hidden relationships. Interactive timeline reconstruction and network graph visualization reduce investigation time from weeks to hours.

**Stack:** `Python` `PySide6` `Sigma Rules` `CDR Analysis` `IPDR Analysis` `Threat Intelligence` `Behavioral Analysis` `Detection Engineering` `Data Correlation`

---

### `[08]` &nbsp; NTFS MFT Forensic Parser

Automated NTFS Master File Table parsing. Recovers deleted files via IsInUse flag analysis. Extracts MACB timestamps for forensic timeline reconstruction. Structured JSON output and HTML reporting for investigation workflows.

**Stack:** `C++` `MFTECmd` `NTFS` `File System Forensics` `Artifact Analysis` `DFIR` `Timeline Analysis`

---

### `[09]` &nbsp; MultiViewer — Real-Time Broadcast Monitoring

High-performance multi-stream video monitoring platform. Simultaneous UDP/RTMP/TCP/HLS/SDI decoding. Under 50ms latency in production. Multithreaded rendering pipeline with frame synchronization built for broadcast-grade reliability.

**Stack:** `C++` `FFmpeg` `TSDuck` `MFC` `Win32 API` `Multithreading` `Real-Time Systems`

---

## Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=prashant-09-tech&show_icons=true&hide_border=true&bg_color=060010&title_color=a78bfa&icon_color=7c3aed&text_color=7c6f9f&include_all_commits=true&count_private=true&rank_icon=github" height="168"/>
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=prashant-09-tech&layout=compact&langs_count=8&hide_border=true&bg_color=060010&title_color=a78bfa&text_color=7c6f9f" height="168"/>

</div>

<div align="center">

<img src="https://streak-stats.demolab.com/?user=prashant-09-tech&hide_border=true&background=060010&ring=7c3aed&fire=a78bfa&currStreakLabel=7c3aed&sideLabels=7c6f9f&dates=7c6f9f&currStreakNum=e2d9f3&sideNums=e2d9f3&stroke=7c3aed" height="152"/>

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=prashant-09-tech&bg_color=060010&color=a78bfa&line=7c3aed&point=a78bfa&area=true&hide_border=true&area_color=0d0019" width="98%"/>

</div>

---

## Trophies

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=prashant-09-tech&theme=darkhub&no-frame=true&no-bg=true&margin-w=8&column=7"/>
</div>

---

## Contribution Snake

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/prashant-09-tech/prashant-09-tech/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/prashant-09-tech/prashant-09-tech/output/github-contribution-grid-snake.svg"/>
  <img alt="contribution snake" src="https://raw.githubusercontent.com/prashant-09-tech/prashant-09-tech/output/github-contribution-grid-snake-dark.svg"/>
</picture>
</div>

---

## Experience

**Innefu Labs Pvt. Ltd.** — Software Engineer &nbsp;·&nbsp; Nov 2024 – Present &nbsp;·&nbsp; New Delhi, India

- Engineered VAJRA v2: agentic DFIR platform using Claude, MCP, NATS pub/sub, and C++ endpoint agent with osquery — eliminating manual analyst triage for endpoint investigations
- Architected RapiDFIR: enterprise remote DFIR platform deployed at national-security operational scale
- Built autonomous LLM orchestration pipelines replacing manual analyst investigation workflows — 70% triage reduction
- Developed Win32/NTAPI kernel-level parsers for deep volatile and persistent Windows artifact extraction
- Designed JSON ingestion pipelines for cross-endpoint forensic artifact normalization and correlation
- Optimized multithreaded acquisition engines — 40% endpoint overhead reduction at sustained throughput

**JTEKT Electronics India Pvt. Ltd.** — Software Engineer &nbsp;·&nbsp; May – Jul 2024 &nbsp;·&nbsp; Gurugram, India

- Engineered industrial PLC design software in C++/MFC for configuration validation, diagnostics, and visualization in safety-critical manufacturing environments

**Planetcast Media Services Ltd.** — Software Engineer &nbsp;·&nbsp; Aug 2021 – Dec 2023 &nbsp;·&nbsp; Noida, India

- Built high-performance C++ and Python systems for broadcast automation at production scale
- Architected multithreaded TCP/UDP communication frameworks for low-latency stream transport
- Integrated FFmpeg, NDI SDK, and TSDuck for real-time video decoding and transport stream analytics
- 25% backend throughput improvement through concurrency tuning and architecture refactoring

**Education:** B.Tech, Computer Science & Engineering — IMS Engineering College, Ghaziabad · 2021

---

## Certifications

| Certification | Issuer | Year |
|:--|:--|:--|
| Advanced Certificate in Data Science — Business Intelligence & Data Analytics | IIIT Bangalore | 2025 |
| SOAR: AI to be Aware — NCVET · Skill India · NSQF Level 2 | Microsoft | 2025 |
| Intro to DFIR: The Divide and Conquer Process | Cyber Triage · Sleuth Kit Labs | 2025 |
| Cybersecurity — Skill India Digital Hub · NSDC | Tech Mahindra Foundation | 2025 |
| Machine Learning with Python | CETPA | — |
| Windows Internals · DFIR · Multithreading & Concurrency · Systems Programming | Specialized Training | — |

---

## Current Research

```python
research = {
    "agentic_forensics"  : "Multi-agent DFIR — memory, planning, autonomous tool orchestration",
    "detection_rules"    : "Sigma rule authoring for behavioral detection on Windows telemetry",
    "dataset_engineering": "Labeled forensic event datasets for zero-day ML training at scale",
    "kernel_forensics"   : "Kernel-mode memory analysis and anti-forensics countermeasures",
    "explainability"     : "SHAP/LIME for interpretable, auditable threat detection models",
}
```

---

<!-- Search optimization: DFIR Engineer Detection Engineer Security Platform Engineer Security Tool Developer Security Automation Engineer Threat Intelligence Engineer Systems Engineer AI Security Engineer Research Engineer Digital Forensics Incident Response Memory Forensics Disk Forensics Endpoint Detection Response EDR Malware Analysis Behavioral Analysis Threat Hunting MITRE ATT&CK Sigma Rules Osquery Volatility3 Windows Internals C++ Python Agentic AI LLM Orchestration MCP NATS Forensic Dataset Engineering Anomaly Detection Zero-Day Detection Network Forensics Artifact Analysis Chain of Custody -->

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:060010,50:0d0019,100:060010&height=110&section=footer&animation=fadeIn"/>
</div>
