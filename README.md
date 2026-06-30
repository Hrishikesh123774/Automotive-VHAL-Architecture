# Automotive VHAL Architecture Emulation

## Overview
This repository contains a lightweight architectural simulation of an Android Automotive OS (AAOS) Vehicle Hardware Abstraction Layer (VHAL) built in C++. It demonstrates the foundational logic required to bridge automotive software with physical vehicle hardware.

## Key Features
* **AOSP Property Mapping:** Models register-level configurations mapping Android Open Source Project (AOSP) property frameworks to low-level hardware actuator responses (specifically HVAC climate systems).
* **Hardware Concurrency:** Implements realistic concurrency structures to mimic micro-controller ADC sensor streams and real-time physical vehicle telemetry changes.

## How to Run
This simulation can be compiled and executed using any standard C++ compiler (C++14 or newer) or run directly via online C++ environments like OnlineGDB.
