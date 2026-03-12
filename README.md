# Atomistic Models of Wood and Straw Biochar for Mn(II) Removal

[![DOI](https://zenodo.org/badge/1119456778.svg)](https://doi.org/10.5281/zenodo.18963461)

This repository contains atomistic models and GROMACS-compatible coordinate/topology files used in the paper:

_**Decoupling Precipitation and Surface Complexation during Mn(II) Removal by Biochar via Experiments and Atomistic Simulations**_ by Audrey Ngambia, Anastasiia Gavrilova, Haitao Huang, Zhuodong Lyu, Ondřej Mašek, Margaret Graham, and Valentina Erastova. DOI pending.

The data in this repository is produced by Audrey Ngambia, Haitao Huang, Zhuodong Lyu, and Valentina Erastova at the School of Chemistry, University of Edinburgh.

The repository includes final equilibrated models of biochar systems containing Mn(II), chloride ions, and water, together with supporting topology and force-field files for straw- and wood-derived biochars.

## Naming

- `S` = straw-derived biochar
- `W` = wood-derived biochar
- `400` / `800` = pyrolysis temperature in °C
- `DP` = partially deprotonated model

### Included systems

- `S400` – straw biochar produced at 400 °C
- `S400DP` – partially deprotonated straw biochar produced at 400 °C
- `S800` – straw biochar produced at 800 °C
- `W400` – wood biochar produced at 400 °C
- `W400DP` – partially deprotonated wood biochar produced at 400 °C
- `W800` – wood biochar produced at 800 °C

## Repository structure

```text
.
├── PDB_systems/
├── Straw_BC/
└── Wood_BC/
```

### `PDB_systems/`
Final equilibrated PDB files for the complete simulation systems, including biochar, Mn2+ and Cl- ions, and water.

### `Straw_BC/`
Straw-derived biochar models and associated GROMACS files:

- `oplsaa.ff/` – local copy of the OPLS-AA force field used for these systems
- `S400/` – straw biochar produced at 400 °C
- `S400DP/` – partially deprotonated straw biochar produced at 400 °C
- `S800/` – straw biochar produced at 800 °C

### `Wood_BC/`
Wood-derived biochar models and associated GROMACS files:

- `oplsaa.ff/` – local copy of the OPLS-AA force field used for these systems
- `W400/` – wood biochar produced at 400 °C
- `W400DP/` – partially deprotonated wood biochar produced at 400 °C
- `W800/` – wood biochar produced at 800 °C

## File types

| File type | Description |
| --- | --- |
| `.pdb` | Final equilibrated full-system structures |
| `.gro` | GROMACS coordinate files |
| `.itp` | GROMACS include topology files for biochar building blocks |
| `.top` | GROMACS system topology files |
| `.atp` | Atom type definition files where required |

## Contents

This repository provides:

- final equilibrated PDB models of biochar + Mn(II) + Cl- + water systems;
- GROMACS `.gro`, `.top`, `.itp`, and `.atp` files for the biochar models;
- OPLS-AA force-field files used in the simulations;
- condensed biochar model files and equilibrated surface-exposed biochar structures where available.

### Notes on file naming

- Files named `surf_exposed_*.gro` correspond to equilibrated surface-exposed biochar material.
- Directories also contain biochar molecular building block files (for example `S400-3.*` or deprotonated variants).


## Citation

If you use these models, please cite the associated publications:

1. Audrey Ngambia, Anastasiia Gavrilova, Haitao Huang, Zhuodong Lyu, Ondřej Mašek, Margaret Graham, and Valentina Erastova. "Decoupling Precipitation and Surface Complexation during Mn(II) Removal by Biochar via Experiments and Atomistic Simulations". DOI PENDING

2. Audrey Ngambia, & Valentina Erastova. (2026). Erastova-group/Mn_Biochar: publication data (v1.0.0). Zenodo. [10.5281/zenodo.18963462](https://doi.org/10.5281/zenodo.18963462)

3. Rosie Wood, Ondřej Mašek, and Valentina Erastova. "Developing realistic molecular models of biochars." Cell Reports Physical Science 5.7 (2024). [10.1016/j.xcrp.2024.102037](https://doi.org/10.1016/j.xcrp.2024.102037)


## Contact

For questions about the models or files in this repository, please contact Valentina Erastova valentina.erastova@ed.ac.uk



