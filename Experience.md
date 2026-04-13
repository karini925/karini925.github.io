---
layout: default
title: Experience
---

## Experience

---

### Data Scientist, Computational Biology
**[Pioneer Labs](https://www.pioneer-labs.org/#mission)** &nbsp;&middot;&nbsp; August 2025 – Present

Pioneer Labs is a non-profit engineering microbes for Mars, tackling one of the hardest problems in synthetic biology: predicting how genes from one organism will behave when transferred to another. I work on the machine learning side, building models and infrastructure that turn high-throughput experimental data into predictive signal.

I helped design and analyze a fitness benchmark spanning 45K donor genes from 11 microbial species, working closely with the wet lab team. The core question was whether protein language model embeddings (ESM2, Profluent E1) capture more useful signal than simple sequence identity for predicting which genes transfer successfully.

---

### PhD, Systems Biology
**[Knowles Lab](https://daklab.github.io/), Columbia University** &nbsp;&middot;&nbsp; 2021 – 2025

My thesis was on alternative splicing, the process by which different combinations of exons are included or excluded from the final mRNA, affecting protein function, localization, or whether a functional protein is produced at all. It is an underexplored axis of cellular variation, partly because the data is sparse and the computational methods to analyze it at scale were limited.

- **[LeafletFA](https://github.com/daklab/leaflet)** is a Bayesian factor model for atlas-scale splicing analysis. I compiled the largest single-cell alternative splicing dataset in mouse and human, then developed this model to apply to the data and learn splicing programs shared across tissues and species. The manuscript is under review at *Nature Aging*.
- **[SpliceVI](https://github.com/daklab/SpliceVI)** is a joint generative model for single-cell splicing and gene expression using variational inference, designed to disentangle the two signals simultaneously.
- **[LeafletSC](https://github.com/daklab/LeafletSC)** is a Python package for single-cell alternative splicing analysis using binomial mixture models.
- **[Isoviz](https://github.com/karini925/isoviz)** is an R package for visualizing splice junctions across transcript isoforms, built because I needed it and nothing good existed.
- I presented this work at MLCB 2023 in Seattle: *Investigating RNA splicing as a source of cellular diversity using a binomial mixture model*

---

### PhD Intern, Molecular Profiling Data Science
**Regeneron Pharmaceuticals** &nbsp;&middot;&nbsp; June 2024 – August 2024

I spent the summer at Regeneron working on single-cell RNA-seq across millions of cells and multiple treatment conditions, characterizing immune response variation at scale.

- Used GPU-accelerated frameworks (RAPIDS, PyTorch) to scale analysis to millions of single cells, integrating scVI variants and interpretable autoencoder architectures for dimensionality reduction and feature extraction across treatment conditions.


---

### Computational Biologist
**[Kridel Lab](https://kridel-lab.com/)**, UHN Princess Margaret Cancer Centre, Toronto &nbsp;&middot;&nbsp; May 2019 – July 2021

A lymphoma research lab at UHN. I did multi-omic integration across RNA-seq, ChIP-seq, and CRISPR screens ([*Clinical Cancer Research*, 2021](https://aacrjournals.org/clincancerres/article-abstract/27/19/5401/671692/Combined-EZH2-Inhibition-and-IKAROS-Degradation)), led clonal evolution analyses across multi-timepoint tumor samples ([*Haematologica*, 2021](https://pmc.ncbi.nlm.nih.gov/articles/PMC8094129/); [2022](https://pmc.ncbi.nlm.nih.gov/articles/PMC9827161/)), and contributed computational and statistical analysis to [NHL-ASCT-PI](https://lymphoma.shinyapps.io/NHL-ASCT-PI/), a clinical risk stratification model integrating clinical factors and pretransplant PET imaging for transplant outcome prediction ([*Blood Advances*, 2020](https://ashpublications.org/bloodadvances/article/4/22/5762/474205/)).

---

## On science and how I work

I care a lot about honesty in research. Things do not always work, results are often ambiguous, and mistakes happen. Being able to talk about that openly, without fear, is something I think matters a lot. The most exciting science tends to live at the boundary between the risky and the safe, and you cannot get there if you are only willing to report the clean results.

Mentorship matters to me too. I grew up idolizing professors without realizing I could question them, and that took a while to unlearn. Now I try to make that easier for people earlier in their careers, by being someone they can push back on and learn alongside rather than defer to. I am always working to grow as a leader and collaborator, and find some of the best learning comes from working closely with people outside my own area of expertise.

---

[Back to home](/)
