# Ultra-Low-Power High-PSRR Sub-1V Voltage Reference

## Project Overview
Design and simulation of an ultra-low-power, high Power Supply Rejection Ratio (PSRR) sub-1V voltage reference circuit using 180nm CMOS technology in LTspice.

This project is based on the IEEE research paper:

"Ultra-Low-Power High PSRR Sub-1 V Voltage Reference Circuit in 22 nm FDSOI CMOS."

## Tools Used
- LTspice
- 180nm CMOS Technology

## Circuit Architecture
The design consists of the following sections:
- Startup Circuit
- Current Reference Circuit
- CTAT Generator
- Voltage Divider
- PTAT Generator
- Low-Pass Filter

## Simulation Results
- Reference Output Voltage: Approximately 504 mV
- Supply Voltage: 0–1.8 V
- Temperature Analysis: -40°C to 120°C
- Process/Sample Variation Analysis: 17 samples

## Repository Structure
- `LTspice/` – Circuit schematic
- `Documentation/` – Project report

## Reference
A. Dossanov, C. Ziegler, and V. Issakov, "Ultra-Low-Power High PSRR Sub-1 V Voltage Reference Circuit in 22 nm FDSOI CMOS," IEEE Transactions on Circuits and Systems II: Express Briefs, 2024.

