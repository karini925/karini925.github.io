---
layout: default
title: Experience
---

## Experience

I am a computational biologist who builds things. My background spans cancer genomics, RNA biology, and protein engineering, and what ties it all together is a love of using large, messy biological datasets to answer questions that matter. I am equally at home reading a paper on splicing mechanisms and debugging a GPU-accelerated pipeline.

---

### Data Scientist, Computational Biology
**[Pioneer Labs](https://www.pioneer-labs.org/#mission)** &nbsp;&middot;&nbsp; August 2025 – Present

Pioneer Labs is a biotech working on one of the hardest problems in synthetic biology: predicting how genes from one organism will behave when transferred to another. I work on the machine learning side of that, building the models and infrastructure that turn high-throughput experimental data into predictive signal.

- To understand which genes are most likely to transfer successfully across species, I coordinated the design and computational analysis of a benchmark spanning 500K fitness measurements across 45K donor genes from 11 diverse microbial species. This is the kind of dataset that does not exist anywhere else, and building it required close collaboration with wet-lab scientists from the start.
- I evaluated protein language models (ESM2, Profluent E1) as a way to represent gene sequences for fitness prediction, comparing them against simpler sequence-identity baselines. Fine-tuning with LoRA gave meaningful accuracy gains over frozen embeddings, which pointed to how much task-specific signal these models were leaving on the table.
- To keep up with experimental throughput, I built end-to-end pipelines on AWS Batch and Nextflow for processing barcoded sequencing data at scale across large microbial libraries.

---

### PhD Intern, Molecular Profiling Data Science
**Regeneron Pharmaceuticals** &nbsp;&middot;&nbsp; June 2024 – August 2024

I spent the summer working on single-cell RNA-seq at a scale that requires you to rethink your tooling entirely. The question was: how do you characterize immune response variation across millions of cells and multiple treatment conditions without the analysis becoming the bottleneck?

- I used GPU-accelerated frameworks (RAPIDS, PyTorch) alongside scVI and NMF-Autoencoders to make dimensionality reduction and feature extraction tractable at that scale.
- I built statistical scoring frameworks to identify which genes were driving latent factors and how those factors shifted across treatments, surfacing pathway-level immune response differences at single-cell resolution.

---

### PhD, Systems Biology
**[Knowles Lab](https://daklab.github.io/), Columbia University** &nbsp;&middot;&nbsp; 2021 – 2025

My thesis was on alternative splicing, the process by which a single gene can produce different protein isoforms depending on cell type, age, or disease state. It is an underexplored axis of cellular variation, partly because the data is sparse and the models to analyze it did not really exist yet. I built them.

- **[LeafletFA](https://github.com/daklab/leaflet)** is a Bayesian factor model for atlas-scale splicing analysis. I applied it to multisample Smart-seq2 datasets to identify conserved age-associated splicing programs shared across mouse and human tissues. The manuscript is under review at *Nature Aging*.
- **SpliceVI** is a joint generative model for single-cell splicing and gene expression using variational inference, designed to disentangle the two signals simultaneously.
- **[LeafletSC](https://github.com/daklab/LeafletSC)** is a Python package for single-cell alternative splicing analysis using binomial mixture models, built to be usable by researchers without a probabilistic modeling background.
- **[Isoviz](https://github.com/karini925/isoviz)** is an R package for visualizing splice junctions across transcript isoforms, built because I needed it and nothing good existed.
- I presented this work at MLCB 2023 in Seattle: *Investigating RNA splicing as a source of cellular diversity using a binomial mixture model*

---

### Computational Biologist
**[Kridel Lab](https://kridel-lab.com/)**, UHN Princess Margaret Cancer Centre, Toronto &nbsp;&middot;&nbsp; May 2019 – July 2021

This is where I learned to do genomics on real clinical questions. The lab studied lymphoma, and the work ranged from understanding why certain drug combinations work, to reconstructing how a patient's tumor evolved over time and across sites in the body.

- I integrated RNA-seq, ChIP-seq, and genome-wide CRISPR screening data to understand why an epigenetic inhibitor combination showed synergistic effects in lymphoma cell lines. That analysis contributed to a publication in *Clinical Cancer Research* (2021).
- I led the computational analysis for a study on relapse in diffuse large B-cell lymphoma, using variant calling and Bayesian clonal phylogeny reconstruction across spatially-separated, multi-timepoint tumor samples. Published in *Haematologica* (2021, 2022).
- I built [NHL-ASCT-PI](https://lymphoma.shinyapps.io/NHL-ASCT-PI/), a Shiny web app for patient risk modeling that integrates clinical variables and pretransplant PET imaging to help clinicians assess transplant outcomes. Published in *Blood Advances* (2020).

---

[Back to home](/)
