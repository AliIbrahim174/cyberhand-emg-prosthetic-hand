# CyberHand — EMG-Controlled Prosthetic Upper Limb

A low-cost **EMG-controlled prosthetic upper-limb prototype** designed to support individuals with upper-limb loss through an affordable, customizable, and embedded biomedical device solution.

CyberHand uses **EMG muscle-signal sensing**, an **Arduino-based control system**, motor actuation, and a **3D-printed mechanical structure** to demonstrate how biomedical engineering, embedded systems, and assistive technology can be combined into a functional prosthetic prototype.

---

## Overview

CyberHand was built as an assistive technology prototype focused on making prosthetic upper-limb solutions more accessible and adaptable.

The system reads muscle activity through an EMG sensor, processes the signal through an Arduino-based embedded control unit, and uses motor actuation to produce prosthetic hand movement.

The project was developed as an individual engineering project and later competed in the **Egypt IoT & AI Challenge**, where it won **Best Prototype Award** and ranked **4th place** after multiple filtration stages among 1000+ participants.

---

## Problem Statement

Advanced prosthetic limbs are often expensive, difficult to customize, and inaccessible for many users.

CyberHand explores a lower-cost alternative by combining:

* EMG-based muscle-signal control
* Embedded motor control
* 3D-printed mechanical parts
* Affordable electronic components
* Customizable prosthetic structure

The goal is to demonstrate a practical prototype that can support future development in **assistive technology**, **prosthetics**, and **rehabilitation engineering**.

---

## Key Features

* EMG-based muscle signal detection
* Arduino-based embedded control logic
* Motor-driven prosthetic movement
* 3D-printed lightweight structure
* Low-cost prototype design
* Customizable prosthetic form factor
* Portable battery-powered concept
* Individual end-to-end development: hardware, software, prototype structure, and documentation

---

## My Role

This was an individual project.

My responsibilities included:

* Designing the project concept
* Building the hardware connections
* Writing the embedded control code
* Integrating the EMG sensor with the control system
* Connecting motors and motor driver circuitry
* Designing and assembling the prosthetic structure
* Preparing the technical and business documentation
* Presenting the project in the Egypt IoT & AI Challenge

---

## System Architecture

```text
Muscle Signal
     ↓
EMG Sensor
     ↓
Arduino-Based Controller
     ↓
Signal Processing / Threshold Logic
     ↓
Motor Driver Circuit
     ↓
Motors
     ↓
Prosthetic Hand Movement
```

---

## Hardware Components

* Arduino-based microcontroller
* EMG sensor
* Motors
* Motor driver circuit
* Battery / power source
* 3D-printed prosthetic structure
* Wires and connectors
* Mechanical joints and support parts

---

## Software / Control Logic

The embedded logic was responsible for:

* Reading EMG signal input
* Detecting muscle activation levels
* Applying threshold-based control
* Sending control signals to the motor driver
* Activating prosthetic movement based on muscle activity

---

## Tech Stack

| Category                | Tools / Components                                    |
| ----------------------- | ----------------------------------------------------- |
| Biomedical Signal Input | EMG sensor                                            |
| Embedded Control        | Arduino-based microcontroller                         |
| Actuation               | Motors, motor driver                                  |
| Fabrication             | 3D printing                                           |
| Programming             | Embedded C / Arduino-style control logic              |
| Project Area            | Prosthetics, Assistive Technology, Biomedical Devices |

---

## Achievements

* Won **Best Prototype Award** in the Egypt IoT & AI Challenge
* Ranked **4th place** after multiple filtration stages
* Competed among **1000+ participants**
* Developed as a complete individual project from concept to prototype and documentation

---

## Potential Applications

* Assistive prosthetic devices
* Rehabilitation engineering prototypes
* Educational biomedical device development
* Low-cost prosthetic design research
* Embedded systems applications in healthcare
* Human-machine interface prototyping

---

## Project Impact

CyberHand demonstrates how affordable embedded systems and biomedical sensing can be used to build accessible assistive technology prototypes.

The project helped me gain hands-on experience in:

* Biomedical device prototyping
* EMG signal-based control
* Embedded systems
* Hardware integration
* 3D-printed mechanical design
* Assistive technology development
* Engineering presentation and competition-based product development

---

## Repository Structure

Add or update this section based on the final repository files.

Recommended structure:

```text
cyberhand-emg-prosthetic-hand/
  README.md
  code/
    cyberhand_control.ino
  docs/
    technical-documentation.pdf
    business-model.pdf
  hardware/
    circuit-diagram.png
    component-list.md
```

---

## Future Improvements

* Improve EMG signal filtering and calibration
* Add multiple grip modes
* Improve mechanical durability
* Add more precise motor control
* Reduce prototype size and weight
* Improve battery management
* Add user-specific calibration
* Explore machine learning-based signal classification

---

## License

This repository is currently shared for academic and portfolio purposes.

If this project is extended for public reuse, a formal open-source license such as MIT, BSD-3-Clause, or CERN-OHL should be added depending on the final hardware/software release plan.
