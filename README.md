# Mani Kamran

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=24&duration=3000&pause=1000&color=00FF99&center=true&vCenter=true&width=700&lines=Independent+Developer;Cybersecurity+Enthusiast;Building+to+Understand+Systems" />
</p>

<p align="center">
  <a href="https://github.com/adolfmacro">
    <img src="https://img.shields.io/badge/GitHub-AdolfMacro-181717?style=for-the-badge&logo=github" />
  </a>
  <a href="https://adolfmacro.github.io">
    <img src="https://img.shields.io/badge/Portfolio-Online-00ff99?style=for-the-badge&logo=googlechrome" />
  </a>
</p>

---

## About

I am an independent developer driven by real-world problems rather than predefined roadmaps.

Most of the projects I build begin with a practical need — something I could not solve or fully understand without building my own solution.

> **For me, programming is not just writing software; it is the process through which understanding becomes something real.**

> **Before searching for answers, I try to understand why the question exists and whether it truly reflects the problem behind it.**

---

## About This Portfolio

This portfolio documents how each project answered a question and how each answer created the next one.

The questions are presented because they reflect the way I think before I build, not simply the code I write.

Perhaps code is not the whole answer.

---

# Evidence

The projects below represent different stages of exploration.

Each project started with a question, evolved through experimentation, and created the next question.

---

# 🛰️ EyeRat

🔗 Repository: https://github.com/adolfmacro/EyeRat

## The Question

> Could communication between systems be understood and redesigned as a different interaction model?

---

## The Journey

As the communication model became more complex, the protocol itself required additional structure.

Interactive commands, encrypted messages, live camera streams, screenshots, files, and other data types had to coexist over the same communication channel without interfering with one another.

This led to designing an application-level communication protocol capable of framing, separating, and reconstructing different types of encrypted data while preserving a consistent communication model.

From outside the protocol, the communication no longer exposed the meaning or boundaries of the transmitted information, while the application itself could reliably interpret every message.

---

## The Outcome

EyeRat became a foundation for exploring remote communication models rather than just building a collection of features.

The project created a deeper understanding of how changing the communication approach could affect the capabilities and limitations of a system.

---

## Derived Exploration

### Can the network environment be changed?

# 🌐 LordRat

🔗 Repository: https://github.com/adolfmacro/LordRat

## The Exploration

LordRat was created to explore whether the same communication model could work through a different environment.

It was not built as a replacement for EyeRat or as a more complete version of it.

Instead, it changed the communication path by using an IRC chat room as an intermediary.

The project showed that changing the communication environment could provide another way to explore the same interaction model.

---

## Technical Understanding

This exploration led to designing communication as an application-level protocol rather than a simple data channel.

It demonstrated how message framing, encrypted communication, and transport independence could shape the behavior of an entire system.

---

## Questions Explored After LordRat

### Does every remote interaction require the same set of capabilities?

---

# 🧩 MiniRat

🔗 Repository: https://github.com/adolfmacro/EyeRat#what-is-a-minirat-

LordRat answered how the communication environment could change.

This raised another question:

> **Does every remote interaction require the same set of capabilities?**

Instead of treating remote access as a single application, MiniRat explored whether each objective could become an independent deployment unit.

Rather than building one large executable, it separated communication into purpose-driven components, allowing only the required capability to be deployed.

This transformed functionality itself into a modular architecture rather than a fixed collection of features.

This also demonstrated that deployment itself could become modular, allowing each executable to represent a single purpose rather than an entire framework.

---

<br>

# 🏹 ScriptArcher

🔗 Repository: https://github.com/adolfmacro/ScriptArcher

## The Question

> Could combining different tools used in daily workflows create a more structured and effective approach?

---

## The Journey

ScriptArcher started from the need to organize different tools used across various workflows.

Instead of using each tool separately, the project explored whether combining them into a single toolkit could create a more connected workflow and reduce repeated preparation.

The project brought together different networking and security-related tools, including scanning, packet analysis, and system utilities, creating a practical environment to understand how different tools could work together.

Through this process, the focus shifted from collecting tools to understanding how the structure of a toolkit could affect the way tasks are approached.

---

## The Outcome

ScriptArcher showed that a well-organized toolkit could improve workflow efficiency and reduce the time spent preparing and switching between different tools.

More importantly, it created a better understanding of when combining tools provides value compared to using them individually.

This raised a new question:

> If tools are only the means, what is it that truly needs to be observed and understood?

---

# 👁️ EyeAnalyzer

🔗 Repository: https://github.com/adolfmacro/EyeAnalyzer

## The Question

> What is the minimum that needs to be observed?

---

EyeAnalyzer was created to answer a simple question:

What is the minimum information required to understand network behavior?

Instead of analyzing packet contents or traffic details, it focused only on counting packets matching simple filters such as IP addresses or ports.

The project explored whether basic observation alone could reveal meaningful network behavior.

---

## New Question

> Could observation itself be protected from simple network noise?

---

# 🛡️ EyeSniffer

🔗 Repository: https://github.com/AdolfMacro/EyeSniffer

EyeSniffer was created to answer a simple question:

> Could observation be protected from simple network noise?

Instead of expanding packet analysis, it introduced basic controls such as blocking predefined IP addresses and reducing the impact of intentional packet flooding.

The goal was not to build a firewall, but to preserve clearer observation by preventing obvious interference.

---

## New Question

> Could the same type of control be applied to network data volume?

---

# 📊 EyeLimiter

🔗 Repository: https://github.com/AdolfMacro/EyeLimiter

EyeLimiter was created to answer a simple question:

> Could the same type of control be applied to network data volume?

Instead of focusing on individual packets, it explored whether limiting network data volume could become another simple layer of observation.

The project remained focused on answering that single question rather than becoming a complete traffic management system.

---

## Technical Understanding

This exploration gradually shifted the focus from collecting network information to understanding:

- What should actually be observed
- How observation can remain reliable
- How unnecessary complexity can be removed without losing meaningful behavior

---

<br>

# 🔥 Phoenix

🔗 Repository: https://github.com/AdolfMacro/phoenix

An independent exploration into file structure, hidden data, and encryption.

---

## The Idea

This project started from exploring whether information could be stored inside another file format while keeping the original file usable.

Instead of focusing on traditional data storage methods, it explored the idea of embedding data into an image and understanding how the file structure could be used as a medium for carrying information.

---

## The Approach

The project implemented a simple method for attaching text data to PNG images while preserving the image format.

It also explored adding an encryption layer using Fernet to protect the embedded data and make the stored information accessible only with the correct key.

The goal was not to create a complete steganography system, but to understand the behavior of files and how data can exist beyond what is directly visible.

---

## The Outcome

The project created a practical understanding of how file structures can be used to store additional information and how encryption can be combined with data embedding.

It provided a deeper view of the relationship between visible content, hidden data, and the way digital files are structured.

---

# 🧠 Technical Skills

## Programming

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnubash&logoColor=white)

- Python
- Bash

---

## Software Engineering

- Client/Server Architecture
- Application-Level Protocol Design
- Modular Software Design

---

## Security

- Secure Communication
- Binary File Manipulation

---

## Networking

- Socket Programming
- Packet Analysis
- Traffic Observation

---

## Technologies & Tools

<p align="center">

<img src="https://skillicons.dev/icons?i=linux,git,python,bash" />

</p>

Additional tools:

- Scapy
- Nmap
- OpenCV

---

# 🎓 Education

## Independent Learning

My education has been driven primarily by curiosity, experimentation, and long-term self-study.

Instead of following predefined learning paths, I have focused on understanding systems by building projects, reading technical documentation, and studying the underlying concepts behind software and computer systems.

Over time, this learning has included Linux internals, networking, cryptography, communication protocols, and software architecture.

---

## Contact
Every project in this portfolio started with a conversation between a question and an idea.
Perhaps the next one starts with a conversation.

- GitHub: https://www.github.com/adolfmacro
- Email: m4nikamran@gmail.com
- WebPage: https://adolfmacro.github.io
**Perhaps code was never the destination—only the language I used to understand the questions.**
