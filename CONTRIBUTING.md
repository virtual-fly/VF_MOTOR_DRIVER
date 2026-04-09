
# Contributing to VF_Motor_Driver

Thank you for your interest in contributing to the VF_Motor_Driver project!  
We welcome community input, suggestions, and improvements.

This document outlines how you can contribute, and how we manage collaboration.

---

## 📌 Project Scope

VF_Motor_Driver is an open hardware board licensed under the GNU GPLv3.  
It is compatible with the [OpenFFBoard](https://github.com/Ultrawipf/OpenFFBoard) ecosystem but is developed and supported by **VirtualFly S.L.** for professional integration.

This repository contains:
- Schematics and PCB layout in KiCad format
- Hardware symbols and footprints (if applicable)
- Licensing and documentation files

**⚠️ The firmware and microcontroller board are not part of this repository.**

---

## 🧑‍💻 How to Contribute

We accept the following types of contributions:

- 🐞 Bug reports or electrical issues
- 💡 Suggestions to improve layout, protection, connectors, etc.
- 🔄 Fixes to the schematic or PCB files
- 📚 Improvements to documentation or README

If you have something to share, please follow the process below.

---

## 🔀 Merge Request Workflow (GitLab)

1. **Fork this repository** on GitLab.
2. Create a new branch for your change:
   ```bash
   git checkout -b my-contribution
   ```
3. Make your changes (using **KiCad 6 or newer**).
4. Commit and push your changes to your fork.
5. Open a **Merge Request** from your fork to this repository.

We will review your submission and reply as soon as possible.

---

## 📂 File Naming & Structure

- Use clear, descriptive filenames.
- Keep schematic (`.kicad_sch`) and PCB (`.kicad_pcb`) files inside their respective folders.
- If you introduce new symbols or footprints, include them in the `symbols/` folder and document them.

---

## 📏 Design Guidelines

- Design using **KiCad 6 or newer**.
- Maintain clarity and modularity in schematics.
- Use SI units and clear annotations.
- Prefer generic, widely available components.

---

## 💬 Bug Reports & Feature Requests

If you're not submitting a change but want to report something:

- Open an **Issue** in the GitLab Issues tab.
- Describe the problem clearly.
- Include screenshots, design screenshots, or simulation results if helpful.

---

## 📜 Licensing

By contributing, you agree that your changes will be licensed under the **GNU GPLv3** for hardware contributions, or under compatible terms for documentation.

---

## 🤝 Thanks for Supporting Open Hardware

Together we can make robust, reusable, and open tools for motion control and simulation.

Happy hacking!  
– The VirtualFly Team
