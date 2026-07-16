# Hazard Detection and Data Forwarding in a 7-Stage Pipelined Processor

**Design and Analysis of Forwarding Units and Hazard Detection Unit (HDU)**

**Author:** Sumaira Safeer  
**Course:** Computer Organization and Architecture (CPE-343)  
**Program:** BS Computer Engineering  
**Institution:** COMSATS University Islamabad, Attock Campus  
**Submitted To:** Engr. Farwida Javed

---

## 📌 Project Overview

This semester project focuses on **advanced pipelining challenges** in computer architecture, specifically:

- Identifying and resolving **data hazards** (RAW) in a **7-stage pipelined processor**
- Designing **Forwarding Units** for both **Integer** and **Floating-Point** execution units
- Designing a **Hazard Detection Unit (HDU)** to handle unavoidable stalls (e.g., load-use hazards)
- Analyzing pipeline execution for floating-point instruction sequences

The processor features a complex pipeline with separate stages for Instruction Fetch (F1, F2), Decode (ID), Execution (EX for integer, EX-1/EX-2/EX-3 for FP), Memory (M1, M2), and Register Write (RW).

---

## 🛠️ Key Topics Covered

- **Data Hazards** (RAW) in deep pipelines
- **Forwarding (Bypassing)** mechanisms for Integer and Floating-Point units
- **Hazard Detection Unit (HDU)** design in the ID stage
- **Load-Use Hazards** requiring stalls even with forwarding
- **Floating-Point Pipeline** analysis (FADD, FSUB, FMUL)
- Pipeline diagrams and datapath design

---

## 📁 Repository Contents

| Folder       | Description                                      |
|--------------|--------------------------------------------------|
| `Report/`    | Complete project report with analysis and designs |
| `Diagrams/`  | Pipeline diagrams and datapath designs (optional) |

---

## 📋 Questions Addressed

| Question | Focus |
|----------|-------|
| Q1       | Integer instruction sequence showing data hazards |
| Q2       | Forwarding Unit design for Integer EX stage |
| Q3       | Sequence requiring stalls even with forwarding (Load-Use hazard) |
| Q4       | Hazard Detection Unit (HDU) design in ID stage |
| Q5       | Floating-point pipeline execution without forwarding (14+ cycles) |
| Q6       | Forwarding Unit design for Floating-Point EX-1 stage |

---

## 📄 Report

The full project report including theoretical analysis, detailed solutions, pipeline diagrams, and conclusions is available in the `Report/` folder.

---

## 👩‍🎓 Author

**Sumaira Safeer**  
BS Computer Engineering 
COMSATS University Islamabad, Attock Campus  
[LinkedIn](https://www.linkedin.com/in/sumaira-safeer-948804418/)

---

*This project demonstrates deep understanding of pipelined processor design, hazard handling, and forwarding mechanisms in modern computer architecture.*
