# 🏥 Physiotherapy Center Simulation

### Data Structures & Algorithms Project — Cairo University

---

## 🔍 Project Overview

A simulation of a physiotherapy center that models real-world **patient scheduling, treatment workflows, and resource allocation** using custom data structures (**no STL**).

Designed to optimize efficiency and handle edge cases gracefully.

---

## 🎯 Key Objectives

* Simulate real-world patient flow:

  * Arrival
  * Waiting
  * Treatment
  * Discharge
* Optimize resource usage (**devices & rooms**) via priority-based scheduling
* Handle edge cases such as:

  * Cancellations
  * Rescheduling
  * Device failures

---

## ⚙️ Core Features

### 👥 Patient Management

* Categorizes patients as:

  * **Early**
  * **On-Time**
  * **Late**
* Applies penalties to late arrivals
* Supports **rescheduling** for early patients
* Allows **cancellation** for patients undergoing **exercise therapy only**

### 💊 Treatment Workflow

* **Normal Patients (N):** Follow a fixed, predefined treatment sequence
* **Recovering Patients (R):** Assigned treatment dynamically to improve resource utilization

### 🛠️ Resource Handling

Manages three types of treatment devices:

| Device | Type           |
| ------ | -------------- |
| **E**  | Electrotherapy |
| **U**  | Ultrasound     |
| **X**  | Exercise       |

* Simulates **room capacity limits**
* Supports optional **device failures** as a bonus feature

---

## ✅ Key Takeaways

This project showcases:

* Algorithmic thinking
* Real-world simulation
* Efficient data structure design from scratch
* Scheduling and prioritization
* Resource optimization
