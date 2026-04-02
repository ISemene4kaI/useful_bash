# 🧩 BashOps Toolkit

A collection of Bash scripts for Linux system diagnostics, health checks, and automation of routine DevOps tasks.

Built as a practical toolkit — focused on real-world usage, not theory.

---

## ⚡ Features

- System health checks (CPU, RAM, disk, uptime)
- Process and resource analysis
- Service monitoring (systemd)
- Network and port inspection
- Log analysis (including 4xx/5xx errors)
- Modular architecture for building custom scripts
- Reusable Bash modules

---

## 🏗️ Project Philosophy

This project follows a simple idea:

> Small, understandable tools that solve real problems.

- No overengineering  
- Minimal dependencies  
- Works out of the box  
- Easy to extend  

---

## 💬 Discussions & Contributions

All ideas and improvements are welcome.

The goal is to build a toolkit that actually helps with everyday DevOps tasks and reduces manual work.

You can:
- open a Discussion
- submit a Pull Request

All contributions will be reviewed 🙌

---

## 📁 Project Structure

- docs/ — documentation for all scripts (usage, flags, arguments)
- src/modules/ — small reusable Bash modules (single responsibility)
- src/builds/ — composed scripts built from modules
- src/ — high-level scripts with extended functionality

---

## 📂 Structure overview

```
docs/
  builds/
    bash_1
    bash_2
  modules/
    bash_module_1.md
    bash_module_2.md
  bash_1.md
  bash_2.md

src/
  builds/
    bash_1
    bash_2
  modules/
    bash_module_1
    bash_module_2
  bash_1
  bash_2
```

---

## 🚀 Getting Started

```
chmod +x src/bash_1
./src/bash_1
```

---

## 🧠 Future Plans

- Full system audit script
- JSON output support
- Colored CLI output
- Integration with monitoring tools
- Unified CLI interface

---

## ⭐ Why this project?

This repository is built as part of hands-on DevOps practice.

The focus is not just writing scripts, but building tools that:
- scale
- can be reused
- are actually useful in production environments

---

If this project helps you — consider giving it a star ⭐
