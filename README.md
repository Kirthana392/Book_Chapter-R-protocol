# Book_Chapter-R-protocol
An R-based Machine Learning Protocol to Predict Diagnostic Biomarkers in Breast Cancer using RNA-sequencing Data

On this page, we provide processed datasets used in the protocol as well as the script to download the raw counts directly from TCGA 

# Requisites for TCGA-BRCA data download:
*TCGAbiolinks*, *SummarizedExperiment*, *tidyverse*, *dplyr* 

# Datasets:
1. raw_counts_brca.csv - raw TCGA data for 1111 breast cancer samples
2. raw_counts_normal.csv -  raw TCGA data for 113 normal samples
3. metadata.csv 
4. GSE71651.csv - Independent breast cancer dataset used for evaluation of the model taken from

# Scripts:
1. TCGA_Data_Download_Script.R - Downloading TCGA-BRCA data from R and Preparing the final dataset used above
