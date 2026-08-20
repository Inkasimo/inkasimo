# Hi, I’m Simo

Senior computational biologist working at the intersection of systems biology, transcriptomics, and drug discovery.

I design and implement reproducible computational workflows for multi-omics integration, network inference, and mechanism-driven data interpretation. My work focuses on extracting robust biological signal from high-dimensional datasets and translating systems-level insights into drug prioritisation and biomarker strategies.

I am a licensed pharmacist in Finland with clinical and pharmacological training that informs my systems pharmacology and translational modelling work. I also bring a background in evolutionary population ecology, shaping my perspective on biological variation and selection.

---

## Selected Technical Work

### multiome-link-ranking

Reproducible benchmark for single-cell multiome peak–gene link scoring
(Docker + Snakemake + Python CLI wrapper):

- Paired scRNA + scATAC processing (Seurat/Signac), LinkPeaks candidate generation
- Eleven interpretable score modes over one fixed candidate universe
- SCENT as an external comparator, chromosome-sharded across 22 autosomes
- Explicit proximity controls: distance-only baseline, distance-matched
  stratification, proximal-removal thresholds
- Containerized image on GHCR, Zenodo-archived, verified by a clean-clone rerun

Reports a partly negative result: apparent ranking gains are substantially
proximity artifacts, and the benchmark is framed as a diagnostic rather than a
method.

Repository: https://github.com/Inkasimo/multiome-link-ranking
DOI: https://doi.org/10.5281/zenodo.22032459

### scRNAseq-pbmc-workflow
Production-style RNA-seq workflow (Docker + Snakemake + explicit Python CLI wrapper) demonstrating:

- FASTQ-level QC and reference preparation  
- STARsolo alignment  
- Donor-aware differential analysis (DESeq2 + TOST)  
- Co-expression and network-based downstream analysis  
- Explicit execution control via wrapper interface  
- Fully containerized, reproducible execution  

Repository:  
https://github.com/inkasimo/scRNAseq-pbmc-workflow

---

### Selected Publications
```text
Inkala, S., Fratello, M., del Giudice, G. et al. MUUMI: an R package for statistical and network-based meta-analysis for multi-omics data integration. BMC Bioinformatics (2026). https://doi.org/10.1186/s12859-026-06394-3
```

Repository: https://github.com/fhaive/muumi

---

## Focus Areas

- Systems biology and network-based modelling
- Multi-omics data integration and transcriptomics
- Single-cell transcriptomics and multiome (scRNA + scATAC) analysis
- Systems pharmacology and mechanism driven drug discovery
- Reproducible computational workflows (Snakemake, Docker, HPC)
- Benchmarking, confound control and validation strategy
---

## Links

- ORCID: https://orcid.org/0009-0002-2091-8436  
- LinkedIn: https://www.linkedin.com/in/simo-inkala/
