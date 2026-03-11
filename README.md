# Intelligent Vacuum Cleaner Agent (3x3 Grid Environment)

## Technologies Used

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python)
![Random](https://img.shields.io/badge/Python-Random%20Library-lightgrey?style=flat-square&logo=python)
![Time](https://img.shields.io/badge/Python-Time%20Library-lightgrey?style=flat-square&logo=python)


## Overview
This repository contains the implementation of an **Intelligent Agent simulation** based on the classic **vacuum cleaner robot problem**. The agent is designed to **perceive its environment through sensors** and **act upon it using actuators** to ensure all areas are clean.

The project demonstrates the fundamental **AI Perception–Action cycle** within a controlled grid environment, focusing on **autonomous decision-making**.

---

## Objectives & Requirements

- Develop a functional **Intelligent Agent** that interacts with a simulated environment.
- Implement **Perception–Action logic**, where the robot identifies dirty rooms and performs cleaning.
- Manage **state constraints**, ensuring the agent only moves between adjacent rooms.
- Achieve a **goal-oriented state**, where the simulation concludes only when **100% of the environment is clean**.

---

## Key Features

- **Randomized Environment**  
  A **3 × 3 grid** of rooms where the **Clean/Dirty** status is generated randomly at the start of each execution.

- **Restricted Movement**  
  The agent follows strict navigation rules, moving only in **four directions**:
  - Up
  - Down
  - Left
  - Right  
  Diagonal movements are not permitted.

- **Orthogonal Navigation**  
  The robot can only move between **neighboring rooms**, preventing "teleportation" between non-adjacent cells.

- **Autonomous Cleaning Logic**  
  The agent evaluates its current position:
  - If the room is **dirty**, it cleans it.
  - If the room is **clean**, it moves to the next target room.

---
