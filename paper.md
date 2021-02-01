---
title: 'SkyPy'
tags:
  - "software: simulations"
authors:
  - name: Adam Amara^[adam.amara@port.ac.uk]
    orcid: 0000-0003-3481-3491
    affiliation: 1
  - name: Lucia F. de la Bella
    orcid: 0000-0002-1064-3400
    affiliation: 2
  - name: Simon Birrer
    orcid: 0000-0003-3195-5507
    affiliation: 3
  - name: Sarah Bridle
    orcid: 0000-0002-0128-1006
    affiliation: 2
  - name: Juan Pablo Cordero
    orcid: 0000-0002-6625-7656
    affiliation: 2
  - name: Ian Harrison
    orcid: 0000-0002-4437-0770
    affiliation: 2
  - name: Brian Nord
    orcid: 0000-0001-6706-8972
    affiliation: "4, 5, 6"
  - name: Richard P. Rollins^[richard.rollins@manchester.ac.uk]
    orcid: 0000-0003-1291-1023
    affiliation: 2
  - name: Philipp Sudek
    orcid: 0000-0001-8685-2308
    affiliation: 1
  - name: Sut-Ieng Tam
    orcid: 0000-0002-6724-833X
    affiliation: 7
  - name: Nicolas Tessore
    orcid: 0000-0002-9696-7931
    affiliation: 8
  - name: Keiichi Umetsu
    orcid: 0000-0002-7196-4822
    affiliation: 7
affiliations:
  - name: Institute of Cosmology and Gravitation, University of Portsmouth
    index: 1
  - name: Jodrell Bank Centre for Astrophysics, University of Manchester
    index: 2
  - name: Kavli Institute for Particle Astrophysics and Cosmology and Department of Physics, Stanford University
    index: 3
  - name: Fermi National Accelerator Laboratory
    index: 4
  - name: Kavli Institute for Cosmological Physics, University of Chicago
    index: 5
  - name: Department of Astronomy and Astrophysics, University of Chicago
    index: 6
  - name: Institute of Astronomy and Astrophysics, Academia Sinica
    index: 7
  - name: Department of Physics and Astronomy, University College London
    index: 8
date: 5 January 2021
bibliography: paper.bib

---

# Summary

SkyPy is an open-source Python package for simulating catalogs of astronomical sources. It comprises a library of astrophysical and empirical models and a command line script to run end-to-end simulations. Pipelines are defined using a YAML-based configuration syntax, while task scheduling and data dependencies are handled internally. The modular design allows users to extend pipelines with external software.



# Statement of need

An open-data revolution in astronomy led by past, ongoing, and future legacy surveys (e.g. Planck^[https://www.cosmos.esa.int/web/planck], DES^[https://www.darkenergysurvey.org], LIGO^[https://www.ligo.caltech.edu]) means access to data is no longer the primary barrier to research. Instead, access to increasingly sophisticated analysis methods is becoming a significant challenge. Researchers frequently need to model multiple astronomical probes and systematics to perform a statistically rigorous analysis that fully exploits the available data. In particular, likelihood-free inference and machine learning have emerged as important techniques for the next generation of surveys and both depend on realistic simulations. However, existing software is frequently closed-source, outdated, unmaintained or developed for specific projects and surveys making it unsuitable for the wider research community. As a consequence astronomers routinely expend significant effort replicating or re-developing existing code. The growing need for skill development and knowledge sharing is evidenced by a number of recent open initiatives focused on statistical and machine learning applications for astronomy  (e.g., Dark Machines^[http://darkmachines.org/], The Deep Skies Lab^[https://deepskieslab.com/], and the Cosmo-Statistics Initiative (COINS)^[https://cosmostatistics-initiative.org/projects/]).

SkyPy [@SkyPy2020] is being developed and maintained as an independent open-source Python package for running end-to-end simulations to enable both forward modelling and machine learning applications. By building a diverse community of domain experts with a range of expertise and fostering co-development, SkyPy will deliver simulations for a range of cosmological probes including galaxy populations, large scale structure, the cosmic microwave background, supernovae and gravitational waves that capture the cross-correlations between datasets.



# Acknowledgements

AA and PS acknowledge support from a Royal Society Wolfson Fellowship grant. LFB, SB, IH, and RR acknowledge support from the European Research Council in the form of a Consolidator Grant with number 681431. IH also acknowledges support from the Beecroft Trust. JPC acknowledges support granted by Agencia Nacional de Investigación y Desarrollo (ANID) DOCTORADO BECAS CHILE/2016 - 72170279.



# References
