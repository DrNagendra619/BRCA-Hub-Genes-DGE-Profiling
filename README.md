# 🧬 BRCA-Hub-Genes-DGE-Profiling

[![Platform: GEPIA2](https://img.shields.io/badge/Platform-GEPIA2-blue.svg)](http://gepia2.cancer-pku.cn/#index)
[![Cancer Type: BRCA](https://img.shields.io/badge/Cancer-Breast_Invasive_Carcinoma-pink.svg)]()
[![Dataset: TCGA + GTEx](https://img.shields.io/badge/Dataset-TCGA%20%2B%20GTEx-green.svg)]()
[![Status: Active](https://img.shields.io/badge/Status-Active-success.svg)]()

---

## 📊 Differential Gene Expression (DGE) Profiling of Top 10 Hub Genes in BRCA

Differential gene expression (DGE) profiling of **top network-derived hub genes** in **Breast Invasive Carcinoma (BRCA)** using the **GEPIA2 platform**.

---

# 📌 Overview

This repository contains the **Differential Gene Expression (DGE) profiling results** for the **top 10 hub genes** identified as potential **key therapeutic targets** in **Breast Invasive Carcinoma (BRCA)**.

Following the identification of these genes through **network analysis of gene interactions (using degree centrality)**, their **expression levels were profiled** to compare:

- **Tumor tissues**
- **Normal tissues**

This comparison helps determine the **differential expression patterns** associated with breast cancer.

---

# 🧪 Methodology

The expression profiling was conducted using the **GEPIA2 web tool**.

🔗 **GEPIA2 Platform:**  
http://gepia2.cancer-pku.cn/#index

### Dataset Information

- **Cancer Type:** Breast Invasive Carcinoma (BRCA)
- **Tumor Dataset Source:** TCGA
- **Normal Dataset Source:** GTEx

### Sample Size

- **Tumor samples (T):** 1085  
- **Normal samples (N):** 291

### Expression Metric

```
Log2(TPM + 1)
```

### Visualization

- **Box plots** comparing expression distributions
- **Tumor samples:** Red color
- **Normal samples:** Grey color

### Statistical Significance

- A **red asterisk (*)** indicates **statistically significant differential expression** between tumor and normal groups.

---

# 📈 Results Summary

The **Differential Gene Expression (DGE) analysis** produced highly **consistent and statistically significant results** across the evaluated hub genes.

### 🔺 Consistent Upregulation

- All **10 identified hub genes** show **statistically significant upregulation**
- Expression levels are **higher in BRCA tumor tissues** compared to **normal tissues**

### 🧬 Clinical Relevance

The strong overexpression observed in:

```
Tumor group (T = 1085)
Normal group (N = 291)
```

supports the hypothesis that these **network-derived hub genes play a critical role in breast cancer pathogenesis**.

These genes may serve as:

- **Potential diagnostic biomarkers**
- **Therapeutic targets**
- **Key molecular indicators of tumor progression**

---

# 📂 Repository Contents

The repository contains the following file:

### 📄 `DGE_Profiling.pdf`

**Description**

Complete exported document containing the **10 comparative expression box plots** generated from **GEPIA2**.

**Includes**

- Tumor vs Normal expression comparisons
- Statistical significance indicators
- Visualization of hub gene expression patterns

---

# 👨‍🔬 Author

**Nagendra**

🔗 GitHub Profile  
https://github.com/DrNagendra619

---

⭐ If you find this repository useful, consider **starring the project** to support the research.
