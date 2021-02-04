---
title: 'SkyPy: A package for modelling the Universe'
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
  - name: Coleman Krawczyk
    orcid: 0000-0001-9233-2341
    affiliation: 1
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
date: 3 February 2021
bibliography: paper.bib

---

# Summary

SkyPy [@SkyPy2020] is an open-source Python package for simulating the astrophysical sky. It comprises a library of physical and empirical models across a range of observables and a command line script to run end-to-end simulations. The library provides functions that sample realisations of sources and their associated properties from probability distributions. Simulation pipelines are constructed from these models using a YAML-based configuration syntax, while task scheduling and data dependencies are handled internally and the modular design allows users to interface with external software. SkyPy is developed and maintained by a diverse community of domain experts with a focus on software sustainability and interoperability. By fostering co-development, it provides a framework for correlated multi-probe simulations of a range of cosmological probes including galaxy populations, large scale structure, the cosmic microwave background, supernovae and gravitational waves. 



# Statement of need

An open-data revolution in astronomy led by past, ongoing, and future legacy surveys (e.g. Euclid^[https://www.euclid-ec.org], the Rubin Observatory Legacy Survey of Space and Time^[https://www.lsst.org], Planck^[https://www.cosmos.esa.int/web/planck] and the Laser Interferometer Gravitational-Wave Observatory^[https://www.ligo.caltech.edu]) means access to data is no longer the primary barrier to research. Instead, access to increasingly sophisticated analysis methods is becoming a significant challenge. Researchers frequently need to model multiple astronomical probes and systematics to perform a statistically rigorous analysis that fully exploits the available data. In particular, forward modelling and machine learning have emerged as important techniques for the next generation of surveys and both depend on realistic simulations. However, existing software is frequently closed-source, outdated, unmaintained or developed for specific projects and surveys making it unsuitable for the wider research community. As a consequence astronomers routinely expend significant effort replicating or re-developing existing code. The growing need for skill development and knowledge sharing in astronomy is evidenced by a number of open initiatives focused on software (e.g., Astropy^[https://www.astropy.org], OpenAstronomy^[https://openastronomy.org]) and statistics and machine learning (e.g., Dark Machines^[http://darkmachines.org], The Deep Skies Lab^[https://deepskieslab.com], and the Cosmo-Statistics Initiative^[https://cosmostatistics-initiative.org]). SkyPy was established as a part of this open ecosystem to meet the research community’s need for realistic simulations and enable forward modelling and machine learning applications.



# Acknowledgements

AA and PS acknowledge support from a Royal Society Wolfson Fellowship grant. LFB, SB, IH, and RR acknowledge support from the European Research Council in the form of a Consolidator Grant with number 681431. IH also acknowledges support from the Beecroft Trust. JPC acknowledges support granted by Agencia Nacional de Investigación y Desarrollo (ANID) DOCTORADO BECAS CHILE/2016 - 72170279.



# References
