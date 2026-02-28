# BRCA-Hub-Genes-DGE-Profiling
Differential gene expression (DGE) profiling of top network-derived hub genes in Breast Invasive Carcinoma (BRCA) using the GEPIA2 platform.
# Differential Gene Expression (DGE) Profiling of Top 10 Hub Genes in BRCA

## Overview
This repository contains the Differential Gene Expression (DGE) profiling results for the top 10 hub genes identified as potential key therapeutic targets in Breast Invasive Carcinoma (BRCA). Following the identification of these genes via network analysis of gene interactions (using degree centrality), their expression levels were profiled to compare tumor tissues against normal tissues. 

## Methodology
The expression profiling was conducted using the **[GEPIA2 web tool](http://gepia2.cancer-pku.cn/#index)** (Gene Expression Profiling Interactive Analysis). 
* **Dataset:** Breast Invasive Carcinoma (BRCA) from TCGA and normal tissue data from GTEx.
* **Sample Size:** Tumor samples (T) = 1085; Normal samples (N) = 291.
* **Expression Metric:** Log2(TPM + 1) transformed expression data.
* **Visualization:** Box plots comparing expression distributions between tumor (red) and normal (grey) states.
* **Statistical Significance:** A red asterisk (*) denotes a statistically significant differential expression between the groups.

## Results Summary
The DGE analysis yielded highly consistent and significant results across the evaluated targets:

* **Consistent Upregulation:** All 10 identified hub genes demonstrate a statistically significant upregulation in BRCA tumor tissues compared to normal tissues. 
* **Clinical Relevance:** The marked overexpression of these network-derived genes in the tumor group (T=1085) versus the normal group (N=291) strongly supports their role in breast cancer pathogenesis and reinforces their potential viability as diagnostic markers or therapeutic targets. 

## Repository Contents
* `DGE_Profiling.pdf`: The complete exported document containing the 10 comparative expression box plots generated from GEPIA2.

## Author
**Nagendra** GitHub: [@DrNagendra619](https://github.com/DrNagendra619)
