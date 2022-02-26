# Spatial and temporal variability in nutricline depth in the Western Pacific

This repository contains scripts used to calculate nutricline depth from BGC-Argo floats in the Western Pacific.

## Data:
- BGC-Argo floats (add all float numbers used here)
- Satellite NPP from VGMP and CGMP algorithms

## Analysis:
- Check the data, some floats seem to have QA/QC issues with big jumps in nitrate concentrations
- Determine nutricline from individual profiles. Which criterion should be used? Look into literature on this.
- Look into estimating epsilon and kappa from the T/S profiles
- Look into estimating nitrate fluxes using kappa (see above)

## Figures to make:
- Data density in time/space
- Example profile(s) of nitrate, epsilon and nitrate flux
- Seasonal maps of nutricline depth
- Histograms to show spatial/seasonal variability in nutricline depth and nitrate flux
- Nutricline depth vs. SSH
- Nutricline depth vs. satellite NPP
- NItrate flux vs. satellite NPP
