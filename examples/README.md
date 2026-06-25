# Example LMTO Structures

This directory contains representative LMTO structures in VASP format.

## Contents

| Directory | Files |
| --- | --- |
| `100K_LMTO_structures/` | `CEMC_0.vasp` to `CEMC_4.vasp` |
| `1000K_LMTO_structures/` | `CEMC_0.vasp` to `CEMC_4.vasp` |
| `10000K_LMTO_structures/` | `CEMC_0.vasp` to `CEMC_4.vasp` |
| `100000K_LMTO_structures/` | `CEMC_0.vasp` to `CEMC_4.vasp` |

Each file is a VASP-style structure for the Li-Mn-Ti-O DRX system.

## Reproduction notebook

`reproduce_cemc_percolation_Li1p2Mn0p4Ti0p4O2.ipynb` generates 100 CEMC
structures at 100 K, 1000 K, 10000 K, and 100000 K for Li1.2Mn0.4Ti0.4O2,
then runs Li percolation analysis to reproduce the Fig. 2b workflow.
