# SNR Enhancement Pipeline for IR Exoplanet Spectroscopy

## Overview
This repository contains a Jupyter notebook demonstrating a preliminary pipeline for SNR enhancement in infrared (IR) exoplanet spectroscopy using Gaussian fitting and multi-band stacking, as described in the RNAAS note "A Preliminary Technique for SNR Enhancement in Infrared Exoplanet Spectroscopy via Spectral Decomposition".

The pipeline processes FITS files from JWST/HST, performs data inspection, and includes synthetic demonstrations. It is implemented in Python and runs in Google Colab.

### Requirements
- Python 3.11+ (tested in Colab)
- Libraries: `numpy`, `matplotlib`, `astropy`, `scipy` (pre-installed in Colab; no additional pip installs needed beyond the notebook's code)

### Usage
1. Open `GJ_1214b_Testing (1).ipynb` in Google Colab.
2. Run cells sequentially to load FITS data, inspect HDUs, and simulate processing (e.g., Rayleigh scattering for demonstration—adapt for IR focus).
3. Customize paths to your FITS files as needed.

### Key Features
- Loads and inspects JWST/HST FITS files (e.g., i2d, x1dints formats).
- Demonstrates data preprocessing and synthetic SNR enhancement.
- Efficient for low-SNR IR datasets; computational time <1 minute for typical inputs.

### Limitations
- Synthetic examples only; real data validation recommended.
- Assumes standard FITS formats; adapt for custom datasets.

### Citation
If using this pipeline, cite the RNAAS note: Nawaz, A. (2025). RNAAS, [volume], [page].

License: MIT
