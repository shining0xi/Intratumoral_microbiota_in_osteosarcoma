# Intratumoral_microbiota_in_osteosarcoma
This is the GitHub repository for “Spatio-temporal and cellular heterogeneity of intratumoral microbiota in osteosarcoma” project.

# Related repositories
There are several other repositories related to this paper:
* Phylogenetic Investigation of Communities by Reconstruction of Unobserved States 2 (PICRUSt2) pipeline was adopted to predict bacterial function [PICRUSt2](https://github.com/picrust/picrust2)
* CSI-Microbes computational pipeline was used to identify microbial-derived transcripts from droplet-based scRNA-seq data [CSI-Microbes](https://github.com/ruppinlab/CSI-Microbes-identification)

# File structure description
* Microbial_bioinformatic_analyses
```
Microbial_bioinformatic_analyses /
├── loading R packages
├── Alpha diversity
├── Beta diversity
├── Top bacteria
├── Aitchison dissimilarities
├── The linear discriminant analysis (LDA) e /ffect size (LEfSe)
├── Phylogenetic Investigation of Communities by Reconstruction of Unobserved States 2 (PICRUSt2) visualization
```
* Single_cell_intratumoral_microbiota_analyses
```
Single_cell_intratumoral_microbiota_analyses /
├── loading R packages
├── Single cell sequencing data visualization
│   ├── Uniform Manifold Approximation and Projection (UMAP)
│   ├── Proportion of cell types
│   ├── Percentage of cells detected microbes
│   ├── Proportion of microbes
│   ├── Average microbe count
│   ├── Microbe Positive cells among cell types by samples
├── Single-cell copy-number variation
├── Differential gene expression and gene set enrichment analysis
```
