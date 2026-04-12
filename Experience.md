---
layout: default
title: Experience
---

## Experience

I am a computational biologist who loves building things. My expertise is using machine learning to dig into hard problems in biology, making it possible to iterate faster and actually use the mountains of data that already exist to better understand these insanely complex processes.

---

### Data Scientist, Computational Biology
**[Pioneer Labs](https://www.pioneer-labs.org/#mission)** &nbsp;&middot;&nbsp; August 2025 – Present

Pioneer Labs is a non-profit engineering microbes for Mars, tackling one of the hardest problems in synthetic biology: predicting how genes from one organism will behave when transferred to another. I work on the machine learning side, building models and infrastructure that turn high-throughput experimental data into predictive signal.

I helped design and analyze a fitness benchmark spanning 45K donor genes from 11 microbial species, working closely with the wet lab team. The core question was whether protein language model embeddings (ESM2, Profluent E1) capture more useful signal than simple sequence identity for predicting which genes transfer successfully.

---

### PhD, Systems Biology
**[Knowles Lab](https://daklab.github.io/), Columbia University** &nbsp;&middot;&nbsp; 2021 – 2025

My thesis was on alternative splicing, the process by which a single gene can produce different protein isoforms depending on cell type, age, or disease state. It is an underexplored axis of cellular variation, partly because the data is sparse and the models to analyze it did not really exist yet. I built them.

- **[LeafletFA](https://github.com/daklab/leaflet)** is a Bayesian factor model for atlas-scale splicing analysis. I compiled the largest single-cell alternative splicing dataset in mouse and human, then developed this model to apply to the data and learn splicing programs shared across tissues and species. The manuscript is under review at *Nature Aging*.
- **SpliceVI** is a joint generative model for single-cell splicing and gene expression using variational inference, designed to disentangle the two signals simultaneously.
- **[LeafletSC](https://github.com/daklab/LeafletSC)** is a Python package for single-cell alternative splicing analysis using binomial mixture models, built to be usable by researchers without a probabilistic modeling background.
- **[Isoviz](https://github.com/karini925/isoviz)** is an R package for visualizing splice junctions across transcript isoforms, built because I needed it and nothing good existed.
- I presented this work at MLCB 2023 in Seattle: *Investigating RNA splicing as a source of cellular diversity using a binomial mixture model*

---

### PhD Intern, Molecular Profiling Data Science
**Regeneron Pharmaceuticals** &nbsp;&middot;&nbsp; June 2024 – August 2024

I spent the summer working on single-cell RNA-seq at a scale that requires you to rethink your tooling entirely. The question was: how do you characterize immune response variation across millions of cells and multiple treatment conditions without the analysis becoming the bottleneck?

- I used GPU-accelerated frameworks (RAPIDS, PyTorch) alongside scVI and NMF-Autoencoders to make dimensionality reduction and feature extraction tractable at that scale.
- I built statistical scoring frameworks to identify which genes were driving latent factors and how those factors shifted across treatments, surfacing pathway-level immune response differences at single-cell resolution.

---

### Computational Biologist
**[Kridel Lab](https://kridel-lab.com/)**, UHN Princess Margaret Cancer Centre, Toronto &nbsp;&middot;&nbsp; May 2019 – July 2021

This is where I learned to do genomics on real clinical questions. The lab studied lymphoma, and the work ranged from understanding why certain drug combinations work, to reconstructing how a patient's tumor evolved over time and across sites in the body.

- I integrated RNA-seq, ChIP-seq, and genome-wide CRISPR screening data to understand why an epigenetic inhibitor combination showed synergistic effects in lymphoma cell lines. That analysis contributed to a publication in *Clinical Cancer Research* (2021).
- I led the computational analysis for a study on relapse in diffuse large B-cell lymphoma, using variant calling and Bayesian clonal phylogeny reconstruction across spatially-separated, multi-timepoint tumor samples. Published in *Haematologica* (2021, 2022).
- I built [NHL-ASCT-PI](https://lymphoma.shinyapps.io/NHL-ASCT-PI/), a Shiny web app for patient risk modeling that integrates clinical variables and pretransplant PET imaging to help clinicians assess transplant outcomes. Published in *Blood Advances* (2020).

---

[Back to home](/)
