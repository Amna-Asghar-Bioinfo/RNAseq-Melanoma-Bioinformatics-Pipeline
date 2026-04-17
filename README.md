🧬 Metastatic Melanoma: Integrative RNA-Seq & Drug Repurposing Pipeline

This project presents a comprehensive bioinformatics workflow developed to analyze transcriptomic data from metastatic melanoma. By integrating differential expression analysis with clinical drug databases, the study identifies high-confidence therapeutic targets and FDA-approved candidates for precision oncology.
📊 Dataset Detail

    Dataset ID: GSE46517

    Source: NCBI Gene Expression Omnibus (GEO)

    Description: Gene expression profiles of metastatic melanoma progression models.

🚀 The Pipeline

The workflow was executed using a combination of statistical filtering and cross-database validation:

    Data Acquisition: Retrieval and preprocessing of transcriptomic profiles from GEO.

    Differential Expression Analysis (DEA):

        Thresholds: P-value<0.05 and ∣Log2​FC∣>2.

        Total Identified: 2,297 DEGs.

    Functional Annotation: Gene ontology and functional analysis via DAVID.

    Pathway Mapping: Identifying systemic dysregulation through KEGG pathways.

    Target Identification: Isolation of "Hub Genes" (e.g., CXCL8, CDK2, PIK3CD) critical for metastasis.

    Clinical Drug Screening: * Integrated DGIdb and ChEMBL databases.

        Constraint: Filtered for FDA-Approved status only to ensure clinical relevance.

💡 Key Findings

    Regulatory Drivers: CXCL8, CDK2, and PIK3CD were identified as top-tier hub genes.

    Metastatic Pathways: High enrichment in PI3K-Akt signaling, MAPK signaling, and Cytokine-cytokine receptor interaction.

    Therapeutic Candidates: Utilizing ChEMBL for targeted screening identified Dinaciclib and Dabrafenib as high-potential FDA-approved drug candidates for the identified dysregulated network.

🛠️ Tools & Databases

    Computational Tools: Microsoft Excel (Advanced filtering), Python/R (Optional script integration).

    Databases: NCBI GEO, DAVID, KEGG.

    Drug Analysis: DGIdb, ChEMBL (High-fidelity clinical drug data).

Author

Amna Asghar BS Bioinformatics | National Centre for Bioinformatics

Focus: RNA_Seq Analysis 

Connect: [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amna-asghar-030771274)

