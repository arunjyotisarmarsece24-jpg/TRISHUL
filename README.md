# 🔱 TRISHUL

## Trusted Reconfigurable Integrated Security Hardware Unit for Lattice Cryptography

> **An open-source hardware research project developing a parameterized, reconfigurable cryptographic compute architecture — from RTL to Spartan-7 FPGA implementation and, ultimately, ASIC-oriented design.**

---

## Overview

TRISHUL is an incremental hardware architecture project focused on the design, verification, implementation, and evaluation of reconfigurable hardware for lattice-based cryptographic computation.

The project starts from fundamental digital and modular arithmetic building blocks and progressively develops them into a complete accelerator architecture.

The primary implementation target is a **Xilinx Spartan-7 FPGA**.

The long-term objective is to establish a reproducible hardware-development path from:

```text
Specification
     ↓
Architecture
     ↓
Microarchitecture
     ↓
RTL
     ↓
Verification
     ↓
FPGA Implementation
     ↓
Measurement
     ↓
Architectural Optimization
     ↓
ASIC-Oriented RTL
     ↓
Physical Design
     ↓
GDSII
