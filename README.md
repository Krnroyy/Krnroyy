<img src="assets/hardware-header.gif" alt="RTL Design, FPGA and Verification — ECE at IIIT Bhagalpur" width="100%">

# RTL Design · FPGA · Digital Verification

I am an Electronics and Communication Engineering student at IIIT Bhagalpur, building projects in RTL design, FPGA implementation, and verification.

My work includes AXI4-Stream interfaces, hardware encryption on ZCU104, and transistor-level CMOS design using Cadence Virtuoso.

[![Portfolio](https://img.shields.io/badge/Portfolio-136F63?style=flat-square)](https://krnroyy.github.io/responsive-personal-portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square)](https://www.linkedin.com/in/krnroyy/)
[![FIFO CI](https://github.com/Krnroyy/axi4-stream-fifo/actions/workflows/verify.yml/badge.svg?branch=master)](https://github.com/Krnroyy/axi4-stream-fifo/actions/workflows/verify.yml)

## Selected Projects

### AES-GCM Hardware Accelerator — ZCU104

Custom Verilog accelerator integrated with AXI DMA and Cortex-A53 software, with Python reference verification.

- Documented board tests: 11/11 ciphertext and authentication-tag matches against Python AESGCM.
- Modified ciphertext rejected in all 11 documented tamper tests.
- Compared CTR and GCM implementations for throughput, resource utilization, and timing.

[Repository](https://github.com/Krnroyy/fpga-aes128-gcm-image-encryption) · [Results](https://github.com/Krnroyy/fpga-aes128-gcm-image-encryption/blob/main/RESULTS.md) · [Build instructions](https://github.com/Krnroyy/fpga-aes128-gcm-image-encryption/blob/main/BUILD_AND_RUN.md)

### AXI4-Stream FIFO — Simulation and Formal Verification

Parameterized SystemVerilog beat FIFO preserving TDATA, TKEEP, and TLAST, with scoreboard-based simulation and formal safety checks.

- 12 passing simulation runs across depths 1, 3, 4, and 16.
- Formal base checks and induction passed for an 8-bit, depth-4 configuration under documented assumptions.
- Deliberately injected handshake bug detected by simulation and formal verification.
- Automated simulation and formal checks through GitHub Actions.

[Repository](https://github.com/Krnroyy/axi4-stream-fifo) · [Validation](https://github.com/Krnroyy/axi4-stream-fifo/blob/master/results/VALIDATION.md) · [Bug case study](https://github.com/Krnroyy/axi4-stream-fifo/blob/master/docs/BUG_CASE_STUDY.md)

### CMOS Full Adder — Cadence Virtuoso

Hierarchical 1-bit full adder designed using gpdk180 and simulated with Spectre at 1.8 V.

- Functional simulation across all eight input combinations.
- Output-load characterization from 5 fF to 50 fF.
- Documented propagation-delay measurements, average supply power, schematics, and waveforms.

Scope: schematic-level simulation; physical layout, DRC, and LVS are not included.

[Repository and results](https://github.com/Krnroyy/cadence-cmos-full-adder)

## Technical Toolkit

| Area | Tools and technologies |
|---|---|
| RTL and verification | Verilog, SystemVerilog, Icarus Verilog, GTKWave |
| Formal verification | Yosys/SMTBMC, Z3 |
| FPGA and interfaces | Vivado, Vitis, ZCU104, AXI4-Stream, AXI4-Lite, AXI DMA |
| CMOS design | Cadence Virtuoso, Spectre, gpdk180 |
| Programming and workflow | Python, C/C++, Git, GitHub Actions, WSL Ubuntu |

## Current Focus

Developing my understanding of AXI interfaces, formal properties, and AES-GCM hardware architecture, with an emphasis on reproducible tests and documented results.

Open to internships and entry-level opportunities in RTL design, FPGA development, and design verification.

[Connect on LinkedIn](https://www.linkedin.com/in/krnroyy/)