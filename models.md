# Models

C2SM supports a number of climate and weather models for its user community. This page is a short
orientation; the [C2SM User Landing Page](https://c2sm.github.io) has the real documentation,
including build instructions and supported machines.

## ICON

**ICON** (ICOsahedral Nonhydrostatic) is a unified modelling framework for numerical weather
prediction and climate simulation, developed jointly by the German Weather Service (DWD), the
Max Planck Institute for Meteorology and partners including MeteoSwiss and ETH Zurich.

It uses an icosahedral grid rather than a traditional latitude-longitude grid, which avoids the
convergence of grid cells at the poles. It runs from global resolutions down to
kilometre-scale limited-area configurations.

ICON is the focus of the [EXCLAIM](https://exclaim.ethz.ch/) project, which targets
kilometre-scale climate simulation on GPU-based supercomputers.

## CESM

**CESM** (Community Earth System Model) is a fully coupled Earth system model developed primarily
at NCAR in the United States. It couples atmosphere, ocean, land, sea ice and land ice components
and is widely used for long climate simulations and large ensembles.

## COSMO

**COSMO** is the limited-area weather and regional climate model previously developed by the
COSMO consortium of European weather services. Much of the community it served, MeteoSwiss
included, has moved to ICON, but COSMO remains relevant for older simulations and long-running
regional climate work.

---

*Adding a model you work with? Open a pull request. See [CONTRIBUTING.md](CONTRIBUTING.md).*
