# THE LAST ARCHIVE // PS-07

An interactive research portfolio disguised as a corrupted computer system.

**The Last Archive** is a game-inspired portfolio where my academic work, research, projects, experience, and unfinished experiments are stored inside a fictional archival operating system.

Instead of scrolling through a conventional resume, you explore a simulated computer, open files, recover research records, inspect technical documentation, and uncover work that has never made it into a publication.

> **ARCHIVE NODE PS-07**
> **STATUS:** PARTIALLY RECOVERED
> **OWNER:** P. SHARMA
> **OBJECTIVE:** Recover the archive.

---

## Concept

Most portfolios present a polished list of finished work.

Research rarely works that way.

Some projects are published. Some are under review. Some are complete manuscripts that have never been submitted. Others are active experiments, failed approaches, hardware builds, or ideas still being developed.

**The Last Archive** treats all of that as part of the research process.

The website presents my work as a fictional recovered archive:

* Navigate a simulated desktop environment
* Explore research sectors and project files
* Open technical documents and experiment logs
* Inspect published and unpublished research
* Interact with embedded experiments and visualizations
* Discover active research and hardware builds
* Recover files to restore the archive's integrity

The goal is not simply to make a resume interactive.

It is to make the **process behind the resume visible**.

---

## What You'll Find

The archive contains material across several areas:

### Research

Research manuscripts, experimental results, methodologies, datasets, architectures, and research notes.

Includes work in:

* Robotics
* Autonomous systems
* Reinforcement learning
* Computer vision
* Machine learning
* Security
* Human-centered computing
* Planetary exploration

### Unpublished Research

Research that is complete or substantially developed but has not yet been formally published.

Each record distinguishes between:

* `PUBLISHED`
* `MANUSCRIPT COMPLETE`
* `UNDER REVIEW`
* `ACTIVE`
* `IN PREPARATION`
* `EXPERIMENTAL`

Unpublished does not mean undocumented.

The archive preserves the work, methodology, results, failures, and current status.

### Projects

Software, robotics, embedded systems, simulations, machine-learning systems, and experimental builds.

### Experience & Education

Academic background, research experience, internships, organizations, awards, certifications, and other professional records.

### Experimental Work

Incomplete systems, ongoing builds, research directions, and experiments that are still evolving.

---

## Featured Research

The archive includes detailed records rather than simple project summaries.

Examples include:

### NAZAKAT

**Compliant Morphology & Developmental Learning for Robotic Manipulation**

A research project investigating whether robust manipulation in uncertain environments is better achieved through compliant hardware, developmental reinforcement learning, or their combination.

The archive contains:

* Research question
* 2 × 2 factorial experimental design
* Robotic architecture
* Reinforcement-learning formulation
* Developmental curriculum
* Multi-seed results
* Failure analysis
* Hardware transition
* Research contribution
* Current manuscript status

### NAZAKAT // Physical Hardware

The companion physical realization of the simulation study.

Includes:

* 4-DOF robotic arm
* Soft six-pad gripper
* Force sensing
* Raspberry Pi deployment
* Embedded control
* Sim-to-real transfer plans
* Hardware build notes

### Planetary Terrain Risk

**Hybrid APSO–K-Means with Transformer Features for Planetary Terrain Risk**

A planetary robotics research project combining:

* Vision Transformers
* Adaptive Particle Swarm Optimisation
* K-Means clustering
* Synthetic Mars terrain
* Curiosity rover imagery
* C++17
* Python / PyTorch

The archive includes experimental comparisons, convergence plots, clustering metrics, runtime analysis, and the limitations of the approach.

### HCVCC

**Perception Is Not Enough: An Algorithm-Aware Security & Usability Evaluation of the HCVCC Text CAPTCHA**

A security research project investigating whether a CAPTCHA can shift difficulty from visual perception toward contextual reasoning.

The archive includes:

* CAPTCHA generator architecture
* Automated attackers
* Ablation experiments
* Held-out evaluation
* Human-study tooling
* LLM evaluation harness
* Statistical analysis
* Security findings

---

## Features

* Simulated archival operating system
* CRT / post-apocalyptic interface
* Glitch and scanline visual effects
* Interactive desktop environment
* File-system style navigation
* Draggable and resizable windows
* Taskbar and start menu
* Terminal interface
* Research document viewer
* Interactive CAPTCHA experiment
* Research tables and visualizations
* ASCII system diagrams
* Cross-linked research documents
* Published / unpublished / active status markers
* Archive recovery / progression system
* Signal and archive-integrity mechanics
* Sound toggle
* Responsive mobile interface
* Reduced-motion support
* Keyboard and pointer interaction

---

## Architecture

The project is intentionally built without a frontend framework.

It is a lightweight single-page application implemented with:

### Rendering & Interface

* HTML5
* CSS3
* Vanilla JavaScript
* SVG icons
* CSS animations
* Canvas-based visual effects

### Application Systems

**Window Manager**

Handles opening, focusing, minimizing, maximizing, dragging, resizing, and closing archive windows.

**Archive Data Layer**

Research and portfolio content is represented as structured JavaScript data rather than being hardcoded directly into the UI.

**Document Renderer**

Generates research documents from structured content including:

* Headings
* Paragraphs
* Tables
* Lists
* Code / ASCII diagrams
* Charts
* Cross-references
* Interactive components

**Recovery System**

Tracks which archive records have been accessed and uses recovery progress to represent the reconstruction of the archive.

**Terminal System**

Provides an interactive command-line interface for navigating and querying the archive.

**Interaction Layer**

Handles mouse, keyboard, touch, and window interaction.

---

## Tech Stack

* HTML5
* CSS3
* Vanilla JavaScript
* HTML5 Canvas
* SVG
* CSS animations
* Web APIs
* Google Fonts

No React, Vue, Bootstrap, or other frontend framework is required.

The entire archive is designed to run as a lightweight static web application.

---

## Project Structure

```text
/
├── index.html
├── Pari_Sharma_CV.pdf
└── README.md
```

The current implementation is intentionally compact: the interface, application logic, archive data, rendering systems, and interactions are contained within the main application.

---

## Controls

```text
MOUSE / POINTER
    Click files, windows, buttons and interface elements

KEYBOARD
    ENTER       Interact
    ESC         Close / return
    ARROWS      Navigate where applicable

TOUCH
    Tap         Interact
    Swipe       Navigate
```

---

## Why I Built This

A traditional resume answers:

> **What have you done?**

I wanted this project to answer a slightly different question:

> **How do you think about the things you've built?**

Research is rarely a straight line from idea → successful result.

There are failed experiments, unexpected results, architectural decisions, broken assumptions, iterations, and unfinished work.

This portfolio is designed to preserve some of that process.

It also gave me a way to combine several things I enjoy working on:

* Robotics
* Artificial intelligence
* Research
* Software systems
* Simulation
* Interactive design
* Experimental interfaces

---

## About Me

**Pari Sharma**

B.Tech Computer Engineering
SVKM's NMIMS, Mumbai
Expected graduation: 2027

### Areas of Interest

* Robotics & Autonomous Systems
* Artificial Intelligence & Machine Learning
* Embedded Systems
* Computer Vision
* Reinforcement Learning
* Space & Planetary Robotics
* Intelligent Autonomous Systems

I am particularly interested in building systems that allow machines to operate, learn, and make decisions in environments where direct human intervention is difficult or impossible.

---

## Archive Status

```text
ARCHIVE NODE       PS-07

OWNER              P. SHARMA
SYSTEM             ONLINE
NETWORK            PARTIALLY RESTORED
RESEARCH           ACTIVE
PUBLICATIONS       RECORDED
EXPERIMENTS        ONGOING

STATUS             RECOVERING...
```

---

## Links

* **LinkedIn:** [linkedin.com/in/pari-sharma-b045991b2](https://www.linkedin.com/in/pari-sharma-b045991b2)
* **GitHub:** [github.com/PariS-x](https://github.com/PariS-x)
* **Resume:** `Pari_Sharma_CV.pdf`

---

## License

This project is primarily a personal portfolio and research archive.

The underlying implementation is available for educational and reference purposes.
