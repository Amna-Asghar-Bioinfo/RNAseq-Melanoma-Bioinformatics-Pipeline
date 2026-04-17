# Metastatic Melanoma: Integrative RNA-Seq & Drug Repurposing Pipeline

A comprehensive bioinformatics workflow analyzing transcriptomic data from metastatic melanoma.
Integrates differential expression analysis with clinical drug databases to identify
high-confidence therapeutic targets and FDA-approved candidates for precision oncology.

---

## Dataset

| Field       | Detail                                                              |
|-------------|---------------------------------------------------------------------|
| Dataset ID  | GSE46517                                                            |
| Source      | NCBI Gene Expression Omnibus (GEO)                                  |
| Description | Gene expression profiles of metastatic melanoma progression models  |

---

## Pipeline

01 — Data Acquisition
Retrieval and preprocessing of transcriptomic profiles from the NCBI Gene Expression Omnibus.

02 — Differential Expression Analysis
Statistical filtering to identify 2,297 differentially expressed genes.
Thresholds: P-value < 0.05 and |Log2FC| > 2.

03 — Functional Annotation
Gene ontology and functional enrichment analysis via DAVID.

04 — Pathway Mapping
Systemic dysregulation mapped through KEGG pathway analysis.

05 — Hub Gene Identification
Isolation of key regulatory drivers critical for metastatic progression.
Identified: CXCL8, CDK2, PIK3CD.

06 — Clinical Drug Screening
Cross-database validation against DGIdb and ChEMBL, filtered exclusively
for FDA-approved compounds to ensure clinical relevance.

---

## Key Findings

Regulatory Drivers
CXCL8, CDK2, and PIK3CD identified as top-tier hub genes critical for metastatic regulation.

Metastatic Pathways
High enrichment in PI3K-Akt signaling, MAPK signaling, and Cytokine-cytokine receptor interaction.

Therapeutic Candidates
Dinaciclib and Dabrafenib identified as high-potential FDA-approved drug candidates
via ChEMBL targeted screening of the dysregulated gene network.

---

## Tools & Databases

| Category        | Tools                           |
|-----------------|---------------------------------|
| Computational   | Microsoft Excel, Python / R     |
| Databases       | NCBI GEO, DAVID, KEGG           |
| Drug Analysis   | DGIdb, ChEMBL                   |

---

## Author

Amna Asghar
BS Bioinformatics — National Centre for Bioinformatics

Focus: RNA-Seq Analysis

https://www.linkedin.com/in/amna-asghar-030771274
