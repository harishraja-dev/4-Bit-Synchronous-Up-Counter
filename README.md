# 4-Bit-Synchronous-Up-Counter
4-bit synchronous up counter designed using J-K flip-flops in DSCH v3 and Microwind v3.


This project demonstrates the design and simulation of a 4-bit synchronous up counter using J-K flip-flops.

The complete design was implemented using DSCH v3 and Microwind v3 as part of an Integrated Circuit Design project.

## Project Overview

A synchronous counter is a sequential circuit where all flip-flops are driven using a common clock signal. Unlike asynchronous counters, synchronous counters reduce propagation delay and support higher operating frequencies.

This project includes:
- D Flip-Flop design
- J-K Flip-Flop implementation using D Flip-Flops
- 4-Bit Synchronous Up Counter
- Timing analysis and waveform verification

## Software Used

- DSCH v3
- Microwind v3

## Components Used

- D Flip-Flops
- J-K Flip-Flops
- NAND Gates
- AND Gates
- OR Gates
- NOT Gates
- Clock Pulse Generator
- LED Outputs

## Working Principle

The least significant flip-flop toggles on every clock pulse, while higher-order flip-flops toggle only when all previous outputs are HIGH.

The counter follows a binary counting sequence:

0000 → 0001 → 0010 → ... → 1111

## Features

- Synchronous operation
- Reduced propagation delay
- Timing waveform analysis
- Digital VLSI circuit design

## Results

The counter successfully counted from 0000 to 1111 using a common clock signal. Timing diagrams and Microwind simulations verified the correct operation of the circuit.

## Files Included

- Project Report
- DSCH Simulation
- Microwind Layout
- Timing Waveforms
- Presentation Slides

## Author

Harish Raja  
ECE Undergraduate, VNIT Nagpur
