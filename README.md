# PLC-Based Smart Railway Level Crossing Control System

## Description
Simulation of an automated railway gate control system using PLC ladder logic with timers, safety interlocks and emergency stop.

## Problem Statement
Design and simulate a PLC-based Smart Railway Level Crossing Control System using ladder logic to automate railway gate operation for safe road and rail traffic management.

## Sequence of Operation
1. System starts → Gate open, green signal ON  
2. Entry sensor detects train → Timer T1 starts  
3. After delay → Buzzer ON, red signal ON, gate closes  
4. Train passes → Gate remains closed  
5. Exit sensor detects train → Timer T2 starts  
6. After delay → Gate opens, green signal ON, red signal OFF
   
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

### Ladder Diagram
![Ladder Diagram](https://github.com/user-attachments/assets/62ab9170-3d24-420c-9151-90edc5183347)
