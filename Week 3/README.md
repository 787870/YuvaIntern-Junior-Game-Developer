# Week 3: Debugging and Performance Optimization

## 🎯 Objective
The goal of this week was to analyze existing code, identify logic bugs, and optimize the game loop for better performance and reliability.

## 🐛 Bug Fixes & Optimization
This folder contains the debugging report detailing how the `StaminaController` was refactored to prevent game-breaking errors and reduce CPU overhead.

### Key Improvements:
* **Boundary Clamping:** Fixed a critical bug where rapid player inputs combined with floating-point imprecision caused stamina to drop below zero. Implemented Python's `max()` and `min()` functions to strictly clamp values between 0.0 and 100.0.
* **Game Loop Optimization:** Added an early-exit `return` statement to the `update()` loop. The script now completely bypasses regeneration math if the player is already at max stamina, saving CPU cycles during idle gameplay.

**Included File:** `Week_3_Debug.docx`
