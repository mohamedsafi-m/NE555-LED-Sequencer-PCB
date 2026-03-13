# NE555 LED Sequencer PCB

A PCB-based LED sequencing circuit built using two NE555 timer ICs.  
The circuit generates oscillating signals to drive multiple LEDs in a pattern.

## Overview

This project implements an LED sequencing circuit using two NE555 timers.
One timer generates the clock signal, while the second timer controls the LED switching pattern.

The design was created as part of a hands-on learning exercise in:

- Analog electronics
- Timer circuits
- PCB design
- KiCad schematic and layout
## Features

- Dual NE555 timer based circuit
- LED sequencing effect
- Custom designed PCB
- Simple analog timing control
- Easy to assemble with through-hole components

## Circuit Description

The circuit consists of two NE555 timer ICs:

Timer 1 (Astable Mode)
- Generates a clock signal
- Frequency controlled using resistor R1 and capacitor C1

Timer 2
- Uses the clock signal to drive LED outputs

LED arrays are arranged on both sides of the PCB to create a visual sequencing pattern.
## How to Use

1. Open the project in KiCad
2. Review the schematic and PCB layout
3. Generate Gerber files
4. Send them to a PCB manufacturer
5. Assemble the components
6. 
