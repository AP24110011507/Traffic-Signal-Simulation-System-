# 🚦 Traffic Signal Simulation with Emergency Vehicle Priority

## 📌 Overview
This project is a C-based simulation of a traffic signal system that manages vehicle flow at an intersection. It also includes a priority system for emergency vehicles like ambulances and fire trucks, ensuring they get immediate passage through traffic.

---

## 🎯 Features
- 🚗 Simulates normal traffic signal cycle (North, East, South, West)
- 🚨 Emergency vehicle priority handling
- 🔁 Continuous loop-based simulation
- ⏱️ Time-based signal switching using delays
- 🖥️ Menu-driven console interface

---

## 🛠️ Technologies Used
- Language: **C Programming**
- Concepts: Loops, Functions, Conditionals, Flags, Basic Time Delay

---

## ⚙️ How It Works
1. The system runs a traffic signal cycle for four directions.
2. Each direction gets a green signal one by one.
3. If an emergency vehicle is detected:
   - Normal cycle is interrupted
   - The emergency route is given priority (GREEN signal)
   - Other directions are set to RED
4. After clearance, normal traffic resumes automatically.

---

## ▶️ How to Run

### Compile the program:
```bash
gcc traffic_signal.c -o traffic_signal
