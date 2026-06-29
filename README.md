# 1×4 Microstrip Patch Antenna Array — 3.5 GHz

A corporate-fed microstrip patch antenna array designed and simulated in **CST Studio Suite**, targeting **3.5 GHz (5G NR Band n78)** on FR-4 substrate.

---

## Overview

This project implements a 1×4 rectangular microstrip patch antenna array with a corporate feed power divider network. It was designed to achieve good return loss (S11) and VSWR performance suitable for sub-6 GHz 5G applications.

---

## Specifications

| Parameter | Value |
|---|---|
| Operating Frequency | 3.5 GHz |
| Substrate | FR-4 (εr = 4.4) |
| Number of Elements | 4 |
| Feed Network | Corporate feed with quarter-wave transformers |
| Element Spacing | λ/2 = 42.8 mm |
| Simulation Tool | CST Studio Suite |

---

## Design Details

- **Patch dimensions** optimized for 3.5 GHz resonance on FR-4
- **Corporate feed network** ensures equal power distribution to all elements
- **Quarter-wave transformers** used for impedance matching at each junction
- **T-junction power dividers** cascade from a single 50Ω input port
- Full ground plane beneath the substrate

---

## Results

- S11 return loss optimized at 3.5 GHz
- VSWR within acceptable range at the design frequency
- Gain simulated via CST farfield solver

---

## Files

- `.cst` — CST Studio Suite project file
- Simulation results exported from CST (S-parameters, farfield)

---

## Tools Used

- [CST Studio Suite](https://www.3ds.com/products/simulia/cst-studio-suite) — EM simulation
