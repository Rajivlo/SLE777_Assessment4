# bioinformatics-assignment4
R Project
## Overview

This repository contains my submission for SLE777 Assessment 4 (Applied Bioinformatics).  
It includes all code and outputs for both Part 1 (gene and tree growth data analysis) and Part 2 (comparative genomics: Barnesiella intestinihominis vs. E. coli), as well as summary plots and the main RMarkdown report.

## Repository Structure

.
├── README.md
├── analysis_report.Rmd # Main RMarkdown analysis document
├── analysis_report.html # Knitted report (HTML)
├── gene_expression.tsv # Provided RNA-seq count data
├── growth_data.csv # Provided tree circumference data
├── Barnesiella_cds.fa # CDS FASTA for Barnesiella intestinihominis
├── Ecoli_cds.fa # CDS FASTA for E. coli K12
├── scripts/
│ ├── part1_analysis.R # All R code for Part 1
│ ├── part2_analysis.R # All R code for Part 2
└── plots/
├── histogram_mean_expression.png
├── boxplot_tree_circ.png
└── ... (more as produced)

text

## Instructions to Reproduce

1. **Install R (≥4.x) & RStudio.**
2. **Install the following packages as needed:**
   - `seqinr`, `R.utils`, `dplyr`, `ggplot2`, `knitr`
3. **Clone this repo:**
git clone https://github.com/your-username/bioinformatics-assignment4.git

text
4. **Open `analysis_report.Rmd` in RStudio and click “Knit”** to generate the full report.
5. **All scripts in `scripts/` can be run separately for individual steps.**

## Data Sources

- RNA-seq: [gene_expression.tsv](https://github.com/ghazkha/Assessment4/main/gene_expression.tsv)
- Tree growth: [growth_data.csv](https://github.com/ghazkha/Assessment4/main/growth_data.csv)
- CDS:
 - Barnesiella intestinihominis: [Ensembl link](https://ftp.ensemblgenomes.ebi.ac.uk/pub/bacteria/release-62/fasta/bacteria_114_collection/barnesiella_intestinihominis_yit_11860_gca_000296465/cds/Barnesiella_intestinihominis_yit_11860_gca_000296465.Barn_inte_YIT_11860_V1.cds.all.fa.gz)  
 - E. coli K12: [Ensembl link](https://ftp.ensemblgenomes.ebi.ac.uk/pub/bacteria/release-62/fasta/bacteria_0_collection/escherichia_coli_str_k_12_substr_mg1655_gca_000005845/cds/Escherichia_coli_str_k_12_substr_mg1655_gca_000005845.ASM584v2.cds.all.fa.gz)

## Scripts

- **part1_analysis.R**: Code for all data wrangling, summary statistics, and plots for gene/tree data.
- **part2_analysis.R**: Code for sequence download, counting, composition, codon usage, and k-mer profiling.

## Outputs

- Key plots and outputs are saved in the `plots/` folder.
- The HTML/PDF report contains all figures, tables, and written explanations as required.

## References

- SLE777 Applied Bioinformatics lecture content (Weeks 6–10)
- Scripts adapted from Deakin University practical materials
- Data sources: Ensembl Bacteria, course-provided files

## Author

- Name: Raajiv Loganathan
- Deakin Student ID: s225175954
