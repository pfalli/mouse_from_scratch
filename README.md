# 🖱️ DIY Wireless Mouse – Built From Scratch

> A personal hardware and embedded systems project where I design and build a fully functional wireless computer mouse from individual electronic components.

---

# Overview

This project is my journey into **embedded systems**, **electronics**, and **hardware design** by creating a wireless mouse completely from scratch.

Instead of modifying an existing mouse, the goal is to understand every layer of how a modern mouse works:

* Electronics
* PCB wiring
* Microcontrollers
* USB HID protocol
* Wireless communication
* Power management
* Firmware development
* Mechanical design

The final result should be a custom mouse that behaves like any commercial mouse while being entirely designed and assembled by me.

---

# Goals

* Learn practical electronics
* Improve soldering skills
* Learn embedded C/C++
* Understand USB HID devices
* Learn wireless communication
* Design a rechargeable battery system
* Create custom firmware
* Build a complete product from individual components

---

# Features (Planned)

* Left / Right click
* Scroll wheel
* DPI adjustment button
* Wireless communication
* Rechargeable battery
* USB charging
* Power saving mode
* Custom firmware
* 3D printed enclosure
* LED status indicator

---

# Technologies

### Hardware

* Arduino Pro Micro (ATmega32U4)
* Optical mouse sensor
* Micro switches
* Rotary encoder (scroll wheel)
* Li-Ion battery
* TP4056 charging module
* Voltage regulator
* NRF24L01 wireless transceiver *(or another wireless module depending on testing)*

---

### Software

* C++
* Arduino Framework
* Embedded Programming
* USB HID
* Serial debugging

---

# Project Architecture

```text
              ┌────────────────────┐
              │      Computer      │
              └─────────┬──────────┘
                        │
                  USB Receiver
                        │
                 Wireless Signal
                        │
         ┌──────────────┴─────────────┐
         │                            │
         │    Arduino Pro Micro       │
         │                            │
         ├──────────────┬─────────────┤
         │              │             │
      Buttons      Scroll Wheel   Optical Sensor
         │              │             │
         └──────────────┴─────────────┘
                    Firmware
                        │
                Battery Management
                        │
               Rechargeable Battery
```

---

# Components

| Component         | Purpose                |
| ----------------- | ---------------------- |
| Arduino Pro Micro | Main microcontroller   |
| Optical Sensor    | Detect mouse movement  |
| Micro Switches    | Left and right click   |
| Rotary Encoder    | Mouse wheel            |
| NRF24L01          | Wireless communication |
| Li-Ion Battery    | Power source           |
| Charging Module   | USB battery charging   |
| Voltage Regulator | Stable power supply    |

---

# What I Want to Learn

This project is less about building a mouse and more about learning how embedded devices are engineered.

Topics include:

* Reading datasheets
* Digital electronics
* GPIO programming
* Interrupts
* SPI communication
* USB HID implementation
* Wireless protocols
* Battery management
* Power optimization
* PCB prototyping
* Embedded debugging

---

# Challenges

Some of the biggest challenges include:

* Integrating the optical sensor
* Reliable wireless communication
* Reducing power consumption
* Battery charging safety
* Compact hardware layout
* Firmware optimization
* Mechanical assembly

---

# Current Progress

* ✅ Project planning
* ✅ Components selected
* ✅ Development environment prepared
* 🔄 Electronics prototyping
* ⏳ Firmware development
* ⏳ Wireless communication
* ⏳ PCB prototyping
* ⏳ Final enclosure

---

# Why I Built This

As a software developer, I wanted to move beyond writing code and better understand the hardware that software ultimately controls.

Building a mouse from scratch combines multiple engineering disciplines—including embedded programming, electronics, communication protocols, and product design—making it an excellent hands-on project to strengthen my skills in embedded systems and low-level software development.

Rather than relying on prebuilt modules, my objective is to understand **how every component works, how they interact, and how commercial devices are engineered**, while documenting the entire process from concept to a working prototype.

---

# Future Improvements

* Bluetooth Low Energy support
* Custom PCB design
* STM32-based version
* Higher polling rate
* RGB lighting
* Adjustable DPI profiles
* USB-C charging
* Dedicated desktop configuration software
* Battery level reporting
* Ergonomic 3D-printed shell

---

## Repository Purpose

This repository documents the complete development process—from the first prototype to the final product—including hardware selection, circuit design, firmware implementation, testing, challenges, and lessons learned. The goal is not only to build a functional wireless mouse but also to demonstrate practical skills in embedded systems engineering, electronics, and hardware-software integration for future projects and professional development.
