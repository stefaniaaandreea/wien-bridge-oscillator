# Wien Bridge Oscillator

Design and simulation of an RC Wien Bridge Oscillator using OrCAD and PSpice.

## Description

This project presents the design and simulation of a Wien Bridge Oscillator circuit.
The oscillator generates a sinusoidal signal and allows frequency adjustment within a specified range.
The circuit was designed and simulated using OrCAD and includes analysis of frequency response, transient behavior, DC sweep and temperature variation.

## Design Specifications

* Adjustable oscillation frequency: **14.5 – 87 kHz**
* Output load: **RL = 29 kΩ**
* Output oscillation amplitude: **0.46 V**
* Automatic amplitude control using **JFET**
* Operating temperature range: **0°C – 70°C**
* Power supply presence indicated using **LED**

## Circuit Schematic

![Circuit Schematic](schema.jpg)

## Block Diagram

![Block Diagram](diagrama.png)

## Frequency Response

Maximum frequency:

![Frequency Max](frecv_max.png)

Minimum frequency:

![Frequency Min](frecv_min.png)

## Transient Analysis

Maximum frequency transient response:

![Transient Max](transient_frecv_max.png)

Minimum frequency transient response:

![Transient Min](transient_frecv_min.png)

## Temperature Analysis

![Temperature Analysis](temperaturi.png)

## DC Sweep Analysis

![DC Sweep](DC_Sweep.png)

## Amplification Stage

![Amplification](amplificare.png)

## PCB Layout

![PCB Layout](layout_placa.jpg)

## Tools Used

* OrCAD Capture
* PSpice Simulation

## Author

Vaicar Stefania-Andreea
Electronics and Telecommunications Student
University POLITEHNICA of Bucharest
