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

SkyPy is an open-source Python package for simulating catalogs of astronomical sources. It comprises a library of astrophysical and empirical models and a command line script to run end-to-end simulations. Pipelines are defined using a YAML-based configuration syntax, while task scheduling and data dependencies are handled internally. The modular design allows users to extend pipelines with external software.



# Statement of need

An open-data revolution in astronomy led by past, ongoing, and future legacy surveys (e.g. Planck^[https://www.cosmos.esa.int/web/planck], DES^[https://www.darkenergysurvey.org], LIGO^[https://www.ligo.caltech.edu]) means access to data is no longer the primary barrier to research. Instead, access to increasingly sophisticated analysis methods is becoming a significant challenge. Researchers frequently need to model multiple astronomical probes and systematics to perform a statistically rigorous analysis that fully exploits the available data. In particular, likelihood-free inference and machine learning have emerged as important techniques for the next generation of surveys and both depend on realistic simulations. However, existing software is frequently closed-source, outdated, unmaintained or developed for specific projects and surveys making it unsuitable for the wider research community. As a consequence astronomers routinely expend significant effort replicating or re-developing existing code. The growing need for skill development and knowledge sharing is evidenced by a number of recent open initiatives focused on statistical and machine learning applications for astronomy  (e.g., Dark Machines^[http://darkmachines.org/], The Deep Skies Lab^[https://deepskieslab.com/], and the Cosmo-Statistics Initiative (COINS)^[https://cosmostatistics-initiative.org/projects/]).

SkyPy [@SkyPy2020] is being developed and maintained as an independent open-source Python package for running end-to-end simulations to enable both forward modelling and machine learning applications. By building a diverse community of domain experts with a range of expertise and fostering co-development, SkyPy will deliver simulations for a range of cosmological probes including galaxy populations, large scale structure, the cosmic microwave background, supernovae and gravitational waves that capture the cross-correlations between datasets.



# Acknowledgements



# References
