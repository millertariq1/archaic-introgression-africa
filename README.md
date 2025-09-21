# archaic-introgression-africa
Detecting Archaic Introgression in African Genomes With AI- Assisted Pipelines
# Detecting Archaic Introgression in African Genomes with AI-Assisted Pipelines

## Project Overview
This repository contains code, results, and notes from my independent research on archaic introgression in West African genomes.  
The focus is on Yoruba and Mende populations (1000 Genomes Project), compared with ancient genomes including Altai Neanderthal, Vindija Neanderthal, and Denisovan (Max Planck datasets).  

## Methods
- Population genomics pipelines (PLINK, ADMIXTOOLS, VCFtools, bcftools)  
- D-statistics, f-statistics, f₄-ratio tests  
- PCA and allele frequency analysis  
- Machine learning integration (Python, R) to detect introgression signals  

## Repository Structure
- `notebooks/` → Jupyter notebooks with analyses (e.g., D-stats, PCA)  
- `scripts/` → Helper Python or R scripts  
- `results/` → Tables and text files with statistics  
- `figures/` → Plots and visualizations

- ## Status Update – March-July 2025
- WA VCFs ready, archaic genomes located, panel in place.
- scikit-allel needs resolution (maybe switch to cyvcf2).
- CEU subset VCF not finalized — priority for AF comparisons.
- Outgroup (chimp VCF) still needed.
- Next: Run D-statistics and f-ratio tests once CEU + archaic datasets are ready.

## Current Progress
Initial work focuses on Yoruba genomes (1000 Genomes) with D-statistics to test for ghost archaic introgression.  
Upcoming updates will include PCA plots, allele frequency distributions, and AI/ML models applied to introgressed alleles.  

---
