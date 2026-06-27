# Aarohi Deshpande

**MS Bioinformatics candidate at Northeastern University— I build reproducible computational pipelines for transcriptomics, single-cell, and mRNA biology.**

I work at the intersection of RNA biology and scientific computing: turning raw sequencing and structural data into reproducible, interpretable results. I write pipelines and analysis code (Nextflow DSL2, Python, R/Bioconductor) and run them reproducibly on HPC with containers and SLURM. Focus on differential expression, cell-type annotation, and model-vs-baseline benchmarking.

---

### Focus areas

- **Transcriptomics & RNA-seq** — differential expression, quantification, functional enrichment
- **Single-cell genomics** — cell-type annotation, foundation models vs. classical baselines
- **mRNA structure & function** — secondary-structure analysis, sequence-to-function modeling
- **Reproducible pipelines** — Nextflow (DSL2), Docker/Apptainer, SLURM/HPC, GPU workflows

---

### Projects

<!-- To add a project: copy a block below, fill it in, commit. -->

#### Completed

**scRNA-seq foundation models vs. a simple baseline: do they actually win?**
Benchmarked a fine-tuned Geneformer foundation model against a classical PCA + logistic-regression baseline for cell-type annotation on human yolk-sac scRNA-seq data. The simple baseline matched or beat the foundation model (macro-F1 0.93 vs. 0.85), with the gap traced to rare, biologically similar progenitor populations — independently reproducing recent published benchmarks. Built as a reproducible HPC pipeline: stratified data handling, GPU fine-tuning via SLURM (H200/V100), integrity-checked evaluation, UMAP + confusion-matrix visualizations, and a containerized (Apptainer) environment for one-command reproduction.
`Python` · `PyTorch` · `Geneformer` · `scanpy` · `SLURM` · `Apptainer`

**Epileptic seizure prediction — deep neural network on EEG**
A deep neural network that detects epileptic seizures from raw EEG signals, benchmarked against a K-Nearest-Neighbors baseline to test whether the added model complexity actually earns its keep. Full pipeline in notebooks — EEG preprocessing, augmentation, training, and evaluation built to be opened and re-run, not just read about.
`Python` · `TensorFlow` · `scikit-learn` · `EEG` · `Jupyter`

#### In progress

**nf-rnaseq-mettl3 — reproducible RNA-seq pipeline (Nextflow DSL2)**
Custom Nextflow DSL2 pipeline (Salmon → DESeq2 → GO/GSEA), containerized and deployed on HPC, analyzing the transcriptomic response to METTL3 (m6A writer) knockdown. End-to-end reproducible from raw FASTQ to interpreted biology, with a test profile, SLURM execution, and a single self-contained container image.
`Nextflow` · `R/Bioconductor` · `Salmon` · `Docker/Apptainer` · `SLURM`

<!-- New project block here -->

---

### Technical stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![Julia](https://img.shields.io/badge/Julia-9558B2?style=flat&logo=julia&logoColor=white)

**Genomics & ML**
![Nextflow](https://img.shields.io/badge/Nextflow-0DC09D?style=flat&logo=nextflow&logoColor=white)
![Bioconductor](https://img.shields.io/badge/Bioconductor-1F65B7?style=flat&logo=r&logoColor=white)
![scanpy](https://img.shields.io/badge/scanpy-1F77B4?style=flat)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![RNA--seq%2FNGS](https://img.shields.io/badge/RNA--seq%20%2F%20NGS-444444?style=flat)
![single--cell](https://img.shields.io/badge/single--cell-444444?style=flat)

**Infrastructure**
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Apptainer](https://img.shields.io/badge/Apptainer-1D4ED8?style=flat)
![HPC%2FSLURM](https://img.shields.io/badge/HPC%20%2F%20SLURM-444444?style=flat)
![CUDA%2FGPU](https://img.shields.io/badge/CUDA%20%2F%20GPU-76B900?style=flat&logo=nvidia&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

---

### Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aarohi-deshpande-9336b3214/)
