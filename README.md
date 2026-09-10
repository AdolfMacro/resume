# MANI KAMRAN

### `PYTHON` · `AUTOMATION` · `SYSTEMS` · `NETWORKING` · `SECURITY`

**Independent Developer · Systems Builder · Technical Explorer**

---

<div align="center">

# MACROPINIX

### An independent engineering space for building, testing and understanding real systems.

**Questions → Experiments → Software → Evidence → Understanding**

[ GitHub ] · [ LinkedIn ] · [ Email ]

</div>

---

> **Programming is the process through which understanding becomes something real.**

Macropinix is where I turn technical questions into working software.

I build tools around problems that interest me — from Python automation and data collection to Linux systems, network analysis, desktop applications and security experiments.

I don't start with a roadmap.

I start with a question.

Then I build something that can answer it.

---

## `01` — IF YOU ONLY READ ONE THING

### I build practical software around real technical problems.

My strongest area is **Python**, especially when it is used to automate work, process data, build tools, or connect different parts of a system.

Around Python, I work with:

```text
Python
  ├── Automation
  ├── Scraping & Data Processing
  ├── Tooling
  ├── Desktop Applications
  └── System Utilities

Linux
  ├── Processes
  ├── CLI
  ├── Permissions
  └── System Behavior

Networking
  ├── TCP/IP
  ├── Packet Capture
  ├── Discovery
  └── Traffic Analysis

Security
  ├── Security Tooling
  ├── Network Security
  ├── Binary Data
  └── Experimental Systems
```

The important part is not the list.

**The important part is the evidence.**

---

# `02` — MACROPINIX AT A GLANCE

<div align="center">

|                |                                                 |
| -------------- | ----------------------------------------------- |
| **BUILD**      | Turn questions into working systems             |
| **OBSERVE**    | Make behavior visible and measurable            |
| **UNDERSTAND** | Study what the system is actually doing         |
| **REFINE**     | Improve architecture, reliability and usability |

</div>

### My working loop

```text
        QUESTION
           │
           ▼
      EXPERIMENT
           │
           ▼
        BUILD
           │
           ▼
       OBSERVE
           │
           ▼
      UNDERSTAND
           │
           ▼
        REFINE
           │
           └──────────────► NEXT QUESTION
```

This loop is the common thread across my projects.

---

# `03` — TECHNICAL LANDSCAPE

```text
                         ┌───────────────────┐
                         │      PYTHON       │
                         │ Automation / Data │
                         │ Tooling / Apps    │
                         └─────────┬─────────┘
                                   │
                 ┌─────────────────┼─────────────────┐
                 │                 │                 │
                 ▼                 ▼                 ▼
          ┌────────────┐    ┌────────────┐    ┌────────────┐
          │   LINUX    │    │ NETWORKING │    │  SECURITY  │
          │ Processes  │    │ TCP/IP     │    │ Tooling    │
          │ CLI / Sys  │    │ Scapy      │    │ Analysis   │
          └──────┬─────┘    └──────┬─────┘    └──────┬─────┘
                 │                 │                 │
                 └─────────────────┼─────────────────┘
                                   ▼
                         ┌───────────────────┐
                         │     SYSTEMS       │
                         │ Build / Observe   │
                         │ Analyze / Refine  │
                         └───────────────────┘
```

---

# `04` — EVIDENCE

## `01` EYE Network Vision

### Modular Network Visibility & Analysis Platform

**Python · Scapy · PyQt6 · Linux · psutil · Matplotlib**

[Repository →](https://github.com/AdolfMacro/EYEnv)

---

### What it does

EYE Network Vision is a modular network visibility system designed to make local network behavior observable.

It combines interface discovery, network segmentation, packet capture, node discovery, traffic classification and visualization into a single application.

### Capabilities

`INTERFACE DISCOVERY`
`NETWORK SEGMENTATION`
`ARP DISCOVERY`
`PASSIVE NODE DISCOVERY`
`PACKET CAPTURE`
`TRAFFIC ANALYSIS`
`FLOW MODELING`
`CSV / TXT REPORTING`
`CLI`
`PyQt6 GUI`

### Architecture

```text
┌───────────────┐
│ Network       │
│ Interfaces    │
└───────┬───────┘
        ▼
┌───────────────┐
│ Interface &   │
│ Segment        │
│ Discovery      │
└───────┬───────┘
        ▼
┌───────────────┐
│ Capture /     │
│ Discovery     │
└───────┬───────┘
        ▼
┌───────────────┐
│ Traffic       │
│ Classification│
└───────┬───────┘
        ▼
┌───────────────┐
│ Nodes / Flows │
│ / Analysis    │
└───────┬───────┘
        ▼
┌───────────────┐
│ Reports / GUI │
└───────────────┘
```

### Why it matters

This project demonstrates the ability to move from low-level network information to a usable application layer:

**network → capture → model → analysis → visualization**

---

## `02` EYE Master

### Modular Business & POI Discovery Framework

**Python · PyQt5 · SQLite · HTTP · Multi-Provider Architecture**

[Repository →](https://github.com/AdolfMacro/EYE-scrapper-master)

---

### From scraping to a data pipeline

EYE Master started as a scraping project and evolved into a modular discovery framework.

Its central rule is simple:

> **No Coordinates = No Record**

A result is not considered useful merely because a provider returned it.

It must pass validation before entering the database.

### Pipeline

```text
                    ┌──────────────┐
                    │     GUI      │
                    └──────┬───────┘
                           ▼
                    ┌──────────────┐
                    │ GUIController│
                    └──────┬───────┘
                           ▼
                    ┌──────────────┐
                    │    Master    │
                    │ ProcessManager│
                    └──────┬───────┘
                           ▼
                    ┌──────────────┐
                    │ScraperProcess│
                    └──────┬───────┘
                           ▼
                    ┌──────────────┐
                    │ ScraperWorker│
                    └──────┬───────┘
                           ▼
                    ┌──────────────┐
                    │ ScraperEngine│
                    └──────┬───────┘
                           ▼
             ┌─────────────┼─────────────┐
             ▼             ▼             ▼
        ┌────────┐   ┌──────────┐   ┌────────┐
        │Provider│   │Provider  │   │Provider│
        │   A    │   │    B     │   │   C    │
        └────┬───┘   └────┬─────┘   └───┬────┘
             └─────────────┼─────────────┘
                           ▼
                    ┌──────────────┐
                    │ Raw Results  │
                    └──────┬───────┘
                           ▼
                    ┌──────────────┐
                    │ Validation   │
                    └──────┬───────┘
                           ▼
                 ┌─────────┴─────────┐
                 ▼                   ▼
          ┌─────────────┐     ┌─────────────┐
          │ Valid Record│     │   Discard   │
          └──────┬──────┘     └─────────────┘
                 ▼
          ┌─────────────┐
          │   SQLite    │
          └─────────────┘
```

### Provider-oriented design

The architecture allows different data sources to participate in the same pipeline while keeping provider-specific logic separated from processing and validation.

Current project work includes providers such as:

`GOOGLE` · `DUCKDUCKGO` · `OPENSTREETMAP` · `BALAD`

The system also includes Persian category-driven discovery and structured storage.

### What this project demonstrates

* Modular architecture
* Data extraction
* Provider abstraction
* Validation pipelines
* Structured storage
* GUI-driven workflows
* Separation of responsibilities
* Designing software for extension

---

# `03` EYE-scrapper

### The Smaller, Single-Path Version

**Python · Scraping · Data Processing · SQLite**

[Repository →](https://github.com/AdolfMacro/EYE-scrapper)

---

EYE-scrapper is the smaller predecessor to the more structured EYE Master architecture.

Instead of introducing the larger orchestration layer, it represents the same fundamental problem as a simpler, more direct pipeline.

```text
          QUERY
            │
            ▼
        SCRAPER
            │
            ▼
        PROVIDER
            │
            ▼
       RAW RESULTS
            │
            ▼
    EXTRACTION / FILTER
            │
            ▼
         STORAGE
```

### Why keep this project?

Because it shows **architectural evolution**.

The interesting story is not:

> “I built two scrapers.”

It is:

> **A simple implementation exposed a problem space, which later evolved into a more modular architecture.**

```text
EYE-scrapper
     │
     │  simple / direct
     ▼
┌─────────────────┐
│ Single-path     │
│ implementation  │
└────────┬────────┘
         │
         │ architectural growth
         ▼
┌─────────────────┐
│    EYE Master   │
│                 │
│ Providers       │
│ Workers         │
│ Processes       │
│ Validation      │
│ Storage         │
└─────────────────┘
```

This is one of the strongest examples in the portfolio of **learning through building**.

---

# `05` — PYTHON AUTOMATION & TOOLING

## ScriptArcher

### Networking & Security-Oriented Automation Toolkit

**Python · Automation · Networking · Linux**

[Repository →](https://github.com/AdolfMacro/ScriptArcher)

ScriptArcher is a Python-based toolkit built around repetitive networking, security and system-oriented tasks.

The project explores how individual utilities can be brought together into a more reusable tooling environment.

```text
NETWORKING
     │
     ├── Scanning
     ├── Packet Analysis
     └── Network Utilities

SYSTEM
     │
     ├── Utilities
     ├── CLI Tools
     └── Automation

SECURITY
     │
     ├── Analysis
     └── Security-Oriented Tooling
```

---

# `06` — NETWORK TOOLING

Several smaller experiments grew from the same interest in making network behavior observable.

### EyeAnalyzer

**Packet observation · IP filtering · Port filtering · Traffic analysis**

### EyeSniffer

**Traffic observation · Filtering · Network behavior · Flood mitigation concepts**

### EyeLimiter

**Traffic monitoring · Data-volume control · Resource behavior**

Together:

```text
              NETWORK TOOLING
                    │
       ┌────────────┼────────────┐
       ▼            ▼            ▼
  EyeAnalyzer   EyeSniffer   EyeLimiter
       │            │            │
       └────────────┼────────────┘
                    ▼
          Observe Network Behavior
```

These projects represent smaller experiments around the same larger question:

> **How can network behavior be captured, understood and controlled through software?**

---

# `07` — BINARY DATA & SECURITY EXPERIMENTS

## Phoenix

### Binary File Manipulation & Data Embedding

**Python · PNG · Fernet · Binary Data**

Phoenix explores the manipulation of binary file structures by embedding encrypted textual data into PNG images while preserving the image format.

The project combines:

`FILE FORMAT` · `BINARY DATA` · `ENCRYPTION` · `PYTHON`

The goal was not simply to use an existing library.

It was to understand what happens underneath the abstraction.

---

# `08` — WHAT I CAN BUILD

<div align="center">

### ⚙️ AUTOMATION

Python scripts · workflow automation · utilities · repetitive task reduction

### ◈ DATA

Web scraping · extraction · validation · structured data · SQLite pipelines

### 🖥 DESKTOP

PyQt5 / PyQt6 applications · monitoring interfaces · technical tools

### ◉ NETWORKING

Packet capture · network discovery · traffic observation · analysis tools

### ⌘ SYSTEMS

Linux utilities · CLI tools · process-oriented applications · system tooling

### 🔐 SECURITY

Security-oriented tooling · network security experiments · binary data · technical analysis

</div>

---

# `09` — SKILL MATRIX

| Area              | Evidence                                          |
| ----------------- | ------------------------------------------------- |
| **Python**        | Automation · Scraping · Tooling · Data Processing |
| **Desktop**       | PyQt5 · PyQt6 · Monitoring Interfaces             |
| **Linux**         | CLI · Processes · Permissions · System Tools      |
| **Networking**    | TCP/IP · Scapy · Capture · Discovery              |
| **Automation**    | ScriptArcher · Data Pipelines · Utilities         |
| **Web Scraping**  | EYE-scrapper · EYE Master                         |
| **Data**          | SQLite · Validation · Structured Processing       |
| **Security**      | Security Tooling · Network Analysis · Binary Data |
| **Architecture**  | Modular Systems · Pipelines · Provider Design     |
| **Visualization** | PyQt · Matplotlib · Real-time Statistics          |

---

# `10` — HOW I ENGINEER

### `01` BUILD

Start with something concrete.

### `02` OBSERVE

Watch what the system actually does.

### `03` UNDERSTAND

Identify the behavior, limitation or missing abstraction.

### `04` REFINE

Change the design based on evidence.

```text
BUILD
  ↓
OBSERVE
  ↓
UNDERSTAND
  ↓
REFINE
  ↓
BUILD AGAIN
```

This is why many of my projects evolve over time instead of appearing as isolated finished products.

**EYE-scrapper → EYE Master** is one example.

---

# `11` — ENGINEERING PRINCIPLES

### Evidence Over Claims

I prefer showing what a system actually does over making large claims about what I know.

### Structure Over Complexity

Complexity is useful only when it solves a real problem.

### Design for Extension

When a project grows, architecture should make the next change easier rather than harder.

### Build to Understand

Sometimes the fastest way to understand a system is to build a smaller version of it.

### Questions → Answers → Next Questions

A finished project does not necessarily mean the investigation is finished.

---

# `12` — TECHNICAL STACK

### Languages

`Python` · `Bash`

### Systems

`Linux` · `CLI` · `Processes` · `Permissions`

### Networking

`TCP/IP` · `Sockets` · `Scapy` · `Packet Capture` · `Network Discovery`

### Desktop

`PyQt5` · `PyQt6` · `Matplotlib`

### Data

`SQLite` · `Structured Data` · `Validation Pipelines`

### Web / Collection

`HTTP` · `Requests` · `Web Scraping` · `Multi-Provider Pipelines`

### Engineering

`Git` · `GitHub` · `Modular Architecture` · `Client/Server Concepts` · `Protocol Design`

---

# `13` — DEVELOPMENT APPROACH

I do not come from a traditional academic computer-science path.

My development has primarily been project-driven.

I learn by:

```text
READ DOCUMENTATION
       ↓
BUILD SOMETHING
       ↓
BREAK IT
       ↓
DEBUG IT
       ↓
READ THE IMPLEMENTATION
       ↓
CHANGE THE DESIGN
       ↓
BUILD AGAIN
```

Linux, networking, Python, security and architecture became connected through this process.

The result is not a claim of knowing everything.

It is an ability to **enter a technical problem, investigate it, build around it and keep learning while solving it.**

---

# `14` — WHAT I'M LOOKING FOR

I'm interested in opportunities where I can contribute through practical technical work in areas such as:

`Python Development`
`Automation`
`Web Scraping / Data Collection`
`IT Support`
`Linux / Systems`
`Networking / NOC`
`Infrastructure`
`Cybersecurity / Security Operations`
`QA / Technical Engineering`
`Junior Engineering Roles`

I'm particularly interested in environments where **real technical problems matter more than a perfect list of technologies.**

---

# `15` — BEYOND THE RESUME

The repositories are the deeper version of this document.

They contain the implementation, experiments, architecture decisions, mistakes, iterations and evidence behind the claims above.

### Start here

**EYE Network Vision**
→ Network visibility and analysis

**EYE Master**
→ Modular data discovery architecture

**EYE-scrapper**
→ The smaller implementation that preceded the larger architecture

**ScriptArcher**
→ Python automation and technical tooling

**Phoenix**
→ Binary data and file-format experimentation

---

# `16` — CONTACT

<div align="center">

## MANI KAMRAN

**Python · Automation · Systems · Networking · Security**

Yerevan, Armenia

**Email**
`m4nikamran@gmail.com`

**GitHub**
https://github.com/AdolfMacro

**LinkedIn**
https://www.linkedin.com/in/manikamran/

---

### MACROPINIX

**Build it. Observe it. Understand it. Improve it.**

</div>

---

<div align="center">

`© MANI KAMRAN · MACROPINIX`

</div>
