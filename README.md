# Capstone-Project-2025
# 🚗 Dynamic Pricing for Urban Parking Lots

### 🧠 Capstone Project – Summer Analytics 2025  
👤 By: Tanisha Lalwani

---

## 📌 Overview

This project implements a real-time **dynamic pricing system** for 14 urban parking lots using Machine Learning models and economic principles. The system intelligently adjusts parking rates based on live demand signals such as:

- Lot occupancy
- Queue length
- Traffic congestion
- Nearby competition

🎯 **Goal:**  
Maximize utilization, reduce congestion, and ensure transparent & fair pricing for users.

---

## 🧰 Tech Stack

| Category           | Tools Used                          |
|--------------------|-------------------------------------|
| Programming        | Python                              |
| Data Handling      | NumPy, Pandas                       |
| Real-Time Engine   | Pathway                             |
| Visualization      | Bokeh                               |
| IDE                | Google Colab                        |
| Version Control    | Git, GitHub                         |

---

## 📐 Architecture Diagram

```mermaid
graph TD
    A[Data Simulation (Pathway)] --> B[Real-time Data Ingestion]
    B --> C[Feature Extraction (Occupancy, Queue, Traffic...)]
    C --> D[Pricing Logic (3 Models)]
    D --> E[Price Output]
    E --> F[Bokeh Visualization]
