<div align="center">

# Mani Kamran

### `Python` · `Linux` · `Networking` · `Security`

**Independent Developer · Systems Builder · Technical Explorer**

<p>
  <a href="https://github.com/AdolfMacro">
    <img src="https://img.shields.io/badge/GitHub-AdolfMacro-181717?style=for-the-badge&logo=github" alt="GitHub">
  </a>
  <a href="https://www.linkedin.com/in/manikamran/">
    <img src="https://img.shields.io/badge/LinkedIn-Mani%20Kamran-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn">
  </a>
  <img src="https://img.shields.io/badge/Location-Yerevan%2C%20Armenia-00B87A?style=for-the-badge" alt="Location">
</p>

</div>

---

## `01` — Who I Am

I'm an **independent developer and technical builder** focused on understanding systems by building them.

I like taking technical questions that are difficult to see from the outside and turning them into something **observable, testable, and understandable**.

> **Build it. Observe it. Understand it. Improve it.**

My main areas of interest are:

| Area                | Focus                                                             |
| ------------------- | ----------------------------------------------------------------- |
| 🐍 **Python**       | Automation, tooling, data processing, modular applications        |
| 🐧 **Linux**        | Systems, processes, permissions, networking, CLI environments     |
| 🌐 **Networking**   | TCP/IP, sockets, discovery, packet capture, traffic analysis      |
| 🔐 **Security**     | Network security, secure communication, security-oriented tooling |
| ⚙️ **Architecture** | Modular systems, pipelines, providers, separation of concerns     |
| 🧩 **Data**         | Collection, validation, processing, structured storage            |

---

# `02` — Technical Landscape

```text
                         ┌───────────────────┐
                         │       Python      │
                         │ Automation / CLI  │
                         │ Data / Tooling    │
                         └─────────┬─────────┘
                                   │
                                   ▼
┌──────────────────┐      ┌───────────────────┐      ┌──────────────────┐
│      Linux       │ ───► │      Systems      │ ◄─── │    Networking    │
│ Processes / CLI  │      │ Architecture      │      │ TCP/IP / Packets │
│ Permissions      │      │ Protocols         │      │ Discovery        │
└────────┬─────────┘      └─────────┬─────────┘      └────────┬─────────┘
         │                          │                          │
         └──────────────────────────┼──────────────────────────┘
                                    ▼
                           ┌───────────────────┐
                           │     Security      │
                           │ Analysis / Tools  │
                           │ Experimentation   │
                           └───────────────────┘
```

---

# `03` — Featured Projects

<div align="center">

## 👁️ EYE Network Vision

### Network Visibility & Security Analysis

</div>

EYE Network Vision is a modular network-visibility platform built with Python.

Instead of treating packet capture as the final output, the project attempts to transform network activity into **structured models representing nodes, segments, and traffic flows**.

### ⚡ Capabilities

```text
Interface Discovery
       │
       ├── IPv4 detection
       ├── Netmask detection
       ├── Broadcast detection
       └── Network segmentation
                │
                ▼
         Packet Collection
                │
       ┌────────┴────────┐
       │                 │
   Active Discovery   Passive Discovery
       │                 │
       └────────┬────────┘
                ▼
        Traffic Analysis
                │
                ▼
       Structured Models
                │
       ┌────────┼────────┐
       ▼        ▼        ▼
    Nodes    Segments   Flows
                │
                ▼
       Reports / Visualization
```

### 🧰 Stack

`Python` `Scapy` `PyQt6` `psutil` `Matplotlib` `Linux`

### 🔗 Repository

**https://github.com/AdolfMacro/EYEnv**

---

<div align="center">

## 👁️ EYE Master

### Geographic Data Collection & Validation

</div>

EYE Master started as a web-scraping project and evolved into a modular **business and POI discovery framework**.

The core idea is simple:

> **Raw data is not useful until it has been validated and structured.**

### ⚡ Core System

```text
                  ┌──────────────┐
                  │     GUI      │
                  └──────┬───────┘
                         ▼
                  GUI Controller
                         │
                         ▼
               Master / Process Manager
                         │
                         ▼
                  Scraper Process
                         │
                         ▼
                   Scraper Worker
                         │
                         ▼
                   Scraper Engine
                         │
              ┌──────────┼──────────┐
              ▼          ▼          ▼
        Query Generator Provider   Pipeline
                         │          │
                         ▼          ▼
                    Raw Results → Validation
                                      │
                         ┌────────────┴────────────┐
                         ▼                         ▼
                 Valid Coordinates          No Coordinates
                         │                         │
                         ▼                         ▼
                      RECORD                    DISCARD
```

### 🌍 Providers

`Google` · `DuckDuckGo` · `OpenStreetMap` · `Balad`

### 🧰 Stack

`Python` `PyQt5` `SQLite` `Requests/HTTP`

### 🔗 Repository

**https://github.com/AdolfMacro/EYE-scrapper-master**

---

# `04` — Protocol & Systems Engineering

A major part of my earlier experimentation focused on understanding **how software communicates below the application surface**.

## EyeRat

Experimental client/server communication project exploring:

* Application-level protocols
* Client/server architecture
* Message framing
* Data serialization and reconstruction
* Encrypted communication
* Structured command/message models
* File and media transfer concepts

The project served primarily as a **protocol and systems-engineering experiment**.

---

## LordRat

An experimental communication architecture exploring **IRC as an intermediary transport layer**.

Focus areas:

`Transport Abstraction` · `Protocol Design` · `Message Routing` · `Communication State`

---

## MiniRat

An experimental project exploring modular remote-interaction components and purpose-driven system modules.

Focus areas:

`Modularity` · `Component Boundaries` · `Communication` · `Deployment Design`

---

# `05` — Network & Security Tooling

### 🏹 ScriptArcher

A unified networking/security-oriented toolkit.

**Explores:**

`Network Scanning` · `Packet Analysis` · `System Utilities` · `Tool Integration` · `Automation`

---

### 🔎 EyeAnalyzer

A lightweight network-observation tool focused on:

`Packet Counting` · `IP Filtering` · `Port Filtering` · `Traffic Observation`

---

### 🛡️ EyeSniffer

An experimental network-control project exploring:

`IP Filtering` · `Traffic Control` · `Flood Mitigation Concepts` · `Network Observation`

---

### 📊 EyeLimiter

An experimental project exploring:

`Traffic Monitoring` · `Data-Volume Limiting` · `Resource Control` · `Network Behavior`

---

# `06` — Security & Binary Data

## 🔥 Phoenix

An experiment combining **binary file manipulation, data embedding, and encryption**.

The project explores embedding encrypted textual data into PNG files while preserving the image format.

### Concepts

```text
PNG Structure
     │
     ▼
Binary File Manipulation
     │
     ▼
Data Embedding
     │
     ▼
Fernet Encryption
     │
     ▼
Structured File Output
```

**Technologies:** `Python` `PNG` `Fernet` `Binary Data`

---

# `07` — Engineering Philosophy

<div align="center">

### Build → Observe → Understand → Refine

</div>

```text
┌───────────┐
│  Problem  │
└─────┬─────┘
      ▼
┌───────────┐
│ Question  │
└─────┬─────┘
      ▼
┌───────────┐
│ Experiment│
└─────┬─────┘
      ▼
┌───────────┐
│Implement  │
└─────┬─────┘
      ▼
┌───────────┐
│ Observe   │
└─────┬─────┘
      ▼
┌───────────┐
│ Refine    │
└─────┬─────┘
      │
      └──────────────► New Question
```

### `01` — Build to Understand

I use software to turn abstract technical questions into systems that can be observed and tested.

### `02` — Structure Over Complexity

I prefer clear separation of responsibilities over large, tightly coupled components.

### `03` — Design for Extension

Provider architectures, modular components, and processing pipelines appear repeatedly in my projects because I like systems that can evolve without being rewritten from scratch.

### `04` — Evidence Over Claims

I prefer demonstrating what I can build rather than relying on excessive skill labels.

---

# `08` — Technology Stack

### Languages

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/Bash-121011?style=flat-square&logo=gnubash&logoColor=white">
</p>

### Systems

`Linux` `Process Management` `CLI` `System Tooling` `Permissions`

### Networking

`TCP/IP` `Socket Programming` `Scapy` `Packet Capture` `Traffic Analysis` `Network Discovery`

### Security

`Network Security` `Secure Communication` `Security Tooling` `Binary File Manipulation`

### Frameworks & Libraries

`PyQt5` `PyQt6` `Scapy` `Requests` `psutil` `Matplotlib`

### Data

`SQLite` `Structured Data Processing` `Validation Pipelines`

### Development

`Git` `GitHub` `Modular Architecture` `Client/Server Architecture` `Protocol Design`

---

# `09` — Selected Projects

| Project                    |     Area     | Core Focus                                  |
| :------------------------- | :----------: | :------------------------------------------ |
| 👁️ **EYE Network Vision** |  Networking  | Visibility · Capture · Discovery · Analysis |
| 👁️ **EYE Master**         |     Data     | POI Discovery · Validation · Pipelines      |
| 🔬 **EyeRat**              |    Systems   | Client/Server · Protocol Engineering        |
| 🔬 **LordRat**             |    Systems   | Transport Abstraction · Protocol Design     |
| 🧩 **MiniRat**             | Architecture | Modular Components                          |
| 🏹 **ScriptArcher**        |   Security   | Network Tooling · Automation                |
| 🔎 **EyeAnalyzer**         |  Networking  | Traffic Observation                         |
| 🛡️ **EyeSniffer**         |  Networking  | Traffic Control Experiments                 |
| 📊 **EyeLimiter**          |  Networking  | Data / Traffic Limiting                     |
| 🔥 **Phoenix**             |   Security   | Binary Files · Data Embedding · Encryption  |

---

# `10` — Technical Development

I don't have a traditional academic background in computer science.

My technical development has been primarily **independent and project-driven**.

I learn by:

* Building real systems
* Reading documentation
* Studying existing implementations
* Experimenting with Linux
* Exploring networking and protocols
* Debugging problems
* Reading source code
* Refactoring and restructuring my own projects
* Turning technical questions into experiments

My current technical direction can be summarized as:

```text
                 Linux
                   │
                   ▼
              Networking
                   │
                   ▼
                Systems
                   │
                   ▼
                Python
                   │
                   ▼
              Automation
                   │
                   ▼
               Security
```

---

# `11` — What I'm Looking For

I'm interested in opportunities where practical engineering, troubleshooting, and continuous learning are valued.

### Areas of Interest

`IT Support` · `Technical Support` · `Linux / Systems Administration`

`Network Engineering` · `NOC` · `Infrastructure`

`Cybersecurity` · `Security Operations`

`Python Development` · `Automation`

`QA / Technical Engineering`

`Junior Engineering Roles`

I'm particularly interested in environments where I can **work with real systems, solve technical problems, and continue developing deeper expertise**.

📍 **Yerevan, Armenia**

---

# `12` — Beyond the Resume

I don't try to present myself as someone who already knows everything.

I'm more interested in being the person who can take an unfamiliar system, **break the problem down, investigate it, understand how it works, and build a solution**.

That's the approach behind most of my projects.

> **Curiosity drives the question.
> Engineering turns it into something real.**

---

# `13` — Contact

<div align="center">

### Mani Kamran

**Python · Linux · Networking · Security**

📍 Yerevan, Armenia

📧 **[m4nikamran@gmail.com](mailto:m4nikamran@gmail.com)**

📞 **+374 91 417836**

<br>

<a href="https://github.com/AdolfMacro/">
  <img src="https://img.shields.io/badge/GitHub-AdolfMacro-181717?style=for-the-badge&logo=github" alt="GitHub">
</a>

<a href="https://www.linkedin.com/in/manikamran/">
  <img src="https://img.shields.io/badge/LinkedIn-Mani%20Kamran-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn">
</a>

<br><br>

`Thanks for stopping by.`

</div>
