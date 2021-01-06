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

SkyPy is an open-source Python package for forward modeling astronomical surveys. At its core is a library of empirical and physically motivated models for the redshifts, morphologies and photometric properties of galaxy populations. SkyPy also provides a command line script to run end-to-end simulations and generate synthetic catalogs; pipelines are defined using a YAML-based config syntax while task scheduling and data dependencies are handled internally. The modular design allows users to extend pipelines with external software and future releases will implement models for additional astrophysical sources to enable correlated multi-probe simulations.


# Statement of need

Until recently,  progress in observational cosmology and extra-galactic observations was limited primarily by data access and collaborations often formed around data access, namely the Sloan Digital Sky Survey^[https://www.sdss.org], COSMOS^[https://cosmos.astro.caltech.edu], the Dark Energy Survey^[https://www.darkenergysurvey.org]. This is now changing, with ever-increasing high-quality archives and upcoming data (the Rubin Observatory^[Formerly known as LSST, https://www.lsst.org], Euclid^[https://www.euclid-ec.org], DESI^[https://www.desi.lbl.gov], the Nancy Grace Roman Space Telescope^[Formerly known as WFIRST, https://roman.gsfc.nasa.gov])
the rate-limiting step is access to methods rather than access to data.
 
SkyPy [@skypy_collaboration_2020_3755531] is therefore envisioned to be a collaboration built around methods. Two exciting  and related types of methods have recently emerged (i) forward modeling/likelihood-free inference and (ii) machine learning. The  key to enabling both of these is the ability to generate realistic simulations. The vision for SkyPy is to build an open-source off-project high quality Python package that contains functionality to make end-to-end simulations to enable both forward modelling and machine learning methods. For this, SkyPy aims to become an Astropy-affiliated package and to reuse existing, high-quality public software. 

SkyPy communes with the Astropy philosophy [@astropy:2018], and aims to develop and foster open-source software and tools for the astronomical community. SkyPy is a collaboration based on open discussions, consensus, transparency and trust. SkyPy has a board that manages membership and policies, and is organised in dynamic teams to minimise permanent structures.

The package is built as a GitHub organisation^[https://github.com/skypyproject/skypy] and is being developed in different phases. SkyPy aims to high-standard coding and documentation, and every module and function is subjected to code-review processes and testing. The public repository is driven by research and development projects and its releases follow a semantic-versioning scheme.



# Acknowledgements



# References
