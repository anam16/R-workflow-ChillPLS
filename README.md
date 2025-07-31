# R-workflow-ChillPLS

# Estimating Chilling Requirements in Apricot Genotypes Using PLS Regression

This repository contains an **R-based workflow** to estimate **chilling requirements (CR)** in multiple **fruit tree genotypes** using **Partial Least Squares (PLS)** regression. The study focuses on **282 apricot (Prunus armeniaca L.) seedlings** from two progenies grown in **southwestern Spain**.

We used the agroclimatic functions integrated into the [`chillR`](https://cran.r-project.org/package=chillR) R package to determine genotype-specific chilling requirements.

## Contents

- `Genotipos_Pheno.Rmd`: R Markdown file with the complete analysis pipeline for PLS-based CR estimation.
- `data/Phenotype_(Phenology)BxC_GxC_Definitivo.xlsx`: Phenological data (full bloom dates) for 282 apricot genotypes.
- `data/Cieza11-25.xlsx`: Temperature records from the experimental orchard in Cieza (Southeastern Spain), spanning 2011–2025.

## Usage

1. Clone or download this repository.
2. Open the `Genotipos_Pheno.Rmd` file in RStudio.
3. Ensure all required packages are installed.
4. Run or knit the document to reproduce the analysis.

## Citation

If you use this workflow or data in your research, please cite the study appropriately. Citation details will be added once the publication is available.


