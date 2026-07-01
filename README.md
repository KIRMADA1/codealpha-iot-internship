# CodeAlpha IoT Internship Submissions 🌐

Welcome to my official repository for the **CodeAlpha Internet of Things (IoT) Internship** cohort (June 2026). This repository serves as a structured portfolio containing all my verified submissions, technical documentation, hardware schematics, and simulation code.

## 📊 Project Index & Repository Directory

The repository is organized into distinct milestone folders for easy navigation and grading:

| Task Milestone | Project Name & Objective | Deliverables | 
| :--- | :--- | :--- | 
| **Task 1** | IoMT Architectures for Real-Time Patient Monitoring | Technical Research Report (PDF) | 
| **Task 2** | Temperature-Activated Alert System | Arduino Source Code (`.ino`) & Tinkercad Simulation | 
| **Task 3** | Smart PIR Motion Detection Alarm System | Embedded C Firmware (`main.c`), Compiled Binary (`.hex`), & Proteus 8.13 Schematic | 

---

## 📁 Deep-Dive Project Breakdowns

### 📑 Task 1: Healthcare Monitoring (IoMT) Architecture Report
* **Objective:** Author a comprehensive 800-1000 word engineering research paper detailing the Internet of Medical Things (IoMT) multi-tier processing frameworks.
* **Key Focus Areas:** * Three-Tier System Topology: Perception Layer ➡️ Local Edge Gateway Layer ➡️ HIPAA-Compliant Cloud Analytics Layer.
  * Mathematical model for edge-node low-power management metrics:
    $$\text{Average Power Consumption} = \frac{(I_{\text{active}} \times t_{\text{active}}) + (I_{\text{sleep}} \times t_{\text{sleep}})}{t_{\text{active}} + t_{\text{sleep}}}$$
  * Common-Mode Rejection Ratio ($CMRR$) analysis for microvolt-level biosensor signal integrity.
* **System Topology Diagram:**
  


---

### 🌡️ Task 2: Temperature-Activated Smart Alert System (Tinkercad)
* **Objective:** Design an interactive embedded control circuit that samples environmental temperature telemetry and initiates prioritized sensory overrides when critical safety limits are breached.
* **Hardware Architecture Stack:**
  * **Processing Core:** Arduino Uno R3 (ATmega328P)
  * **Telemetry Sensors:** Analog TMP36 Temperature Sensor
  * **Output Indicators:** Piezo Buzzer, High-Efficiency Red LED, and a 16x2 Parallel Character LCD Unit.
* **Functional Logic:** Reads transient ambient voltages, converts analog signals to Celsius scales, maps dynamic messages to the LCD, and sounds a persistent audio/visual alarm if thresholds pass safety limits.

---

### 🚨 Task 3: 8051 Smart Motion Detection Prototype (Keil + Proteus)
* **Objective:** Construct a complete microcontroller hardware circuit running custom-compiled bare-metal C firmware to process digital logic inputs from an infrared security array.
* **Hardware Architecture Stack:**
  * **Processing Core:** AT89C51 Microcontroller
  * **Sensors & Inputs:** PIR Motion Sensor via simulated `LOGICSTATE` digital toggles.
  * **Actuators:** Industrial Piezo Sounder & Red Alert Indicator LED driven via GPIO switching.
* **Software Stack & Binary Compilation:**
  * Firmwae written in industry-standard Embedded C inside the **Keil uVision IDE**.
  * Complete target build configurations compiled using the `BL51` Linker to produce a clean, error-free production binary file: **`lcd_proect.hex`**.
  * Hex runtime flashed directly into the microcontroller internal flash space inside **Proteus 8.13** for real-time validation.

---

## 🛠️ Tools, IDEs, and Ecosystems Used
* **Firmware Development:** Keil uVision IDE (Embedded C for 8051 Core Architecture)
* **Circuit Modeling & Hardware Simulation:** Proteus Design Suite 8.13 & Autodesk Tinkercad
* **Technical Writing:** Microsoft Word Equation Editor (LaTeX Formatting Standards)
* **Version Control:** GitHub Web Workspaces & Git SCM

---

## 👤 Intern Information
* **Name:** Arjun Rathod
* **Email:** engineerarjun0@gmail.com
* **Domain:** Internet of Things (IoT) Engineering
* **Organization:** CodeAlpha Training & Development

---
*Note: All files within this repository are the exclusive properties of the author, submitted in partial fulfillment of the CodeAlpha Technical Curriculum requirements.*
