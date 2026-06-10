# 🎓 CT&DT-Galgotias-Batch No:5-Task 1-Product Failure Analysis

<div align="center">

![Task Badge](https://img.shields.io/badge/Task-01-7c3aed?style=for-the-badge&logo=notion)
![Course Badge](https://img.shields.io/badge/Course-CT%26DT-06b6d4?style=for-the-badge)
![Batch Badge](https://img.shields.io/badge/Batch-5-f59e0b?style=for-the-badge)
![Tool Badge](https://img.shields.io/badge/Dataset-Kaggle-10b981?style=for-the-badge&logo=kaggle)

**Critical Thinking, Design Thinking, Leadership and Teamwork**
Galgotias University · Batch No: 5 · Task #01

</div>

---

## 📌 Task Overview

> **Topic: Fundamentals of Design Thinking — Product Failure Analysis**
> **Task #01 – Machine Failure Analysis**
>
> 1. Identify and Fix the product
> 2. Explore its features which may lead to product failure
> 3. Prepare an Excel sheet like the example dataset

**Dataset:** [Kaggle Machine Failure Data](https://www.kaggle.com/datasets/binaicrai/machine-failure-data)

---

## 🏭 Product Identified — CNC Manufacturing Machine

**Problem:** CNC machines in manufacturing plants experience unpredictable failures due to tool wear, heat dissipation issues, power overloads, and overstrain — causing costly unplanned downtime.

---

## 📊 Features Explored (Leading to Machine Failure)

| Feature | Description | Failure Threshold |
|---|---|---|
| **Air Temperature (K)** | Ambient temperature around machine | Affects heat dissipation |
| **Process Temperature (K)** | Operating temperature during machining | Diff < 8.6K → HDF |
| **Rotational Speed (rpm)** | Spindle speed | Low speed + high torque → PWF |
| **Torque (Nm)** | Cutting force applied | >65 Nm → Overstrain risk |
| **Tool Wear (min)** | Cumulative tool usage time | >200 min (H), >150 min (M), >53 min (L) |

## ⚠️ Failure Types Identified

| Code | Failure Type | Cause |
|---|---|---|
| **TWF** | Tool Wear Failure | Tool wear exceeds type-specific threshold |
| **HDF** | Heat Dissipation Failure | Temp difference between air & process < 8.6K |
| **PWF** | Power Failure | Torque × RPM exceeds 9000 W·min |
| **OSF** | Overstrain Failure | Tool wear × Torque exceeds limit for machine type |
| **RNF** | Random Failure | Unexpected 0.1% probability failure |

## 🔧 Fix Recommendations

1. **TWF Fix** → Replace cutting tool before wear threshold; implement tool life monitoring sensors
2. **HDF Fix** → Improve cooling system; clean heat exchangers and vents regularly
3. **PWF Fix** → Limit operational torque-speed combinations; use intelligent load balancing
4. **OSF Fix** → Reduce machining load; schedule preventive maintenance based on torque trends
5. **RNF Fix** → Implement redundant sensors and automated shutdown on anomaly detection

---

## 📁 Files

| File | Description |
|---|---|
| `Machine_Failure_Analysis_CTDT_Batch5_Task1.csv` | Excel dataset with 50 records — failure analysis & fix recommendations |
| `README.md` | This file |

---

## 📬 Submission Details

| Field | Details |
|---|---|
| **Course** | Critical Thinking, Design Thinking, Leadership & Teamwork |
| **College** | Galgotias University |
| **Batch** | Batch No: 5 |
| **Task** | Task #01 — Product Failure Analysis |
| **Product** | CNC Manufacturing Machine |
| **Dataset** | Kaggle Machine Failure Dataset |
| **Path** | `CT&DT-Galgotias-Batch No:5-Task 1-Product Failure Analysis` |

---

<div align="center">

Made with ❤️ for the Critical Thinking, Design Thinking, Leadership & Teamwork Course
**Galgotias University · Batch 5 · Task #01**

</div>
