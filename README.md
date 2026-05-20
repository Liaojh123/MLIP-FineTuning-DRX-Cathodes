# MLIP-FineTuning-DRX-Cathodes

This repository supports the manuscript "Dual Control of Percolation and Site
Energy Distribution for Optimizing Li+ Transport in Disordered Rocksalt
Cathodes".

It contains example LMTO structures, SevenNet checkpoints, and a compact test
dataset used for machine-learned interatomic potential (MLIP) fine-tuning and
evaluation on disordered rocksalt (DRX) cathode materials.

## Repository layout

```text
data/       Compact test dataset archive
examples/   Example LMTO structures in VASP format
models/     Pretrained and fine-tuned SevenNet checkpoints
```

## Data availability

The complete LMTO training and testing datasets are hosted on Zenodo:

https://zenodo.org/records/19179419

The local `data/` directory contains a compact archive for repository-level
testing and inspection. See `data/README.md` for details.

## Models

The `models/` directory includes:

- `pretrained_checkpoint_sevennet.pth`
- `finetuned_checkpoint_sevennet.pth`

See `models/README.md` for intended use and versioning notes.

## Example structures

The `examples/` directory contains representative LMTO structures generated at
100 K, 1000 K, 10000 K, and 100000 K. Each temperature directory contains five
`CEMC_*.vasp` structures.

## License

Code and repository documentation are released under the MIT License. Dataset
license terms should follow the Zenodo record.
