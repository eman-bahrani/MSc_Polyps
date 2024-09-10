# Polyp Fiction: Identification of Biomarkers in Precancerous Lesions Denoting Risk of Recurrence

This repository contains the code and resources associated with my master's thesis, "Polyp Fiction: Identification of Biomarkers in Precancerous Lesions Denoting Risk of Recurrence", submitted in fulfilment of the requirements for the degree MSc Bioinformatics and Computational Genomics at QUB.

## Overview

The project focuses on identifying biomarkers from clinicopathological (clinpath) and transcriptomic data (raw_expr and norm_expr) to predict the recurrence risk of colorectal polyps and potential progression to CRC. The analysis was carried out across several stages, from data quality control to cluster analysis, as outlined below.

## Files and Directories

### 1. Clinpath QC

This script handles the QC of clinicopathological data, including filtering, consistency checks, and basic descriptive statistics to ensure data readiness for further analysis.

### 2. Clinpath Analysis

Here, the clinicopathological data is used for exploratory and comparative analysis, identifying associations between clinical features and recurrence risk. This file includes correlation analysis, survival analysis, and risk stratification.

### 3. Transcriptomic QC

This script includes quality control for raw and normalised gene expression data. This stage ensures that only high-quality, normalised data is passed forward for downstream analysis.

### 4. Whole Cohort Analysis

In this section, differential expression analysis, pairwise GSEA, and ssGSEA were conducted. This file identifies key pathways and biological processes involved in recurrence risk by comparing the gene expression profiles between patients with and without future polyps or CRC.

### 5. Clusters Analysis

This part involves utilising unsupervised clustering of the transcriptomic data to identify subgroups within the cohort. It includes comparison between clusters in terms of clinical and transcriptomic feature in addition to differential expression analysis, pairwise GSEA, ssGSEA and survival analyses.

### 6. Extra Plots

Any additional visualisations, including plots created for exploration or for specific requests that weren't included in the main analyses, are stored here. These may assist in illustrating the findings or exploring outliers.
