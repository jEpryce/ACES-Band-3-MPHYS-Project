# Star Formation in the Central Molecular Zone (CMZ)

This repository contains the analysis scripts and Jupyter notebooks used in the master's thesis project:  
**"Chemical and Dynamical Analysis of Dense Gas in the CMZ"**.

## Contents

- `0000_molecule_identification.ipynb`  
  Identifies molecular lines in the spectral cube. This includes peak finding and matching to known species.

- `moment_map_stitching_core.py`  
  Script for combining Moment 0, 1, and 2 maps for each core, and generating core moment map pages for the appendix.

- `moment_map_stitching_cloud.py`  
  Same as above, but for full cloud-scale maps.

- `energy_proxy_analysis.ipynb`  
  Calculates energy proxies to estimate gravitational stability of each core.

## Data Access

The data used in this project (ACES Band 3 FITS cubes and derived moment maps) is **not included in this repository** due to size and licensing restrictions.

**Data is available upon request** for academic or review purposes. Please contact the author at sgjpryc2@liverpool.ac.uk.

## Requirements

To run the code and notebooks, you will need:

- Python 3.x
- `numpy`, `matplotlib`, `astropy`, `scipy`, `PIL` (Pillow)

You can install dependencies with:

```bash
pip install numpy matplotlib astropy scipy pillow
