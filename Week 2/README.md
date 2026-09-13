# Week 2: Coding and Implementation of a Game Module

## 🎯 Objective
The goal of this week was to translate the Week 1 Game Design Document into clean, functional, and well-documented code using Object-Oriented Programming (OOP) principles.

## 💻 Implementation: Stamina Controller (Python)
This folder contains the functional Python module (`StaminaController`) that handles the logic for our Dynamic Stamina & Dodge System. 

### Core Features:
* **Action Validation:** The `attempt_dodge()` method checks if the player has sufficient resources before allowing an action, handling deductions automatically.
* **Time-Delta Regeneration:** The `update()` method calculates elapsed time to enforce a 1.5-second cooldown delay before stamina begins regenerating.
* **Modular Design:** Built as a standalone class, making it easy to integrate into a larger game engine's character script.

**Included File:** `Week_2_Code.docx` (Contains the Python script and simulation logic).
