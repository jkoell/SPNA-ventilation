# SPNA-ventilation

This repository contains code for the paper *"Progressive oxygenation of the North Atlantic subpolar gyre"* (https://essopenarchive.org/doi/full/10.22541/essoar.172926706.63693481), submitted to JGR: Oceans on Nov 20, 2024, and accepted for publication on October 10, 2025.

### List of files

* [airsea_flux](airsea_flux.ipynb) - **Computing air-sea fluxes of oxygen.** Fluxes are calculated with the Liang et al. (2013) parameterization, adjusting bubble components by a factor of $\beta$ = 1.5. Includes code for producing Fig. 2a-c, Fig. 3a, and Fig. 6 (jupyter notebook)


* [ECCO_Darwin_O2_mass_budget](ECCO_Darwin_O2_mass_budget.m) - **Oxygen budget terms in ECCO-Darwin.** Code for reading in data used to produce Fig. 4. Based on DIC budget code from the [ECCO-Darwin github](https://github.com/MITgcm-contrib/ecco_darwin) (MATLAB)

* [float_oxygen](float_oxygen.ipynb) - **Oxygen along float track following subpolar gyre path.** Code for producing Fig. 5 (jupyter notebook)

* [isopycnal_oxygen](isopycnal_oxygen.ipynb) - **Calculations for oxygen changes in isopycnal layers.** Includes code for producing Fig. 7 and the blue line in Fig. 6b (jupyter notebook)

*Code citation*: [![DOI](https://zenodo.org/badge/889193073.svg)](https://doi.org/10.5281/zenodo.15214777)


