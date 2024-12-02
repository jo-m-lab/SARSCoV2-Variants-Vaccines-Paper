# SARS-CoV-2 Variant-Vax Nasal Immunity Study (2025)

This repository contains code and analysis to replicate the findings of [Walsh et al](https://www.biorxiv.org/content/10.1101/2024.05.29.596308v1). 
In this study, we compared nasal immune responses to SARS-CoV-2 across the ancestral, Delta, and Omicron waves using nasal swab scRNA-seq. 

## Data 
The data included in this analysis is available for download from the Broad Institute Single Cell Portal ([Accession: SCP2593](https://singlecell.broadinstitute.org/single_cell/study/SCP2593)). 
The file named "Variant_Vax_obj.Rds" contains an annotated Seurat object and is used as the input for all analyses. For information on how cell types and cell subsets were identified and annotated, see the Results and Methods sections of the paper. Input for some analyses are also provided as Supplementary Tables associated with the manuscript. 

## Contents

Each notebook corresponds to a set of analyses. 

* 01_Pt_Metadata_Analysis: Comparison of demographic, timing, and clinical metadata across variant and vaccination groups (Fig. 1b-1c, Table 1, Extended Data Table 1, Extended Data Figure 1) 
* 02_Cell_Type_Analysis: Exploration of major cell types and comparisons of cell type frequencies across participant groups (Fig. 1d-1g, Extended Data Figure 2)
* 03_Compositional_Cell_Subset_Analysis: Generation of ARBOL tree, cellular composition principal component analysis, comparison of cell subset frequencies, and NMF (Figure 2, Extended Data Figure 5)
* 04_Viral_RNA_Analysis: Assessment of SARS-CoV-2 RNA distribution across participant groups and nasal cell subsets (Figure 3, Extended Data Figure 6)
* 05_Vaccination_Group_Analysis: Comparison of nasal immune responses between vaccinated and unvaccinated Delta and Omicron participants (Figure 4, Extended Data Figure 7)
* 06_COVID19_Severity_Analysis: Identification of transcriptional and cellular correlates of severity for each variant (Figure 5, Extended Data Figures 8-9)
