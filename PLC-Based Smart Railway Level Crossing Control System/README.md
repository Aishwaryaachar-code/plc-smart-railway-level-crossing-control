# PLC-Based Smart Railway Level Crossing Control System

## Description
Simulation of an automated railway gate control system using PLC ladder logic with timers, safety interlocks and emergency stop.

## Problem Statement

Design and simulate a PLC-based Smart Railway Level Crossing Control System using ladder logic to automate railway gate operation for safe road and rail traffic management.

The system shall satisfy the following conditions:

1. The system shall start using a Start push button and remain latched until Stop or Emergency Stop is pressed.

2. Under normal conditions:
- Railway gate remains open.
- Green road signal remains ON.

3. When a train is detected by the Entry Sensor:
- Timer T1 starts.
- After the preset delay:
  - Warning buzzer activates
  - Red signal turns ON
  - Green signal turns OFF
  - Railway gate closes automatically

4. While the train is passing, the gate remains closed.

5. When the train reaches the Exit Sensor:
- Timer T2 starts.
- After the preset delay:
  - Railway gate opens automatically
  - Red signal turns OFF
  - Green signal turns ON

6. The system includes safety interlocking and emergency stop logic.

## Inputs
- Start
- Stop
- Entry Sensor
- Exit Sensor
- Emergency Stop

## Outputs
- Railway Gate Open
- Railway Gate Close
- Green Signal
- Red Signal
- Buzzer

## Features
- Start/Stop latch control
- Timer-based gate closing and opening
- Safety interlocking
- Emergency stop logic

## Software Used
- PLC Ladder Simulator Online
  
## Simulation Output
 ![Ladder Diagram](images/ladder_diagram.png)
