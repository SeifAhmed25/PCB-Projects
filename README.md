# Seif Ahmed - PCB Design Portfolio

This repository showcases my practical work in **PCB design**, focusing on **schematic creation**, **PCB layout**, and **manufacturing optimization** using **KiCad** software.

Projects are arranged from **latest to oldest**.

**Tools & Skills:**  
KiCad • Circuit Design • PCB Layout • DRC/ERC Checks • Soldering • Git Version Control • Documentation

---

## MCU Datalogger

**Goal:**  
Design a printed circuit board for a microcontroller-based data logger using the **ATmega328P-AU**, supported by two **EEPROMs** and a **real-time clock (RTC)**.

**Key Features:**
- Designed in two versions: a **2-layer** and a **4-layer** PCB, both managed using **Git** version control.  
- The **ATmega328P-AU** acts as the central controller.  
- Handles communication with the **RTC** and **EEPROM** modules.  
- Includes indicator LEDs and a reset circuit for the microcontroller.

**Main Components:**
- ATmega328P-AU  
- Crystal oscillator  
- Battery  
- Capacitors (decoupling)  
- Resistors  

**Project Pictures:**  
- **Board Schematic**  
  ![Board Schematic](Boards_Pics/MCU%20Datalogger%20Sch.png)  
- **Board Layout**  
  ![Board Layout](Boards_Pics/MCU%20Datalogger%20Layout.png)  
- **Board Top View**  
  ![Board Top View](Boards_Pics/MCU%20Datalogger%20Topview.png)  
- **Board Back View**  
  ![Board Back View](Boards_Pics/MCU%20Datalogger%20Backward.png)

---

## Solar Power Supply PCB

**Goal:**  
Design and implement a PCB that delivers a **regulated 3.3 V output** from a **solar panel**, functioning as a **solar energy regulator module**.  
This circuit was originally designed by *Elektor Magazine* and reimplemented in **KiCad**.

**Key Features:**
- Converts unregulated solar panel voltage into regulated **3.3 V**.  
- Suitable for powering **microcontrollers and sensors**.  
- Includes **copper fills** and a mix of **THT and SMD components**.

**Main Components:**
- Male connectors  
- Protection diodes  
- Inductor (switching regulator)  
- DC-DC converter  
- Resistors  

**Project Pictures:**  
- **Board Schematic**  
  ![Board Schematic](Boards_Pics/Solar%20Supply%20Schm.png)  
- **Board Top View**  
  ![Board Top View](Boards_Pics/Solar%20Supply%20Board%20Topview.png)  
- **Board Back View**  
  ![Board Back View](Boards_Pics/Solar%20Supply%20Board%20Backward.png)

---

## Breadboard Power Supply PCB

**Goal:**  
Design a compact PCB that plugs directly into a **breadboard** and provides **5 V** and **3.3 V** regulated outputs.

**Key Features:**
- Fits perfectly on a standard breadboard.  
- Provides both **5 V** and **3.3 V** outputs.  
- Includes an **on/off switch** and **copper fills**.  
- Assembled using **THT components** for ease of soldering.

**Main Components:**
- Capacitors  
- LED  
- Jack connector  
- Screw terminals  
- Male connectors  
- Resistors  
- Slide switch  
- Voltage regulators  

**Project Pictures:**  
- **Board Schematic**  
  ![Board Schematic](Boards_Pics/BreadBoard%20Power%20Supply%20Sch.png)  
- **Board Top View**  
  ![Board Top View](Boards_Pics/BreadBoard%20Power%20Supply%20Topview.png)  
- **Board Back View**  
  ![Board Back View](Boards_Pics/BreadBoard%20Power%20Supply%20Backward.png)

---

## LED Torch PCB

**Goal:**  
An introductory project for learning **KiCad** fundamentals through schematic capture, PCB layout, and basic 3D visualization.

**Key Features:**
- Simple LED lighting circuit.  
- Demonstrates PCB routing and footprint placement.  
- Serves as a base for learning design rules and 3D viewer tools.

**Main Components:**
- Battery  
- Switch  
- Resistor  
- LED  

**Project Pictures:**  
- **Board Top View**  
  ![Board Top View](Boards_Pics/PCB%20LED%20Torch%20Board%20Topview.png)  
- **Board Back View**  
  ![Board Back View](Boards_Pics/PCB%20LED%20Torch%20Board%20Backward.png)

---

**Author:** Seif Ahmed  
**Contact:** [Email](mailto:seif7760@gmail.com)  
**Software Used:** KiCad 9.0
