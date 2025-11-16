# Week 04 – Instruction-Level Parallelism (ILP) using gem5
**Author:** Naveen Nallani  
**Course:** MSCS 531 – Computer Architecture & Design  
**University:** University of the Cumberlands  

This repository contains my Week 04 assignment exploring **Instruction-Level Parallelism (ILP)** using the gem5 simulator.

## 📘 Contents
- `WEEK04_Assignment_NaveenNallani.docx` – Final APA-formatted report with research, charts, and analysis.
- `m5out/` – gem5 simulation output directory (pipeline, branch prediction, superscalar, and SMT runs).
- `se.py` – gem5 configuration file used for simulation.

## 🧪 Experiments
The following ILP techniques were tested:
1. **Baseline (TimingSimpleCPU)**
2. **Branch Prediction (DerivO3CPU + LTAGE)**
3. **Superscalar Execution**
4. **Simultaneous Multithreading (SMT)**

## 📊 Results Summary
| Configuration | IPC | Avg Latency |
|---------------|-----|-------------|
| Baseline | 0.91 | 1.10 |
| Branch Prediction | 1.20 | 0.83 |
| Superscalar | 1.80 | 0.56 |
| SMT | 2.10 | 0.48 |

## 🧰 Tools Used
- gem5 v25.0.0.1  
- Python and Shell scripting  
- Ubuntu (WSL)

---

*Initial commit by Naveen Nallani – November 2025*
