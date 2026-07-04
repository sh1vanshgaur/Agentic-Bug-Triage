<div align="center">

  <h1>🚀 Agentic Bug Triage & Routing System</h1>

  <p>
    <b>An autonomous, multi-agent AI pipeline that intelligently enriches, correlates, and synthesizes software bugs across disconnected enterprise tracking systems — in real time.</b>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white" />
    <img src="https://img.shields.io/badge/FastAPI-0.111-009688?logo=fastapi&logoColor=white" />
    <img src="https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=black" />
    <img src="https://img.shields.io/badge/LLM-Llama%203.3%2070B-blueviolet?logo=meta" />
    <img src="https://img.shields.io/badge/Kafka-Event--Driven-231F20?logo=apachekafka&logoColor=white" />
    <img src="https://img.shields.io/badge/Redis-Caching-DC382D?logo=redis&logoColor=white" />
    <img src="https://img.shields.io/badge/PostgreSQL-Database-336791?logo=postgresql&logoColor=white" />
    <img src="https://img.shields.io/badge/Docker-Compose-2496ED?logo=docker&logoColor=white" />
    <img src="https://img.shields.io/badge/License-MIT-green" />
  </p>

</div>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [⚡ Quick Links to Key Deliverables](#-quick-links-to-key-deliverables)
- [Project Directory Structure](#-project-directory-structure)
- [📌 Special Mention: Reference Links & Core Documents](#-special-mention-reference-links--core-documents)
- [The Problem We Solve](#-the-problem-we-solve)
- [Key Features](#-key-features)
- [Team Contributions](#-team-contributions)
- [License](#-license)

---

## 📖 Overview

In modern enterprise environments, bug reports are fragmented across multiple disconnected tracking systems — JIRA, GitHub Issues, and Bugzilla. Engineers must manually search each system, gather context, identify related tickets, and form a triage decision entirely from memory and institutional knowledge.

The **Agentic Bug Triage & Routing System** eliminates this manual overhead. It is a unified AI intelligence layer that accepts a bug ticket, runs it through a four-stage autonomous agent pipeline, and streams structured triage results — including root cause, severity, cross-system duplicates, and recommended actions — directly to the engineer's dashboard in real time.

---

## ⚡ Quick Links to Key Deliverables

| Deliverable | Formats / Paths |
| :--- | :--- |
| **Software Design Document (SDD)** | 📄 [PDF (docs/)](docs/Software%20Design%20Document.pdf) \| 📁 [PDF (demo/)](Final%20Demo%20CPP%203/Software%20Design%20Document.pdf) |
| **User Manual** | 📄 [PDF (docs/)](docs/Agentic_Bug_Triage_Routing_System_User_Manual.pdf) \| 📁 [PDF (demo/)](Final%20Demo%20CPP%203/Agentic_Bug_Triage_Routing_System_User_Manual.pdf) |
| **Final Presentation (PPT)** | 📊 [PPTX (ppts/)](ppts/HPE%20CPP%203%20Final%20Presentation-%20Agentic%20Bug%20Triage%20and%20Routing.pptx) \| 📁 [PPTX (demo/)](Final%20Demo%20CPP%203/HPE%20CPP%203%20Final%20Presentation-%20Agentic%20Bug%20Triage%20and%20Routing.pptx) \| 📁 [PDF version](Final%20Demo%20CPP%203/HPE%20CPP%203%20Final%20Presentation-%20Agentic%20Bug%20Triage%20and%20Routing.pdf) |
| **Source Code Repository** | 🌐 [GitHub Remote](https://github.com/pulkitjn3010/agentic-bug-triage-and-routing) \|

---

## 📁 Project Directory Structure

```text
agentic-bug-triage-and-routing/
├── designs/                 # Architectural drawings & sequence flows
│   ├── Sequence Diagrams/   # Flowcharts for cache, context fetch, and AI synthesis
│   ├── HLD_v1.pdf           # High-Level Design document version 1
│   ├── HLD_v2.png           # High-Level Design diagram version 2
│   ├── HLD_v3.png           # High-Level Design diagram version 3
│   ├── POC Architecture.png # Proof of Concept architecture layout
│   └── Reference_...        # Mentor-suggested reference architecture
├── docs/                    # Official documentation and guidelines
│   ├── Software Design Document.pdf
│   ├── Agentic_Bug_Triage_Routing_System_User_Manual.pdf
│   ├── Agentic_Bug_Triage_SOLUTION_PROPOSAL.pdf
│   ├── Team-Contributions.pdf
│   └── problem-statement.md
├── ppts/                    # Slide decks detailing progress and meetings
│   ├── HPE CPP 3 Final Presentation- Agentic Bug Triage and Routing.pptx
│   └── Checkpoint/Meeting presentations
├── ui-mockup/               # Interactive UI mockups
│   ├── Bug_Triage_Mockup_v1.html
│   └── Bug_Triage_Mockup_v2.html
├── meeting-notes/           # Collaboration notes & recording links
└── Final Demo CPP 3/        # Collected assets for the final project delivery
```

---

## 📌 Reference Links & Core Documents

> [!IMPORTANT]
> Below are the core deliverables, source repositories, documentation, and demo recordings for the Agentic Bug Triage and Routing System.

### 🌐 Source Code & Repositories
* **[Source Code Repository](https://github.com/pulkitjn3010/agentic-bug-triage-and-routing)**
  * *Description:* Holds interactive UI mockups, technical documentation, architectural drawings, presentation decks, and collaboration history for the system.
  * *Local Workspace Directory:* [Agentic-Bug-Triage Root Folder](./)

### 📄 System Design & Documentation
* **[Software Design Document (SDD)](docs/Software%20Design%20Document.pdf)**
  * *Description:* Outlines the complete technical blueprints of the system. Includes details on MCP connector architecture, caching strategies, agent orchestration workflows, database models, sequence diagrams, and crash recovery mechanisms.
  * *Alternative Demo Version:* [Final Demo CPP 3/Software Design Document.pdf](Final%20Demo%20CPP%203/Software%20Design%20Document.pdf)
* **[User Manual](docs/Agentic_Bug_Triage_Routing_System_User_Manual.pdf)**
  * *Description:* Step-by-step instructions for end-users and administrators. Explains how to integrate different trackers (Jira, Bugzilla, GitHub), configure tokens/tokens settings, search and filter bugs, and manually manage triage updates.
  * *Alternative Demo Version:* [Final Demo CPP 3/Agentic_Bug_Triage_Routing_System_User_Manual.pdf](Final%20Demo%20CPP%203/Agentic_Bug_Triage_Routing_System_User_Manual.pdf)

### 📊 Project Presentation & Proposal
* **[Final Presentation (PPTX)](ppts/HPE%20CPP%203%20Final%20Presentation-%20Agentic%20Bug%20Triage%20and%20Routing.pptx)**
  * *Description:* A comprehensive PowerPoint deck summarizing the business impact, system requirements, architecture implementation, live-demo highlights, and next steps.
  * *Alternative Demo Version (PPTX):* [Final Demo CPP 3/HPE%20CPP%203%20Final%20Presentation-%20Agentic%20Bug%20Triage%20and%20Routing.pptx](Final%20Demo%20CPP%203/HPE%20CPP%203%20Final%20Presentation-%20Agentic%20Bug%20Triage%20and%20Routing.pptx)
  * *Alternative Demo Version (PDF):* [Final Demo CPP 3/HPE%20CPP%203%20Final%20Presentation-%20Agentic%20Bug%20Triage%20and%20Routing.pdf](Final%20Demo%20CPP%203/HPE%20CPP%203%20Final%20Presentation-%20Agentic%20Bug%20Triage%20and%20Routing.pdf)
* **[Solution Proposal](docs/Agentic_Bug_Triage_SOLUTION_PROPOSAL.pdf)**
  * *Description:* The initial project pitch and proposal outlining the architectural roadmap and anticipated outcomes.

### 🎥 Video Demonstration Recordings
* **[Problem Demonstration Video (YouTube)](https://www.youtube.com/watch?v=gOyspIhLMJc)**
  * *Description:* A visual walkthrough explaining the pain points of fragmented, manual bug triage in a multi-team development setting.
* **[Live System Demo Video (YouTube)](https://www.youtube.com/watch?v=MUy3MSw08wI)**
  * *Description:* A full recorded walkthrough of the active Agentic Bug Triage system dashboard, showcasing real-time synchronization, AI-powered classification suggestions, and routing execution.

### 📅 Meeting & Collaboration History
For complete context on project milestones and meeting details, see:
* **[Meeting Notes Directory](meeting-notes)** (Contains PDFs for Kick-off and Meetings 1 through 4)
* **Recorded Meetings (Google Drive Links):**
  * [Meeting 3 Drive Recording (27.04.2026)](https://drive.google.com/file/d/1M39fdf9TwDDV2AnBrEClDJ930Fp6Zosd/view?usp=sharing)
  * [Meeting 4 Drive Recording (25.05.2026)](https://drive.google.com/file/d/1u1t8y-mYk-S4-9HOQfge-R99Obw_6ru0/view?usp=sharing)
  * [Meeting 5 Drive Recording (17.06.2026)](https://drive.google.com/file/d/1avCuTO0_HbkWnJ-ifgPE4SYa9WMcUUTQ/view?usp=sharing)

---

## 🚨 The Problem We Solve

| Pain Point | Impact |
|---|---|
| **Multi-System Data Fragmentation** | Bug data is spread across JIRA, GitHub, Bugzilla with no unified view |
| **Manual Context Gathering** | Engineers spend hours searching tickets and logs |
| **Missing Cross-System Correlation** | Related bugs across systems are never automatically linked |
| **Scattered Knowledge Repositories** | Runbooks and workarounds remain buried in Confluence |
| **No Actionable Triage Intelligence** | Trackers provide no AI-driven severity, root cause, or fix recommendations |

---

## ✨ Key Features

- **🌐 Unified Bug Dashboard** — Aggregates a near real-time, read-only view of open issues across JIRA (Cloud & On-Prem), GitHub, Bugzilla, and Confluence.
- **🤖 Four-Agent Autonomous Pipeline** — `ContextFetchAgent` → `CrossSystemFetchAgent` + `EnrichmentAgent` (parallel) → `AISynthesisAgent`.
- **⚡ Progressive WebSocket Streaming** — Results are streamed panel-by-panel as each agent completes. Engineers see data within seconds, not minutes.
- **🎯 Structured AI Triage Output** — Generates severity (P0–P3), root-cause hypothesis, confidence score, affected components, and recommended actions.
- **📊 Cross-System Correlation** — Identifies duplicate and semantically related issues across all connected systems using multi-query LLM search and similarity scoring.
- **📚 Knowledge Base Enrichment** — Uses a ReAct (Reason + Act) loop to iteratively search Confluence and surface relevant runbooks and historical fixes.
- **🔌 Dynamic Connector Registry** — New source systems can be added via configuration without touching pipeline logic.
- **🛡️ Fault-Tolerant Architecture** — Kafka-backed event processing with PostgreSQL pipeline checkpointing enables crash recovery mid-triage.

---



## 👥 Team Contributions

### Collaborative Design
The entire system architecture and documentation were designed collaboratively by all team members, including:
- High-Level Design (HLD) & Software Design Document (SDD)
- Agent workflow design & sequence diagrams
- Database schema & connector architecture
- Technology evaluation & design reviews

---

## 📄 License

This project is open for educational and evaluation purposes.
