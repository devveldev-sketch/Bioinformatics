# 🧬 Predictive Analysis of ACVR1 Gene Variants in Fibrodysplasia Ossificans Progressiva (FOP)

## 📌 Overview

This project presents a **bioinformatics and machine learning framework** to analyze and predict the pathogenicity of genetic variants in the **ACVR1 gene**, associated with **Fibrodysplasia Ossificans Progressiva (FOP)**.

The study integrates **multiple biological datasets** including genomic sequences, variant data, and gene expression profiles to extract insights and build a predictive model.

---

## 🎯 Objective

* Analyze ACVR1 gene variants using bioinformatics techniques
* Identify mutation patterns and hotspots
* Predict pathogenicity of genetic variants
* Develop an integrated computational pipeline

---

## 📂 Project Structure

```id="c6fdmk"
Bioinformatics/
│── Bio_Final.ipynb      # Code (EDA + ML model)
│── Output.docx          # Results and analysis
│── .gitignore           # Excludes dataset files
```

---

## 📊 Datasets Used

This project uses **multiple datasets from different bioinformatics repositories**:

### 1. ClinVar Dataset

* Contains genetic variants and clinical significance labels
* Used as the **primary dataset for machine learning**

### 2. NCBI Gene Dataset

* Provides detailed information about the ACVR1 gene
* Used for biological context and interpretation

### 3. NCBI Nucleotide Dataset (FASTA)

* Contains gene sequences
* Used for sequence analysis using Biopython

### 4. GEO Dataset (Gene Expression)

* Contains gene expression profiles across samples
* Used for exploratory gene expression analysis

👉 Dataset access (external due to large size):
https://drive.google.com/drive/folders/141thggtbQe_oIIjvvmCjAygmAOMQV92t?usp=sharing

---

## ⚙️ Methodology

### Data Pipeline

1. Data Collection from multiple sources
2. Data Preprocessing and cleaning
3. Sequence Analysis using Biopython
4. Feature Extraction (mutation position, mutation type)
5. Exploratory Data Analysis (EDA)
6. Mutation Hotspot Identification
7. Gene Expression Analysis
8. Handling class imbalance using SMOTE
9. Model training using Random Forest
10. Model evaluation and validation

---

## 🤖 Machine Learning Model

* Algorithm: **Random Forest Classifier**
* Features:

  * Mutation position
  * Mutation type

---

## 📈 Results

* **Accuracy:** ~95%
* **ROC-AUC:** ~0.97
* **Cross-validation:** ~0.94

### Key Insights

* High number of **variants of uncertain significance (VUS)**
* **Missense mutations** dominate
* Mutation **position plays a crucial role**
* Identified important mutation hotspots

---

## 🧠 Conclusion

This project demonstrates the effectiveness of combining **multiple bioinformatics datasets with machine learning** to analyze genetic variants and predict disease-related mutations.

---

## 🔮 Future Scope

* Include structural and evolutionary features
* Apply deep learning models
* Extend to multi-omics integration
* Improve prediction of uncertain variants

---

## 👩‍💻 Author

Devadharshini S & Karan K 

VIT Chennai 

Integrated M.Tech CSE (Business Analytics)
