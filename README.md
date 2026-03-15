RNA-Seq Bioinformatics Pipeline for Metastatic Melanoma
Project Overview

This project presents an integrative bioinformatics pipeline developed to analyze transcriptomic data from metastatic melanoma samples. The aim of the study is to identify differentially expressed genes (DEGs), key regulatory pathways, and potential therapeutic targets using publicly available RNA-seq datasets.

The analysis was performed using the GSE46517 dataset from the NCBI Gene Expression Omnibus (GEO).

Dataset

Dataset ID: GSE46517
Source: NCBI GEO

The dataset contains gene expression profiles representing different stages of melanoma progression, enabling the study of molecular changes associated with metastasis.

Research Objectives

Identify significantly up-regulated and down-regulated genes in metastatic melanoma.

Perform pathway enrichment analysis to understand the biological systems involved in disease progression.

Identify hub genes that may play a major role in melanoma metastasis.

Investigate drug–gene interactions to identify potential therapeutic targets.

Bioinformatics Pipeline

The analysis workflow consists of the following stages:

Data Acquisition

Retrieval of transcriptomic dataset from the GEO database.

Differential Gene Expression Analysis

Statistical filtering using criteria:

P-value < 0.05

|LogFC| > 1

Gene Categorization

Identification of up-regulated and down-regulated genes.

Functional Annotation

Gene functional analysis using the DAVID bioinformatics tool.

Pathway Enrichment Analysis

Mapping genes to KEGG biological pathways.

Hub Gene Identification

Selection of genes strongly associated with melanoma progression.

Drug–Gene Interaction Analysis

Screening DGIdb to identify FDA-approved drugs targeting key genes.

Key Findings

2,297 differentially expressed genes (DEGs) were identified.

Several genes including CXCL8, CDK2, and PIK3CD emerged as potential regulatory drivers.

Significant enrichment was observed in the following pathways:

PI3K-Akt signaling pathway

MAPK signaling pathway

Cytokine signaling pathways

Pathways in cancer

Drug interaction analysis identified Dinaciclib and Dabrafenib as potential therapeutic candidates targeting dysregulated genes.

Significance of the Study

This project demonstrates how bioinformatics approaches can be applied to precision oncology by linking gene expression patterns with biological pathways and potential drug targets.

The pipeline provides insights into:

Molecular mechanisms driving melanoma metastasis

Candidate biomarkers for disease progression

Potential targets for therapeutic intervention

Tools & Databases Used

- NCBI GEO (Dataset source)
- DAVID Functional Annotation Tool
- KEGG Pathway Database
- DGIdb (Drug Gene Interaction Database)
- Microsoft Excel (Data organization and filtering)

Author

Amna Asghar  
BS Bioinformatics  
National Centre for Bioinformatics
