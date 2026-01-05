Smart Solar and Wind Hybrid Object Monitoring System

A renewable-energy-powered monitoring system that uses infrared sensors to detect objects in real time. The system is powered by a hybrid solar and wind energy setup, stores energy in a lithium-ion battery, and provides immediate visual alerts through LED indicators. System behavior and sensor states can be observed via serial monitoring.

Features

Hybrid solar and wind power integration

Real-time object detection using infrared sensors

Visual status indication using LEDs

High-alert mode when multiple detections occur

Energy storage using a lithium-ion battery

Continuous system monitoring through serial output

Hardware Requirements

Microcontroller (Arduino Nano or equivalent)

Solar panel

Wind turbine generator

Lithium-ion battery (18650)

Charging and protection module

DC-DC buck/boost converter

Infrared sensors

Red and green LEDs

Current-limiting resistors

Power switch

Jumper wires and power supply

(Component names only; no specific brands required.)

Wiring Overview

Solar panel and wind turbine feed the charging module

Battery stores harvested energy

Buck/boost converter regulates voltage for the microcontroller

Infrared sensors connect to dedicated digital input pins

LEDs connect to digital output pins through resistors

All components share a common ground reference

Proper grounding is required to prevent unstable behavior and unexpected resets.

Installation

Clone or download this repository

Open the project folder in your Arduino development environment

Connect all hardware components according to the wiring overview

Upload the program to the microcontroller

Open the Serial Monitor to observe sensor readings and system status

Test object detection and LED indicators

System Operation

Renewable energy is harvested from solar and wind sources

Power is stored in a lithium-ion battery

The microcontroller continuously monitors IR sensor inputs

LEDs indicate detection status in real time

A high-alert visual response is activated when multiple sensors detect objects

License

This project is open-source and intended for educational and experimental use.
You are free to modify, improve, and expand the system.
