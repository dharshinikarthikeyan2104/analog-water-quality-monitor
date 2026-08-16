# System Design

## Project Overview

The Analog Water Quality Monitor is a proposed low-cost electronic system
designed to monitor the pH level of water using an analog pH sensor.

## Objective

The main objective is to convert the pH sensor output into an electrical
signal that can be processed and represented using a simple indicator system.

## Block Diagram

pH Sensor
↓
Signal Conditioning
↓
Reference / Comparison
↓
LED Indicator

## Working Principle

1. The pH sensor detects the hydrogen-ion activity of the water.
2. The sensor produces an analog electrical signal.
3. The signal is conditioned using an operational amplifier.
4. The conditioned signal is compared with predefined reference levels.
5. LEDs indicate different pH ranges.

## Proposed pH Indication

| pH Range | Indication |
|---|---|
| Acidic | Red LED |
| Near Neutral | Yellow LED |
| Alkaline | Green LED |

## Current Status

This is currently a design and documentation project.
The proposed circuit has not been physically tested.

## Future Improvements

- Add an LCD display
- Add temperature compensation
- Add additional water-quality parameters
- Develop a PCB
- Perform laboratory testing
## Block Diagram

The following block diagram shows the proposed signal flow of the system.

![System Block Diagram](block-diagram.png)
