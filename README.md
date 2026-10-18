<h1 align="center">Hi, I'm Karan Kumar</h1>

<h3 align="center">RTL Design | FPGA Development | Hardware Verification</h3>

<p align="center">
ECE final-year student at IIIT Bhagalpur<br>
Building digital hardware and making its behaviour verifiable.
</p>

<p align="center">
<a href="https://krnroyy.github.io/responsive-personal-portfolio/"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-Visit-136F63?style=for-the-badge"></a>
<a href="https://github.com/Krnroyy"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-Krnroyy-181717?style=for-the-badge&logo=github&logoColor=white"></a>
</p>

---

## About Me

- Interested in RTL design, functional and formal verification, and secure hardware.
- Working with Verilog/SystemVerilog, FPGA toolchains, and Python.
- Exploring FIFO design, AXI handshakes, assertions, and reference-model checking.
- Open to internships, entry-level opportunities, and engineering collaboration.

## Featured Projects

| Project | Engineering Focus | Evidence |
|---|---|---|
| [AXI4-Stream FIFO](https://github.com/Krnroyy/axis-packet-fifo) | SystemVerilog beat FIFO, scoreboard simulation, formal safety checks | [Validation](https://github.com/Krnroyy/axis-packet-fifo/blob/master/results/VALIDATION.md), [bug case study](https://github.com/Krnroyy/axis-packet-fifo/blob/master/docs/BUG_CASE_STUDY.md), [waveform](https://github.com/Krnroyy/axis-packet-fifo#backpressure-waveform) |
| [FPGA AES-128-GCM Image Security](https://github.com/Krnroyy/FPGA-AES128-CTR-Image-Encryption) | ZCU104 accelerator, AXI DMA, Cortex-A53 integration, Python reference checks | [Measured results](https://github.com/Krnroyy/FPGA-AES128-CTR-Image-Encryption/blob/main/RESULTS.md) |
| [CMOS Full Adder](https://github.com/Krnroyy/cadence-cmos-full-adder) | Hierarchical CMOS design using gpdk180 and Spectre | Schematics, eight-state verification, and load characterization in the repository |

## Technical Toolkit

### RTL and Verification

![Verilog](https://img.shields.io/badge/Verilog-235789?style=for-the-badge)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-654EA3?style=for-the-badge)
![Icarus Verilog](https://img.shields.io/badge/Icarus_Verilog-345995?style=for-the-badge)
![GTKWave](https://img.shields.io/badge/GTKWave-136F63?style=for-the-badge)
![Yosys](https://img.shields.io/badge/Yosys_SMTBMC-3A506B?style=for-the-badge)
![Z3](https://img.shields.io/badge/Z3-8F3985?style=for-the-badge)

### FPGA and Circuit Design

![Vivado](https://img.shields.io/badge/Vivado-C74634?style=for-the-badge)
![Vitis](https://img.shields.io/badge/Vitis-9E2A2B?style=for-the-badge)
![Virtuoso](https://img.shields.io/badge/Cadence_Virtuoso-235789?style=for-the-badge)
![Spectre](https://img.shields.io/badge/Spectre-136F63?style=for-the-badge)

### Programming and Interfaces

**Programming:** Python, C, C++  
**Interfaces:** AXI4-Stream, AXI4-Lite, AXI DMA  
**Environment:** Windows, WSL Ubuntu, Git, GitHub Actions

## Verification in Action

[![FIFO verification](https://github.com/Krnroyy/axis-packet-fifo/actions/workflows/verify.yml/badge.svg?branch=master)](https://github.com/Krnroyy/axis-packet-fifo/actions/workflows/verify.yml)

The FIFO project documents:
- Simulation across depths 1, 3, 4, and 16.
- Formal safety checks for an 8-bit, depth-4 configuration.
- A pop-without-ready mutation detected by simulation and formal.
- Output stability during backpressure, illustrated with a waveform.

Formal results apply to the documented configuration and harness assumptions.

## Currently Learning

- AXI4-Stream backpressure and AXI4-Lite register interfaces.
- FIFO pointers, occupancy, reset behaviour, and boundary conditions.
- Assertions, assumptions, cover properties, and induction.
- AES-GCM architecture and FPGA hardware/software integration.

---

<p align="center">
<a href="https://krnroyy.github.io/responsive-personal-portfolio/">Explore my engineering portfolio</a>
</p>