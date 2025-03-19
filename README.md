# Transcriptomic-Profiling-of-Type-2-Diabetes-RNA-Seq-Analysis-of-Blood-and-Pancreatic-Tissues
This project explores the molecular landscape of Type 2 Diabetes (T2D) by analyzing publicly available RNA-Seq data from blood and pancreatic tissues of healthy and T2D patients. Using bioinformatics pipelines, differentially expressed genes (DEGs) are identified.
Project Overview

This project investigates the molecular mechanisms of Type 2 Diabetes (T2D) by analyzing RNA sequencing (RNA-Seq) data from blood and pancreatic samples of healthy and T2D individuals. Using publicly available data from the Gene Expression Omnibus (GEO), the study identifies differentially expressed genes (DEGs) and explores pathways associated with glucose metabolism, insulin resistance, and pancreatic beta-cell function.

Workflow & Methodology

1. Data Acquisition

RNA-Seq datasets were retrieved from GEO using SRA Toolkit.

Samples included blood and pancreatic tissues from both healthy individuals and T2D patients.

2. Quality Control & Preprocessing

FastQC: Performed quality assessment of raw sequencing reads.

Fastp: Used for adapter trimming, quality filtering, and removing low-quality reads.

3. Read Alignment & Feature Counting

HISAT2: Aligned the preprocessed reads to the reference genome.

HTSeq: Performed feature counting to obtain raw gene expression counts.

4. Differential Expression Analysis

R packages (DESeq2, edgeR, or limma) were used to identify differentially expressed genes (DEGs) between healthy and T2D samples.

Normalization, statistical significance testing, and log-fold change calculations were performed.

5. Pathway and Functional Analysis

R packages (clusterProfiler, ReactomePA, and KEGG) were used for enrichment analysis and pathway exploration.

Gene Ontology (GO) and Kyoto Encyclopedia of Genes and Genomes (KEGG) pathways were analyzed to identify key biological functions and metabolic pathways involved in T2D.

Key Findings & Expected Outcomes

Identification of disease-specific DEGs in blood and pancreatic tissues.

Insights into biological pathways related to insulin resistance, glucose metabolism, and beta-cell dysfunction.

Discovery of potential biomarkers and therapeutic targets for T2D.

Tools & Technologies Used

Data Retrieval: SRA Toolkit

Quality Control & Preprocessing: FastQC, Fastp

Alignment & Feature Counting: HISAT2, HTSeq

DEG Analysis & Functional Interpretation: R (DESeq2, clusterProfiler, KEGG)

Future Directions

Validation of identified DEGs using independent datasets.

Integration with single-cell RNA-Seq data for a more detailed cellular landscape.

Comparative analysis of other metabolic disorders to identify common and distinct molecular signatures.
