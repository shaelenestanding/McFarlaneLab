# McFarlaneLab
This code was used for Shalene Standing's BHSc Undergraduate Thesis project at the University of Calgary. All code is written in R. 

This code is a workflow for single-cell RNA-Sequencing data for the zebrafish eye at 5 days post-fertilization. All code was written for the thesis. This project uses the Seurat package by the Satija lab (https://satijalab.org/seurat/). 

Dissociated eye cells were gathered by Shaelene Standing and Carrie Hehr in the McFarlane Lab. Sequencing of samples was done by the Biernaskie Lab. For this project wild type and mutant (Sema3fa ca304 - _sema3fa_ knockout zebrafish were used). 40 eyes for each genotype were disociated.

The main function (scRNA-Seq_Workflow) inputs a h5 file (available by request by contacting Sarah McFarlane) that contains the sequening reads and normalizes the samples. Following this, the program runs UMAP dimensionality reduction and visualizes all the cells in the retina as well as those specifically in the ciliary marginal zone for downstream analysis and interpretation.

A file of all the differentially expressed genes for all cell types in the eye is included in this project as an excel file. 
