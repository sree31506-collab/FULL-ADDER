# Full Adder in Verilog

## Overview
This project implements a 1-bit Full Adder in Verilog.

A Full Adder adds three binary inputs:
- A
- B
- Carry-in (Cin)

It produces:
- Sum
- Carry-out (Cout)

## Files

- full_adder.v - Full Adder design
- full_adder_tb.v - Testbench
- simulation.png - Simulation waveform

## Logic Equations

Sum = A ^ B ^ Cin

Cout = (A & B) | (B & Cin) | (A & Cin)

## Truth Table

|A|B|Cin|Sum|Cout|
|--|--|---|---|----|
|0|0|0|0|0|
|0|0|1|1|0|
|0|1|0|1|0|
|0|1|1|0|1|
|1|0|0|1|0|
|1|0|1|0|1|
|1|1|0|0|1|
|1|1|1|1|1|

## Tools Used

- Verilog HDL
- Icarus Verilog / ModelSim / Vivado
- GTKWave (optional)

## Author

Your Name