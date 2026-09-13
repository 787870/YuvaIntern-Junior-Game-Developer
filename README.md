# YuvaIntern Junior Game Developer Portfolio 🎮

This repository contains the complete 4-week portfolio of work completed during the **Junior Game Developer Internship** with YuvaIntern. Over the course of this program, I designed, developed, optimized, and tested a core gameplay module: a **Dynamic Stamina & Dodge-Roll System** for an Action RPG.

## 🚀 Project Overview

The project focuses on creating a balanced resource-management mechanic where players must strategically balance offensive actions and defensive evasions. The module calculates real-time stamina consumption, manages exhaustion states, and handles delayed time-delta regeneration loops.

### 🛠️ Tech Stack
* **Language:** Python
* **Concepts:** Object-Oriented Programming (OOP), Game Loop Optimization, Boundary Clamping, Unit Testing

---

## 📂 Repository Structure

### [Week 1: Game Feature Planning and Design Document](./Week%201)
* **File:** `Week_1_Design.docx`
* **Focus:** Conceptualizing the stamina mechanic, defining core rules (max stamina, action costs, regeneration rates), designing the user experience, and creating pseudocode flow diagrams for the internal logic.

### [Week 2: Coding and Implementation of a Game Module](./Week%202)
* **File:** `Week_2_Code.docx` (Contains `stamina.py` logic)
* **Focus:** Translating the design document into functional, modular Python code. Developed the `StaminaController` class to handle real-time action validation, resource deduction, and time-delta regeneration within a simulated game loop.

### [Week 3: Debugging and Performance Optimization](./Week%203)
* **File:** `Week_3_Debug.docx`
* **Focus:** Identifying and resolving edge-case logic bugs (e.g., negative stamina values caused by floating-point imprecision and rapid input). Refactored the code using mathematical boundary clamps (`max()`, `min()`) and optimized CPU performance by adding early-exit conditionals during idle states.

### [Week 4: Testing and Quality Assurance Documentation](./Week%204)
* **File:** `Week_4_Testing.docx`
* **Focus:** Establishing a robust Quality Assurance (QA) framework. Designed and documented strict unit tests to validate valid action consumption, exhaustion rejection, cooldown delays, and upper boundary limits to ensure the module's stability before broader engine integration.

---
*Developed by A. Mohammed Aslam during the YuvaIntern Junior Game Developer Internship program.*
