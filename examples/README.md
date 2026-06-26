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

`example.ipynb` generates CEMC structures at 100 K, 1000 K, 10000 K, and
100000 K for Li1.2Mn0.4Ti0.4O2, then runs Li percolation analysis. It defaults
to one structure per temperature for a quick test and can be changed to 100 for
manuscript-scale statistics.
