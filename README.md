# Geochemical-mCDR-Map-Intercomparison

This repository contains the analysis workflow for model experiments conducted with CESM, exploring global variations in the efficiency of ocean-based geochemical carbon dioxide removal (CDR), including Ocean Alkalinity Enhancement (OAE) and Direct Ocean Removal (DOR).

## Repository structure

- [`analysis/`](analysis) — notebooks and Python modules used to reproduce the manuscript figures.
- [`data/`](data) — expected location for model output/intermediate data used by the notebooks; see [`data/README.md`](data/README.md) for the Zenodo download link and expected layout.

## Data availability

The data used to generate the figures are archived on Zenodo (~4.4 GB, too large for GitHub): see [`data/README.md`](data/README.md) for the DOI and instructions.

## Environment

The notebooks were run with the conda environment specified in [`mcdr-atlas.yml`](mcdr-atlas.yml):

```
conda env create -f mcdr-atlas.yml
conda activate mcdr-atlas
```
