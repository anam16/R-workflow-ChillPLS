# Data Folder

This folder contains the datasets used in the analysis of chilling requirements for apricot genotypes.

## Files

### `Phenotype_(Phenology)BxC_GxC_Definitivo.xlsx`

- **Description**: Phenological dataset containing full bloom dates for 282 apricot (Prunus armeniaca L.) genotypes from two breeding progenies (BxC and GxC).
- **Content**:
  - Each row represents a unique genotype.
  - Columns correspond to bloom dates for different seasons (2012–2025).
- **Source**: Field phenological observations collected in southwestern Spain.

### `Cieza11-25.xlsx`

- **Description**: Daily temperature data from the experimental orchard located in Cieza, Southeastern Spain, covering the years 2011 to 2025.
- **Content**:
  - `Day`: Day of the month.
  - `JDay`: Julian day (1–365/366).
  - `Month`: Month number.
  - `Year`: Year of observation.
  - `Tmax`: Daily maximum temperature (°C), stored with comma decimal format (e.g., "14,46").
  - `Tmin`: Daily minimum temperature (°C), also in comma decimal format.

## Usage Notes

- These datasets are used in the R Markdown analysis script `Genotipos_Pheno.Rmd`.
