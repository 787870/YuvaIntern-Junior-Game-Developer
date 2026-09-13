# Week 4: Testing and Quality Assurance Documentation

## 🎯 Objective
The goal of this week was to establish a robust Quality Assurance (QA) framework and document a comprehensive test plan to ensure the game module operates flawlessly under stress.

## 🧪 QA & Test Plan
This folder contains the testing documentation for the stamina module. Since resource management is critical to gameplay balance, the module must mathematically verify all inputs and boundaries.

### Testing Scope:
* **Valid Action Consumption:** Verifying exact mathematical deductions.
* **Exhaustion Rejection:** Ensuring actions are blocked when resources are depleted (Edge Case).
* **Cooldown Timers:** Validating the time-delta logic respects the 1.5-second delay.
* **Upper Boundary Limits:** Confirming the regeneration loop strictly halts at 100.0 without overflowing.

**Included File:** `Week_4_Testing.docx`
