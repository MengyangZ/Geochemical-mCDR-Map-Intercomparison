# Data

The model output and intermediate data used by the notebooks in [`analysis/`](../analysis) (~4.4 GB total) are archived on Zenodo rather than stored in this repository, since several files exceed GitHub's file size limits:

**Zenodo DOI: TODO — add link once the record is published**

Download the archive and unpack it here so the directory looks like:

```
data/
├── ada_eff_maps.nc
├── box_model_result.nc
├── dor_efficiency_curves.nc
├── dor_eff_maps.nc
├── eta_max_maps.nc
├── eta_max_mean.nc
├── oae_efficiency_curves.nc
├── oae_eff_maps.nc
├── weighted_eta_max_curves.nc
├── weighted_eta_max_maps.nc
├── plume_surf_excess_alk/
│   ├── North_Atlantic_basin-0444.nc
│   ├── North_Atlantic_basin-0544.nc
│   ├── North_Pacific_basin-0000.nc
│   ├── North_Pacific_basin-0256.nc
│   ├── North_Pacific_basin-0480.nc
│   └── North_Pacific_basin-0700.nc
└── polygon_data/
    ├── Atlantic_final_cluster_centers.npy
    ├── Atlantic_final_polygon_mask.npy
    ├── Atlantic_final_polygon_vertices.npy
    ├── Pacific_final_cluster_centers.npy
    ├── Pacific_final_polygon_mask.npy
    ├── Pacific_final_polygon_vertices.npy
    ├── polygon_center_coords.nc
    ├── polygon_masks.nc
    ├── Southern_Ocean_final_cluster_centers.npy
    ├── Southern_Ocean_final_polygon_mask.npy
    ├── Southern_Ocean_final_polygon_vertices.npy
    ├── South_final_cluster_centers_120EEZ_180openocean.npy
    ├── South_final_polygon_mask_120EEZ_180openocean.npy
    └── South_final_polygon_vertices_120EEZ_180openocean.npy
```
