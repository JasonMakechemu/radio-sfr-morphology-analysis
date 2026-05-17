# radio-sfr-morphology-analysis
# Structural Information in the Radio–Star-Formation-Rate Relation — Code Repository

## Overview

This repository contains the analysis scripts, notebooks, machine learning pipelines, and figure-generation code associated with the paper:

> *Structural Information as the Missing Component in the Radio–Star-Formation-Rate Relation*

The project investigates how galaxy morphology contributes to the intrinsic scatter in the infrared-radio correlation (IRRC) and radio-based star formation rate (SFR) inference using VLA-COSMOS 3 GHz data, Zurich non-parametric morphology, and Galaxy Zoo Hubble classifications.

---

## Main Scientific Results

- Non-parametric morphology contributes the dominant hidden-variable information in the radio–SFR relation
- Morphology improves predictive performance by ΔR² ≈ 0.13
- Galaxy Zoo Hubble classifications independently reproduce the signal
- Flat-spectrum radio-excess sources exhibit strong asymmetry suppression
- Parametric Sérsic morphology contributes substantially less predictive information

---

## Repository Structure

```text
data/               -> Processed catalogues and derived datasets
notebooks/          -> Jupyter notebooks for exploratory analysis
scripts/            -> Main analysis scripts
figures/            -> Generated figures for the manuscript
models/             -> Saved ML models and pipelines
tables/             -> Exported statistical tables
paper/              -> Manuscript PDF and LaTeX source
