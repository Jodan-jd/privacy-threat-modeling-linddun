# 🛡️ Privacy Threat Modeling using LINDDUN

## 📌 Overview

This project performs a privacy risk assessment of a disaster relief communication system using the **LINDDUN privacy threat modeling framework**.

The system involves drone-based communication and real-time data exchange, making it critical to evaluate privacy risks such as data leakage, linkability, and unauthorized access.

---

## 🧠 Framework Used

### 🔍 LINDDUN

A privacy threat modeling methodology focusing on:

* **L**inkability
* **I**dentifiability
* **N**on-repudiation
* **D**etectability
* **D**isclosure of information
* **U**nawareness
* **N**on-compliance

---

## 🎯 Objective

To identify and mitigate privacy risks in a distributed disaster communication system by applying structured threat modeling techniques.

---

## 🔬 Methodology

### 1. System Modeling

* Defined system components:

  * Drones
  * Communication servers
  * User endpoints

---

### 2. Data Flow Analysis

* Identified data flows across:

  * MQTT communication channels
  * Sensor data streams
  * Control commands

---

### 3. Threat Identification

* Applied LINDDUN categories to each data flow
* Identified privacy threats such as:

  * Data exposure
  * User tracking
  * Unauthorized data access

---

### 4. Risk Assessment

* Evaluated severity and likelihood
* Prioritized threats

---

### 5. Mitigation Strategies

Proposed solutions including:

* End-to-end encryption
* Data minimization
* Pseudonymization
* Access control mechanisms

---

## 📂 Project Structure

```id="m5d9sw"
privacy-threat-modeling-linddun/
├── README.md
├── docs/
│   └── project-report.pdf
```

---

## 📄 Report

👉 View Full Report:
docs/project-report.pdf

---

## 🧠 Key Insights

* Privacy risks must be considered alongside security
* Data flow analysis is critical for identifying exposure points
* Structured frameworks like LINDDUN enable systematic evaluation
* Distributed systems introduce complex privacy challenges

---

## ⚠️ Limitations

* Based on simulated system environment
* Assumes predefined system architecture
* Real-world deployment may introduce additional variables

---

## 🧠 Perspective

This project reflects my interest in:

* Privacy engineering
* Secure system design
* Risk assessment methodologies
* Data protection in distributed systems

