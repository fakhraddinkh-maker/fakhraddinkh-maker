# RNA-seq Functional Enrichment Pipeline (Chicken Broiler Study)

## Overview
This project provides a fully reproducible RNA-seq analysis pipeline for broiler chicken transcriptomic data.  
It includes differential gene analysis visualization and functional enrichment (GO and KEGG).

## Features
- GO Biological Process enrichment
- KEGG pathway analysis
- Gene ID to gene name mapping using GTF annotation
- Publication-quality visualization (patchwork plots)
- Fully reproducible R pipeline

## Requirements
- R (>= 4.2)
- Packages:
  - dplyr
  - ggplot2
  - clusterProfiler
  - enrichplot
  - gprofiler2
  - rtracklayer
  - patchwork

## How to Run
```r
setwd("your_path/broiler-rnaseq-pipeline")
source("code/full_pipeline.R")