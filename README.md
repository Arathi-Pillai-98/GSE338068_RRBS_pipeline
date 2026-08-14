# GSE338068_RRBS_pipeline
RRBS methylation pipeline for epidermolysis bullosa dataset GSE338068

## Background

Epidermolysis bullosa (EB) is a group of rare, inherited genetic disorders causing extreme skin fragility. People with EB lack the anchor proteins that hold skin layers together. Minor friction, rubbing, or heat causes the skin to blister, tear, and form painful wounds. Reduced representation bisulfite sequencing (RRBS) was performed to investigate DNA methylation profiles in patients with epidermolysis bullosa (EB) exhibiting variable disease severity. Differential methylation analysis identified a differentially methylated region within the NLRP7 promoter in severe patients.

## Dataset

This project uses the public GEO series **GSE338068**, which includes:
- SRA files of each sample

## Project goals

The main goals of this project are:

- Reproduce (at least qualitatively) the reported NLRP7 promoter hypermethylation in severe disease.
- Generate a small set of DMRs and annotate them with gene context (promoter, gene body) and basic GO enrichment.

## Repository structure

Planned directory layout:

- `data/` – information about GEO data sources and any small derived data objects.
- `scripts/` – R and Python scripts for data preparation, QC, analysis and visualization.
- `results/` – figures and tables summarizing the main findings.
