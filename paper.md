---
title: 'SkyPy'
tags:
  - "software: simulations"
authors:
  - name: Adam Amara
    orcid: 0000-0003-3481-3491
    affiliation: 1
  - name: Richard P. Rollins
    orcid: 0000-0003-1291-1023
    affiliation: 2
affiliations:
  - name: Institute of Cosmology and Gravitation, University of Portsmouth, Portsmouth, P01 3FX UK
    index: 1
  - name: Jodrell Bank Centre for Astrophysics, University of Manchester, Manchester, M13 9PL UK
    index: 2
date: 5 January 2021
bibliography: paper.bib

---

# Summary

SkyPy is an open-source Python package for forward modeling astronomical sky surveys. At its core is a library of empirical and physically motivated models for the redshifts, morphologies and photometric properties of galaxy populations. SkyPy also provides a command line script to run end-to-end simulations and generate synthetic catalogs; pipelines are defined using a YAML-based config syntax while task scheduling and data dependencies are handled internally. The modular design allows users to extend pipelines with external software and future releases will implement models for additional astrophysical sources to enable correlated multi-probe simulations.


# Statement of need

Until recently, progress in observational cosmology and extra-galactic observations was limited primarily by data access and collaborations often formed around data access, for example the Sloan Digital Sky Survey^[https://www.sdss.org], COSMOS^[https://cosmos.astro.caltech.edu], the Dark Energy Survey^[https://www.darkenergysurvey.org]. This is now changing, with ever-increasing high-quality archives and upcoming open data (the Rubin Observatory^[Formerly known as LSST, https://www.lsst.org], Euclid^[https://www.euclid-ec.org], DESI^[https://www.desi.lbl.gov], the Nancy Grace Roman Space Telescope^[Formerly known as WFIRST, https://roman.gsfc.nasa.gov]) the rate-limiting step is access to methods rather than access to data. The analyses are also becoming ever more demanding and a multitude of astronomical phenomenology needs to be sufficiently accounted for to perform statistically meaningful and precise knowledge.

In the astronomical community, two exciting and related types of methods have emerged (i) forward modeling/likelihood-free inference and (ii) machine learning. The key to enabling both of these methods is the ability to generate realistic simulations. Tools for the generation of such simulations already exist within the scientific community, but are mostly private or linked to projects.  There is a significant amount of ‘re-inventing the wheel’ due to lack of compatibility between different efforts. 

The vision for SkyPy [@SkyPy2020] is to build an open-source off-project high quality Python package that contains functionality to make end-to-end simulations to enable both forward modelling and machine learning methods. To develop tools for forward modelling a plausible optical galaxy survey, we have initially focussed on: background calculation, perturbation statistics, halo statistics, galaxy properties and galaxy populations, selection effects and synthetic observations. SkyPy is envisioned as a collaboration formed by experts on a wide range of fields in astrophysics and cosmology, with the additional benefits of co-development of compatible modules by teams outside of SkyPy, enabled by the open-source collaborative development.



# Acknowledgements



# References
