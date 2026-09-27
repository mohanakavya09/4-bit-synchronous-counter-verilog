# 4-Bit Synchronous Counter using Verilog HDL

## Overview

This project implements a 4-bit synchronous up counter using Verilog HDL.

The counter changes its output state on the rising edge of the clock. A reset input is provided to initialize the counter to zero.

## Features

- 4-bit synchronous counter
- Verilog HDL implementation
- Positive-edge triggered clock
- Synchronous reset
- Counts from 0 to 15
- Includes a Verilog testbench for simulation

## Working

The counter receives a clock signal and reset signal as inputs.

When reset is active, the counter output is set to:

0000

When reset is inactive, the counter increments by one on every rising edge of the clock.

After reaching:

1111

the counter rolls over to:

0000

## Files

| File | Description |
|------|-------------|
| `counter_4bit.v` | Main 4-bit synchronous counter design |
| `counter_4bit_tb.v` | Testbench used to verify the counter |

## Tools & Technologies

- Verilog HDL
- Digital Logic Design
- RTL Design
- Simulation

## Learning Outcome

This project demonstrates basic RTL design concepts, sequential logic, clocked processes, reset operation, and Verilog testbench development.
