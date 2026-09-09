# Geochemical-mCDR-Map-Intercomparison

This repository contains the analysis workflow for mapping global variations in Direct Ocean Removal (DOR) efficiency, and its comparison with Ocean Alkalinity Enhancement (OAE) efficiency. The combination of OAE and DOR simulations are used to quantify simultaneous alkalinity and DIC perturbations (ADA), enabling direct assessment of the oceanic fate of ADA perturbations from approaches like enhanced rock weathering, riverine alkalinity enhancement, and accelerated limestone weathering.

## Repository structure

- [`analysis/`](analysis) — notebooks and Python modules used to reproduce the manuscript figures.
- [`data/`](data) — expected location for analysis data used by the notebooks; see [`data/README.md`](data/README.md) for the Zenodo download link and expected layout.

## Data availability

The data used to generate the figures are archived on Zenodo (~4.4 GB): see [`data/README.md`](data/README.md) for the DOI and instructions.

## Environment

The notebooks were run with the conda environment specified in [`mcdr-atlas.yml`](mcdr-atlas.yml):

```
conda env create -f mcdr-atlas.yml
conda activate mcdr-atlas
```
