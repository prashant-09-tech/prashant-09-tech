<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0e1a,30:0d1b3e,60:1a1a4e,100:0a192f&height=250&section=header&text=Prashant%20Rai&fontSize=72&fontColor=58a6ff&animation=fadeIn&fontAlignY=40&desc=Systems%20Engineer%20%E2%80%A2%20Agentic%20AI%20%E2%80%A2%20Cybersecurity%20%E2%80%A2%20C%2B%2B%20%E2%80%A2%20Python&descSize=18&descColor=8b949e&descAlignY=60" />

</div>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&duration=2000&pause=800&color=58A6FF&center=true&vCenter=true&width=900&lines=Architecting+Agentic+AI+systems+that+reason%2C+plan+%26+act+autonomously;Engineering+forensic+datasets+powering+94%25-accurate+threat+detection;High-performance+C%2B%2B+%7C+Windows+Internals+%7C+NTAPI+%7C+Low-latency+systems;Memory+forensics+%7C+DFIR+%7C+National-security-grade+platforms;100%2C000%2B+forensic+events%2Fday+%E2%80%94+zero-day+detection+at+machine+speed" />

</div>

<br/>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-prashant--rai0203-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/prashant-rai0203)&nbsp;
[![Email](https://img.shields.io/badge/Email-prashantkrai765%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:prashantkrai765@gmail.com)&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-prashant--09--tech-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/prashant-09-tech)&nbsp;
![Profile Views](https://komarev.com/ghpvc/?username=prashant-09-tech&style=flat-square&color=58a6ff&label=Profile+Views)

</div>

---

## `$ ./prashant --summary`

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                                                                             │
│   Role      Software Engineer                                               │
│   Company   Innefu Labs Pvt. Ltd. — New Delhi, India                        │
│   Focus     Agentic AI · C++ Systems · DFIR · Forensic Datasets             │
│   Stack     C++ · Python · TensorFlow · Win32/NTAPI · Qt5 · Volatility3     │
│   Domain    National Security · Law Enforcement · Threat Intelligence       │
│                                                                             │
│   ▸ 4+ years building mission-critical production systems                   │
│   ▸ Architected DFIR platforms deployed at national-security level          │
│   ▸ Built agentic AI pipelines with autonomous investigation logic          │
│   ▸ Engineered forensic datasets driving 94% zero-day detection             │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

## 🤖 Agentic AI & Autonomous Systems

> *My primary research and engineering focus: building AI systems that don't just respond — they reason, plan, and act.*

**What I build:**
- Autonomous investigation agents that self-direct forensic collection, decide what to analyze next, and synthesize findings without human prompting
- LLM orchestration layers with tool-use, memory, and multi-step planning — integrated into production DFIR workflows
- Agent pipelines that ingest 100K+ forensic signals/day, reason over them, and surface prioritized threat intelligence

**Why it matters:**
Traditional DFIR requires a senior analyst to manually chain together evidence. My agentic systems replace that chain with an autonomous reasoning loop — cutting triage time by **70%** while improving detection accuracy to **94%**.

```python
# The architecture I'm building
class ForensicAgent:
    def __init__(self):
        self.memory    = VectorStore(forensic_artifacts)
        self.tools     = [DiskAcquisition, MemoryCapture, 
                          NetworkTracer, RegistryParser, MFTAnalyzer]
        self.reasoning = LLM(model="chain-of-thought", domain="DFIR")
    
    def investigate(self, endpoint: str) -> ThreatReport:
        plan     = self.reasoning.plan(goal="identify threat on " + endpoint)
        evidence = self.execute_tools(plan.steps)     # autonomous tool use
        findings = self.reasoning.synthesize(evidence) # cross-artifact reasoning
        return ThreatReport(findings, confidence=0.94)
```

---

## 📊 Forensic Dataset Engineering

> *Most ML systems fail in cybersecurity because the data is wrong. I fix the data.*

**Pipeline Architecture:**

```
Raw System Telemetry
        │
        ▼
┌──────────────────┐    ┌──────────────────┐    ┌──────────────────┐
│  Process Events  │    │  Network Flows   │    │  Registry Deltas │
│  (100K+/day)     │    │  TCP/UDP/DNS     │    │  HKLM/HKCU keys  │
└────────┬─────────┘    └────────┬─────────┘    └────────┬─────────┘
         └─────────────────┬──────────────────────────────┘
                           ▼
              ┌────────────────────────┐
              │  Feature Extraction    │
              │  MACB timestamps       │
              │  Process ancestry      │
              │  Behavioral sequences  │
              └────────────┬───────────┘
                           ▼
              ┌────────────────────────┐
              │  Ensemble ML Models    │
              │  Random Forest         │
              │  Gradient Boosting     │
              │  Isolation Forest      │
              └────────────┬───────────┘
                           ▼
              ┌────────────────────────┐
              │  94% Zero-Day Accuracy │
              │  SHAP Explainability   │
              │  Real-time Scoring     │
              └────────────────────────┘
```

---

## ⚡ Technical Stack

<div align="center">

**Core Languages**

![C++](https://img.shields.io/badge/C%2B%2B-Expert-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-Expert-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-Proficient-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Advanced-336791?style=for-the-badge&logo=postgresql&logoColor=white)

**Agentic AI · ML · Data**

![LLM Orchestration](https://img.shields.io/badge/LLM%20Orchestration-412991?style=for-the-badge&logo=openai&logoColor=white)
![Agentic Pipelines](https://img.shields.io/badge/Agentic%20AI%20Pipelines-0066FF?style=for-the-badge)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP%20Explainability-E63946?style=for-the-badge)

**Systems · Low-Level**

![Windows Internals](https://img.shields.io/badge/Windows%20Internals-0078D4?style=for-the-badge&logo=windows&logoColor=white)
![Win32 API](https://img.shields.io/badge/Win32%2FNTAPI-0078D4?style=for-the-badge&logo=windows)
![Multithreading](https://img.shields.io/badge/Multithreading%20%26%20Concurrency-6A0DAD?style=for-the-badge)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white)
![Qt5](https://img.shields.io/badge/Qt5-41CD52?style=for-the-badge&logo=qt&logoColor=white)

**Cybersecurity · DFIR**

![Memory Forensics](https://img.shields.io/badge/Memory%20Forensics-DC143C?style=for-the-badge)
![Volatility3](https://img.shields.io/badge/Volatility3-1C1C2E?style=for-the-badge)
![Sigma Rules](https://img.shields.io/badge/Sigma%20Rules-FF8C00?style=for-the-badge)
![DFIR](https://img.shields.io/badge/DFIR-00C853?style=for-the-badge)
![NTFS Analysis](https://img.shields.io/badge/NTFS%20Forensics-607D8B?style=for-the-badge)

</div>

---

## 🔬 Flagship Projects

### 1 · RapiDFIR — Agentic DFIR Platform
*Enterprise forensic investigation platform with autonomous AI-driven workflows*

Built at **Innefu Labs** for national security and law enforcement clients. RapiDFIR replaces the manual chain of analyst judgment with an agentic AI system that autonomously directs evidence collection, correlates artifacts across systems, and generates prioritized threat intelligence.

| Capability | Detail |
|:---|:---|
| **Agentic Core** | Self-directing investigation agents that plan, collect, and synthesize |
| **Acquisition** | Remote endpoint: disk · memory · registry · processes · network state |
| **Performance** | 40% endpoint overhead reduction via optimized multithreaded engines |
| **Evidence** | RAM dumps · E01 · DD — full forensic format support |
| **Correlation** | JSON ingestion pipelines for cross-system artifact linkage |

`C++` `Python` `Agentic AI` `Win32/NTAPI` `Windows Internals` `JSON Pipelines`

---

### 2 · Threat Intelligence Engine — ML at Forensic Scale
*Forensic dataset pipeline + ensemble ML achieving 94% zero-day detection*

Engineered end-to-end: from raw telemetry ingestion to model training to real-time scoring. The forensic dataset pipeline is the core innovation — processing 100K+ behavioral events daily from process execution, network connections, and registry mutations into labeled training data that powers detection models far beyond signature-based tools.

| Metric | Result |
|:---|:---|
| **Zero-day detection accuracy** | **94%** (ensemble: RF + Gradient Boosting) |
| **Analyst triage time reduction** | **70%** |
| **Events processed daily** | **100,000+** |
| **Anomaly detection** | Isolation Forests for privilege escalations & process injection |
| **Explainability** | SHAP values — every alert is interpretable by analysts |

`Python` `TensorFlow` `Scikit-learn` `SHAP` `Isolation Forests` `Dataset Engineering`

---

### 3 · Live RAM Acquisition & Memory Forensics Suite
*Kernel-level memory capture — 60% faster than full-dump methods*

A lightweight C++ tool that acquires volatile memory without generating crash dumps, preserving system state for forensic analysis. Integrated with Volatility3 for deep artifact extraction — detecting fileless malware, injected code, and hidden processes that leave zero disk traces.

`C++` `Windows Internals` `NTAPI` `Volatility3` `Winpmem` `Memory Analysis`

---

### 4 · Network Tracer & Process Correlation Engine
*Real-time traffic capture mapped to originating system processes — C2 detection*

```
Intercepted Packet → WinDivert → PID/PPID Lookup → Process Tree → Threat Score
     < 0.1% packet loss under sustained production-volume traffic
```

`C++` `WinDivert` `Win32 API` `Python Qt5` `Network Observability`

---

### 5 · Cipher Sentinel Imager
*Forensic acquisition with cryptographic chain-of-custody for legal proceedings*

Multi-format disk imaging (E01/RAW/DD), block-level cloning, RAM capture, SHA-256/MD5/SHA-1 hash verification — remote NAS/SAN acquisition for enterprise-scale investigations.

`Python` `Qt5` `Cryptography` `Osfmount`

---

### 6 · Sigma-Based CDR/IPDR Intelligence Platform
*Large-scale communication data analysis for intelligence operations*

Sigma rule-driven detection across Call Detail Records and IP Detail Records at scale. Cross-correlation of calls, messages, and IP sessions. Interactive timeline reconstruction and network graph visualization for investigative teams.

`Python` `PySide6` `Sigma Rules` `Large-Scale Data` `Threat Intelligence`

---

### 7 · NTFS MFT Forensic Parser
*Deep file system artifact analysis — deleted file recovery & timeline reconstruction*

Automated MFT parsing, MACB timestamp extraction, deleted file detection via IsInUse flag, structured JSON output and HTML reports for forensic workflows.

`C++` `MFTECmd` `NTFS` `JSON` `Timeline Forensics`

---

### 8 · MultiViewer — Broadcast Monitoring Platform
*Real-time multi-stream video system · < 50ms latency in production*

Simultaneous UDP/RTMP/TCP/HLS/SDI stream decoding. Multithreaded rendering pipeline with frame synchronization. Built for broadcast-grade reliability using FFmpeg and TSDuck.

`C++` `FFmpeg` `TSDuck` `MFC` `Win32 API`

---

## 📈 GitHub Analytics

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=prashant-09-tech&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&hide_border=true&title_color=58a6ff&icon_color=58a6ff&text_color=8b949e&bg_color=0d1117"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=prashant-09-tech&layout=compact&langs_count=8&theme=github_dark&hide_border=true&title_color=58a6ff&text_color=8b949e&bg_color=0d1117"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com/?user=prashant-09-tech&theme=github-dark-blue&hide_border=true&background=0d1117&ring=58a6ff&fire=ff6b6b&currStreakLabel=58a6ff&sideLabels=8b949e&dates=8b949e)](https://git.io/streak-stats)

</div>

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=prashant-09-tech&bg_color=0d1117&color=58a6ff&line=58a6ff&point=ffffff&area=true&hide_border=true&area_color=0d2137)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## 🏆 Recognition

<div align="center">

[![trophy](https://github-profile-trophy.vercel.app/?username=prashant-09-tech&theme=algolia&no-frame=true&no-bg=true&margin-w=8&column=7)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## 🐍 Contribution Graph

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/prashant-09-tech/prashant-09-tech/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/prashant-09-tech/prashant-09-tech/output/github-contribution-grid-snake.svg" />
  <img alt="contribution-snake" src="https://raw.githubusercontent.com/prashant-09-tech/prashant-09-tech/output/github-contribution-grid-snake-dark.svg" />
</picture>

</div>

---

## 💼 Experience

```
Innefu Labs Pvt. Ltd.          Software Engineer          Nov 2024 → Present
New Delhi, India
  ├─ Architected RapiDFIR: enterprise DFIR platform for national security clients
  ├─ Built agentic AI investigation pipelines with autonomous evidence collection
  ├─ Engineered Win Internals-based parsers for volatile & persistent artifacts
  ├─ Designed JSON ingestion pipelines for cross-system artifact correlation
  └─ Optimized multithreaded engines → 40% endpoint overhead reduction

JTEKT Electronics India Pvt. Ltd.  Software Engineer      May 2024 → Jul 2024
Gurugram, India
  ├─ Built PLC design software: validation, diagnostics, configuration
  └─ C++ · MFC · Win32 API · SQL-backed configuration systems

Planetcast Media Services Ltd.    Software Engineer        Aug 2021 → Dec 2023
Noida, India
  ├─ High-performance C++ & Python systems for broadcast automation
  ├─ Multithreaded TCP/UDP frameworks for low-latency stream transport
  ├─ Integrated FFmpeg · NDI SDK · TSDuck for stream analytics
  └─ 25% backend throughput improvement via architecture refactoring

Education
  └─ B.Tech Computer Science & Engineering — IMS Engineering College, 2021
```

---

## 🎓 Certifications

```
▸ Advanced Certificate in Data Science        IIIT Bangalore
▸ Machine Learning with Python                CETPA
▸ Windows Internals                           Specialized Training
▸ Digital Forensics & Incident Response       Specialized Training
▸ Multithreading, Concurrency & Systems       Specialized Training
```

---

## 🔭 Active Research

```python
research = {
    "agentic_ai"   : "LLM-powered agents with tool-use for autonomous forensic reasoning",
    "datasets"     : "Curating large-scale labeled forensic datasets for zero-day ML",
    "kernel"       : "Kernel-level memory analysis & anti-forensics detection techniques",
    "explainability": "SHAP/LIME-based interpretable models for high-stakes security decisions"
}
```

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a192f,50:0d1b3e,100:0a0e1a&height=130&section=footer&animation=fadeIn" />

</div>
