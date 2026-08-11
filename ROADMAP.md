# 🔱 TRISHUL

## Trusted Reconfigurable Integrated Security Hardware Unit for Lattice Cryptography

TRISHUL is an open-source hardware research project focused on developing a
reconfigurable security-oriented compute architecture, beginning with a
Spartan-7 FPGA prototype and progressing toward ASIC-ready RTL.

---

## Vision

Build a complete hardware research journey:

**Concept → Architecture → RTL → Verification → FPGA → Benchmarking → Research → ASIC**

---

## Primary Hardware Platform

- FPGA: Xilinx Spartan-7
- HDL: SystemVerilog
- FPGA Toolchain: AMD/Xilinx Vivado
- Verification: RTL simulation + Python reference models
- Future ASIC Flow: Open-source RTL-to-GDSII flow

---

## Core Research Direction

TRISHUL will investigate resource-efficient and reconfigurable hardware
architectures for lattice-based cryptographic computation.

The initial research direction will focus on:

- Modular arithmetic
- Polynomial arithmetic
- Number Theoretic Transform (NTT)
- Reconfigurable butterfly architectures
- Memory-efficient datapaths
- Hardware verification
- Built-In Self-Test (BIST)
- FPGA resource/throughput optimization
- ASIC migration

---

## Development Philosophy

Every development day produces a visible engineering artifact.

Each daily milestone follows:

1. Learn
2. Design
3. Implement
4. Verify
5. Measure
6. Document
7. Commit

---

## Long-Term Architecture

```text
                    TRISHUL
                       │
              Reconfigurable
              Security Fabric
                       │
        ┌──────────────┼──────────────┐
        │              │              │
        ▼              ▼              ▼
   Modular Math      NTT/PQC         BIST
        │              │              │
        └──────────────┼──────────────┘
                       │
                       ▼
                  Spartan-7
                       │
                       ▼
               FPGA Benchmarking
                       │
                       ▼
                 ASIC Migration
                       │
                       ▼
                    GDSII
