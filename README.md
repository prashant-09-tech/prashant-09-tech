<div align="center">

<img src="https://capsule-render.vercel.app/api?type=cylinder&color=0:0d0d0d,40:1a0533,70:0d1b3e,100:0d0d0d&height=220&section=header&text=Prashant%20Rai&fontSize=64&fontColor=ffffff&animation=blinking&fontAlignY=50&desc=Software%20Engineer%20%E2%80%94%20Agentic%20AI%20%C2%B7%20C%2B%2B%20%C2%B7%20Cybersecurity%20%C2%B7%20DFIR&descSize=16&descColor=a371f7&descAlignY=72"/>

</div>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/-prashant--rai0203-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/prashant-rai0203)
[![Email](https://img.shields.io/badge/-prashantkrai765-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:prashantkrai765@gmail.com)
[![GitHub](https://img.shields.io/badge/-prashant--09--tech-161b22?style=for-the-badge&logo=github&logoColor=white)](https://github.com/prashant-09-tech)
[![Visitors](https://komarev.com/ghpvc/?username=prashant-09-tech&style=for-the-badge&color=a371f7&label=VISITORS)](https://github.com/prashant-09-tech)

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=15&duration=2000&pause=800&color=A371F7&center=true&vCenter=true&multiline=true&repeat=true&width=720&height=80&lines=Agentic+AI+%7C+LLM+Orchestration+%7C+Autonomous+Forensic+Systems;C%2B%2B+Systems+%7C+Win32+%7C+NTAPI+%7C+Kernel+Memory+Forensics;Forensic+Dataset+Engineering+%7C+94%25+Zero-Day+Detection" />

</div>

<br/>

<div align="center">

```
╭──────────────────────────────────────────────────────────────────────────────╮
│  4+ YEARS  ·  MISSION-CRITICAL PRODUCTION SYSTEMS  ·  NATIONAL SECURITY      │
│  C++ · Python · Agentic AI · DFIR · Memory Forensics · Dataset Engineering   │
╰──────────────────────────────────────────────────────────────────────────────╯
```

</div>

---

<img align="right" width="310" src="https://raw.githubusercontent.com/abhisheknaiidu/abhisheknaiidu/master/code.gif"/>

## `whoami`

**Systems engineer** with a deep focus on agentic AI, high-performance C++ systems, and digital forensics. I build platforms where AI agents reason autonomously over forensic evidence — combining kernel-level systems programming with LLM orchestration.

Currently at **Innefu Labs** — building enterprise-grade DFIR tools for law enforcement and national security operations.

**What makes my work distinct:**
- Agentic AI pipelines that self-direct investigation without human prompting
- Forensic dataset engineering at 100K+ events/day feeding ML models
- Kernel-level C++ systems — Win32, NTAPI, memory acquisition
- Production impact: **94%** malware detection · **70%** analyst time saved

<br clear="right"/>

---

## `stack --list`

<div align="center">

<img src="https://skillicons.dev/icons?i=cpp,python,tensorflow,qt,django,linux,git,visualstudio,mysql,sqlite,cs,dotnet&theme=dark&perline=12" />

<br/><br/>

**Agentic AI & ML**

![Agentic AI](https://img.shields.io/badge/Agentic_AI-a371f7?style=flat-square)
![LLM Orchestration](https://img.shields.io/badge/LLM_Orchestration-6e40c9?style=flat-square)
![MCP](https://img.shields.io/badge/MCP_Protocol-2d333b?style=flat-square)
![NATS](https://img.shields.io/badge/NATS-27aae1?style=flat-square)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-e63946?style=flat-square)
![Isolation Forests](https://img.shields.io/badge/Isolation_Forests-238636?style=flat-square)

**Systems & Low-Level**

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Win32/NTAPI](https://img.shields.io/badge/Win32_/_NTAPI-0078D4?style=flat-square&logo=windows&logoColor=white)
![Windows Internals](https://img.shields.io/badge/Windows_Internals-0078D4?style=flat-square&logo=windows&logoColor=white)
![Multithreading](https://img.shields.io/badge/Multithreading-6A0DAD?style=flat-square)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white)
![WinDivert](https://img.shields.io/badge/WinDivert-2d333b?style=flat-square)

**DFIR & Forensics**

![Memory Forensics](https://img.shields.io/badge/Memory_Forensics-dc143c?style=flat-square)
![Volatility3](https://img.shields.io/badge/Volatility3-161b22?style=flat-square&logoColor=white)
![Osquery](https://img.shields.io/badge/Osquery-2E86AB?style=flat-square)
![Sigma Rules](https://img.shields.io/badge/Sigma_Rules-FF8C00?style=flat-square)
![NTFS Forensics](https://img.shields.io/badge/NTFS_Forensics-607D8B?style=flat-square)
![DFIR](https://img.shields.io/badge/DFIR-238636?style=flat-square)

</div>

---

## `projects --featured`

<br/>

### ⬡ &nbsp;VAJRA v2 — Agentic DFIR Endpoint Investigation Platform

<div align="center">

> *Natural language in. Forensic intelligence out. No manual evidence collection.*

</div>

An analyst types a question. Claude reasons over it, decides what evidence is needed, instructs an MCP server to dispatch the right tools, which push commands over NATS to a lightweight C++ agent running on the Windows endpoint. The agent executes osquery and system health commands, results flow back through the same chain, and Claude synthesizes a structured DFIR answer.

```
 ┌─────────────────────────────────────────────────────────────────┐
 │  "Which processes established external connections last hour?"   │
 └──────────────────────────┬──────────────────────────────────────┘
                            │
              ┌─────────────▼─────────────┐
              │     Python Orchestrator    │
              └─────────────┬─────────────┘
                            │
              ┌─────────────▼─────────────┐
              │       Claude (LLM)         │  reason · plan · decide
              │   chain-of-thought core    │  select tools · synthesize
              └─────────────┬─────────────┘
                            │
              ┌─────────────▼─────────────┐
              │        MCP Server          │  tool execution layer
              └─────────────┬─────────────┘
                            │
              ┌─────────────▼─────────────┐
              │      NATS Message Bus      │  pub/sub · low-latency
              └─────────────┬─────────────┘
                            │
              ┌─────────────▼─────────────┐
              │     C++ Agent (Windows)    │
              │  osquery · health checks   │  live endpoint telemetry
              │  live artifact collection  │
              └─────────────┬─────────────┘
                            │
              ┌─────────────▼─────────────┐
              │   Structured DFIR Report   │
              └───────────────────────────┘
```

| Component | Technology | Role |
|:---|:---|:---|
| AI Reasoning | **Claude LLM** | Evidence planning · tool selection · answer synthesis |
| Orchestration | **Python** | Session management · request routing |
| Tool Execution | **MCP Server** | Forensic tool dispatch · workflow control |
| Transport | **NATS** | High-speed pub/sub between server and agent |
| Endpoint | **C++ Agent** | Live Windows system — osquery + health commands |
| Telemetry | **Osquery** | SQL queries over processes · network · registry · files |

`C++` `Python` `Claude AI` `MCP` `NATS` `Osquery` `Agentic AI` `Windows Internals`

---

### ⬡ &nbsp;RapiDFIR — Enterprise Agentic DFIR Platform

> Autonomous forensic agents direct remote evidence collection across Windows endpoints, correlate multi-source artifacts through structured JSON pipelines, and surface prioritized threat intelligence — without analyst intervention.

```
 Endpoint ──► C++ Acquisition Engine (Win32/NTAPI)
              disk · memory · registry · network · processes
                           │
                           ▼
              Agentic AI Core — autonomous planning
                           │
                           ▼
              JSON Correlation Engine
              cross-system artifact linkage · threat scoring
                           │
                           ▼
              Intelligence Report
```

| | |
|:---|:---|
| Overhead reduction | **40%** via multithreaded acquisition optimization |
| Evidence formats | RAM dumps · E01 · raw disk images (DD) |
| Scale | National-security-grade operational deployment |

`C++` `Python` `Agentic AI` `Win32/NTAPI` `Windows Internals` `JSON`

---

### ⬡ &nbsp;Threat Intelligence Engine — Forensic Dataset → ML Pipeline

> Forensic dataset engineering pipeline ingesting 100K+ behavioral events per day, feeding stacked ensemble models achieving **94% zero-day detection accuracy** — with full SHAP explainability.

```
 Raw Telemetry (100K+/day)
 processes · network flows · registry mutations
              │
              ▼
 Feature Engineering
 MACB timestamps · process ancestry · behavioral graphs
              │
              ▼
 Ensemble Models
 Random Forest · Gradient Boosting · Isolation Forests
              │
              ▼
 94% accuracy · 70% triage reduction · SHAP interpretability
```

`Python` `TensorFlow` `Scikit-learn` `SHAP` `Isolation Forests` `Dataset Engineering`

---

<details>
<summary>&nbsp;<b>⬡ &nbsp;All Projects</b></summary>

<br/>

| Project | What it does | Stack |
|:---|:---|:---|
| **Live RAM Forensics Suite** | Kernel-level memory acquisition · 60% faster than full-dump · fileless malware detection | `C++` `Volatility3` `NTAPI` |
| **Network Tracer & Process Engine** | WinDivert packet capture → PID/PPID correlation · <0.1% packet loss · C2 detection | `C++` `WinDivert` `Win32` |
| **Cipher Sentinel Imager** | E01/DD/RAW imaging · SHA-256 chain-of-custody · remote NAS/SAN acquisition | `Python` `Qt5` `Cryptography` |
| **Sigma CDR/IPDR Platform** | Rule-driven detection on communication records · timeline & network graph viz | `Python` `PySide6` `Sigma` |
| **NTFS MFT Parser** | Deleted file recovery · MACB timestamps · forensic timeline reconstruction | `C++` `MFTECmd` `JSON` |
| **Windows Prefetch Parser** | Execution history reconstruction · run timeline · web dashboard with export | `Python` `PECmd` `HTML` |
| **MultiViewer Broadcast Platform** | Multi-stream UDP/RTMP/HLS/SDI · <50ms latency · multithreaded rendering | `C++` `FFmpeg` `TSDuck` |
| **KOSTAC PLC Software** | Industrial PLC configuration & validation · safety-critical manufacturing | `C++` `MFC` `Win32` |

</details>

---

## `analytics --show`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=prashant-09-tech&show_icons=true&hide_border=true&bg_color=0d0d0d&title_color=a371f7&icon_color=a371f7&text_color=8b949e&ring_color=a371f7&include_all_commits=true&count_private=true&rank_icon=github" height="165"/>
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=prashant-09-tech&layout=compact&langs_count=8&hide_border=true&bg_color=0d0d0d&title_color=a371f7&text_color=8b949e" height="165"/>

<br/><br/>

<img src="https://streak-stats.demolab.com/?user=prashant-09-tech&hide_border=true&background=0d0d0d&ring=a371f7&fire=a371f7&currStreakLabel=a371f7&sideLabels=8b949e&dates=8b949e&currStreakNum=ffffff&sideNums=ffffff&stroke=a371f7" height="155"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=prashant-09-tech&bg_color=0d0d0d&color=a371f7&line=6e40c9&point=a371f7&area=true&hide_border=true&area_color=1a0533" width="98%"/>

</div>

---

## `trophies --all`

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=prashant-09-tech&theme=darkhub&no-frame=true&no-bg=true&margin-w=6&column=7"/>
</div>

---

## `git log --contributions`

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/prashant-09-tech/prashant-09-tech/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/prashant-09-tech/prashant-09-tech/output/github-contribution-grid-snake.svg"/>
  <img alt="contribution snake" src="https://raw.githubusercontent.com/prashant-09-tech/prashant-09-tech/output/github-contribution-grid-snake-dark.svg"/>
</picture>
</div>

---

## `experience --verbose`

```
┌──────────────────────────────────────────────────────────────────────────────┐
│  Innefu Labs Pvt. Ltd.                Software Engineer      Nov 2024 → Now  │
│  New Delhi, India                                                            │
├──────────────────────────────────────────────────────────────────────────────┤
│  ▸ Built VAJRA v2: agentic DFIR platform — Claude · MCP · NATS · C++ agent  │
│  ▸ Architected RapiDFIR: enterprise forensic platform at security scale      │
│  ▸ Engineered autonomous AI pipelines with LLM-driven evidence collection    │
│  ▸ Built Win32/NTAPI parsers for volatile & persistent artifact visibility   │
│  ▸ Designed JSON pipelines for cross-system forensic correlation             │
│  ▸ Optimized multithreaded engines → 40% endpoint overhead reduction         │
└──────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────────────────────────────────────────────┐
│  JTEKT Electronics India Pvt. Ltd.    Software Engineer      May → Jul 2024  │
│  Gurugram, India                                                             │
├──────────────────────────────────────────────────────────────────────────────┤
│  ▸ Industrial PLC design software — validation, configuration, diagnostics   │
│  ▸ C++ · MFC · Win32 API · SQL-backed systems for manufacturing              │
└──────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────────────────────────────────────────────┐
│  Planetcast Media Services Ltd.       Software Engineer      Aug 2021 → Dec 2023 │
│  Noida, India                                                                │
├──────────────────────────────────────────────────────────────────────────────┤
│  ▸ High-performance C++ & Python systems for broadcast automation            │
│  ▸ Multithreaded TCP/UDP frameworks for low-latency stream transport         │
│  ▸ FFmpeg · NDI SDK · TSDuck — decoding and transport stream analytics       │
│  ▸ 25% backend throughput gain via concurrency tuning & architecture work    │
└──────────────────────────────────────────────────────────────────────────────┘

  🎓  B.Tech — Computer Science & Engineering
      IMS Engineering College, Ghaziabad · 2021
```

---

## `certifications --list`

<div align="center">

<table border="0" cellpadding="12">
<tr>
<td align="center">
<img src="https://img.shields.io/badge/IIIT_BANGALORE-003087?style=for-the-badge&logo=academia&logoColor=white" /><br/><br/>
<strong>Advanced Certificate</strong><br/>
<strong>in Data Science</strong><br/>
<sub>BI & Data Analytics · Feb 18, 2025</sub>
</td>
<td align="center">
<img src="https://img.shields.io/badge/MICROSOFT-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" /><br/><br/>
<strong>SOAR: AI to be Aware</strong><br/>
<sub>NCVET · Skill India · NSQF L2</sub><br/>
<sub>Jun 09, 2025 · 20 hrs</sub>
</td>
<td align="center">
<img src="https://img.shields.io/badge/TECH_MAHINDRA-E4002B?style=for-the-badge&logoColor=white" /><br/><br/>
<strong>Cybersecurity</strong><br/>
<sub>Skill India Digital Hub · NSDC</sub><br/>
<sub>Aug 19, 2025 · 10 hrs</sub>
</td>
<td align="center">
<img src="https://img.shields.io/badge/CYBER_TRIAGE-1a0533?style=for-the-badge&logoColor=a371f7" /><br/><br/>
<strong>Intro to DFIR</strong><br/>
<strong>Divide & Conquer</strong><br/>
<sub>Sleuth Kit Labs · 2025 · 3 hrs</sub>
</td>
</tr>
<tr>
<td align="center">
<img src="https://img.shields.io/badge/CETPA-FF6B35?style=for-the-badge&logoColor=white" /><br/><br/>
<strong>ML with Python</strong><br/>
<sub>Supervised & Unsupervised</sub>
</td>
<td align="center" colspan="3">
<img src="https://img.shields.io/badge/SPECIALIZED_TRAINING-6A0DAD?style=for-the-badge&logoColor=white" /><br/><br/>
<strong>Windows Internals &nbsp;·&nbsp; DFIR &nbsp;·&nbsp; Multithreading</strong><br/>
<strong>Concurrency &nbsp;·&nbsp; Systems Programming</strong>
</td>
</tr>
</table>

</div>

---

## `research --active`

```python
{
  "agentic_systems" : "Multi-agent forensic frameworks — memory, planning, tool-use",
  "dataset_curation": "Large-scale labeled forensic datasets for zero-day ML training",
  "kernel_forensics" : "Kernel-mode memory analysis & anti-forensics detection",
  "explainability"  : "SHAP/LIME interpretable threat models for high-stakes decisions",
}
```

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0d0d,50:1a0533,100:0d0d0d&height=130&section=footer&animation=fadeIn"/>

</div>
