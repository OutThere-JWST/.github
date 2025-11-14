# JWST Proposal 3383 — Wide Area 3D Parallel Survey

## Project Overview
The JWST Proposal 3383 – Wide Area 3D Parallel Survey – is a large-scale, near-infrared spectroscopic program using the James Webb Space Telescope (JWST) in pure parallel mode. The survey exploits the wide-field slitless spectroscopy capability of NIRISS to collect deep, wide-area data as “bonus” parallel observations.

Program information: [JWST Program 3383 at STScI](https://www.stsci.edu/jwst/science-execution/program-information?id=3383)

A large, homogeneous spectroscopic sample from z ~ 1–5 (and beyond) will clarify how galaxies assemble mass, form and quench stars, chemically enrich, and evolve within their dark-matter halos. The large-area design minimizes cosmic variance, enabling strong constraints on clustering, environmental dependence, and the abundance of rare sources. Our open-source, reproducible tools aim to establish a community benchmark for galaxy evolution in the JWST era.

---

## Key Goals
- Wide-area coverage: ~1000 arcmin² via pure parallel pointings, obtaining both direct imaging (filters F150W and F200W) and slitless grism spectra (GR150C) for the same fields.  
- Spectroscopic redshifts: High-completeness redshifts for ~60,000 galaxies over 1 < z < 5, spanning from Cosmic Noon to Cosmic Dawn.  
- Galaxy physics: Continuum and emission-line measurements down to low masses, enabling SFRs, metallicities, stellar ages, and spatial gradients.  
- Environmental context: From field galaxies to proto-clusters, connecting dark-matter halo growth with baryonic evolution.  
- Benchmark dataset: A definitive spectroscopic reference for stellar-mass functions, quenching histories, internal gradients, and rare sources (e.g., bright galaxies at z > 11).  
- Data-driven discovery: Application of machine learning and advanced statistics to a large, homogeneous dataset.

---

## Observing Strategy & Technical Approach
- Parallel operations: While a primary JWST instrument observes its target, NIRISS simultaneously observes a parallel field.  
- Mode & filters: Each pointing includes direct imaging (F150W, F200W) and slitless spectroscopy (GR150C) in both filters.  
- Exposure times (typical): ~1200 s for direct images and ~3600 s for grism spectra (minimums ~430 s and ~1300 s, respectively).  
- Survey design: Many parallel pointings across the sky to maximize volume, minimize cosmic variance, and enable robust statistics.

---

## Relevance to This Organization

This repository hosts repositories for data reduction, analysis, calibration and visualizations for the survey.




