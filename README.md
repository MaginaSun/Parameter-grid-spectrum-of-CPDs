Parametric CPD Models – Spectral Data Repository

This repository contains spectral data generated from parametric circumplanetary disk (CPD) models using the radiative transfer code RADMC-3D.

The models were developed for the systematic exploration of infrared spectra from circumplanetary disks and their application to spectral fitting. At the current stage, only the subset of models presented in the associated paper has been uploaded. The complete parameter grid will be added progressively in future updates.

Repository Contents

Each numbered directory (0001, 0002, …) corresponds to one model from the parameter grid used in the paper. Each directory contains:

* The synthetic spectrum produced with RADMC-3D.
* The corresponding RADMC-3D input files required to reproduce the simulation.

Users may therefore rerun the same model with different numerical settings (e.g., wavelength sampling or photon statistics) to generate spectra with different accuracies or spectral resolutions.

Plotting the Spectra

The repository includes a Jupyter notebook:

Plot_spectrum.ipynb

which reproduces the spectral comparison figures presented in the paper directly from the uploaded data.

Related Paper

Parameter Effects in Circumplanetary Disk Spectra and Prospects for Spectral Fitting

* arXiv: https://arxiv.org/abs/2606.08996
* DOI: to be added after publication

Additional Notes

* The radmc3d.out files are placeholders. During the original simulations, the standard terminal output of RADMC-3D was not redirected to log files and is therefore unavailable.


Future Updates

Future releases will include:

* the data of spectral fitting (Fig.6 of the related paper),
* the complete parameter grid,
* additional model visualizations (e.g., surface density and temperature structures),
* and other products that may facilitate the interpretation and fitting of circumplanetary disk spectra.

Citation

If you use these models or spectra in your work, please cite the associated paper.
