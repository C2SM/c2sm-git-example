# Tools

Alongside the models themselves, C2SM maintains and supports a set of tools. Short descriptions
only; the [C2SM User Landing Page](https://c2sm.github.io) documents each properly.

| Tool | What it is for |
| --- | --- |
| **Spack** | A package manager for supercomputers, used to build models and their dependencies reproducibly |
| **Processing Chain** | Automates the sequence of pre-processing, simulation and post-processing steps of a model run |
| **ExtPar** | Generates external parameter files (topography, land use, soil) for ICON and COSMO |
| **icontools** | Grid generation and remapping utilities for ICON |
| **Zonda** | Prepares and manages input data for model simulations |
| **Probtest** | Tests whether a model change alters results beyond expected numerical noise |

## Why these exist

Most of them solve the same underlying problem: a climate simulation is not one program but a
long chain of steps, each with its own inputs, formats and conventions. Automating a chain makes
it reproducible, and reproducibility is what turns a simulation into science.

---

*Something missing? Open an issue, then a pull request.*
