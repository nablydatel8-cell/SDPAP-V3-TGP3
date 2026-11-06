# SDPAP V3 TGP: Sub-nanosecond Balanced Ternary Memristive Computational Architecture

## 1. Abstract & System Overview
The Sub-nanosecond Balanced Ternary Memristive Computational Architecture (SDPAP V3 TGP) is an open hardware and cryptographic specification establishing a high-performance ternary computing paradigm. By combining 1T1R (one-transistor, one-resistor) memristive cells with carbon nanotube field-effect transistor (CNTFET) selectors and hafnium/titanium oxide stacks, SDPAP V3 TGP achieves ultra-low latency, native trinary logic states (-1, 0, +1), and hardware-level append-only data integrity.

## 2. Core Architectural Specifications

### 2.1. Memory Cell & Selector Stack
- **Cell Topology**: 1T1R architecture providing discrete intermediate resistance states (IRS).
- **Selector Technology**: Solution-deposited CNTFET (Carbon Nanotube Field-Effect Transistor) selectors ensuring high current density and steep subthreshold swing.
- **Dielectric Layers**: Bilayer metal-oxide stack consisting of Hafnium Oxide ($\text{HfO}_2$) and Titanium Oxide ($\text{TiO}_2$) for reliable bipolar resistive switching.
- **Metallization Stack**: CMOS-compatible TiN (bottom electrode) and Ti/TiN (top electrode) layers designed to prevent noble metal line contamination.

### 2.2. Ternary Logic & Execution Flow
- **Native Logic States**: Balanced ternary encoding utilizing negative (-1), zero (0), and positive (+1) voltage/resistance thresholds.
- **Arithmetic Logic Unit (ALU)**: Optimized for parallel ternary operations, significantly reducing transistor count compared to traditional binary equivalents.
- **Compensatory Zeroing**: Hardware-level mechanism ensuring data integrity by balancing positive and active states (+1 $\leftrightarrow$ -1).

## 3. Licensing & Open IP Framework
This repository operates under a dual-tier open framework to protect both hardware designs and descriptive text:
- **Hardware & RTL / GDSII / SPICE**: Licensed under the **CERN Open Hardware Licence Version 2 - Permissive (CERN-OHL-P-2.0)**[cite: 15].
- **Documentation & Specifications**: Dedicated to the public domain under the **Creative Commons CC0 1.0 Universal** standard[cite: 15].
- **Prior Art Declaration**: Foundational cell topologies and execution flows are published explicitly as Prior Art to prevent restrictive patent assertions[cite: 15].
