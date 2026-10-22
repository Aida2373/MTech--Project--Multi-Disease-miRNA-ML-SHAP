# Explicating miRNA Biomarkers Involved in Inflammatory Pathways Across Pulmonary, Cardiovascular, Neurological, and Pancreatic Diseases: A Machine Learning and SHAP-Based Approach

## ⚠️ Academic & Publication Notice
> **Manuscript Status:** Publication Pipeline / In Preparation
> To strictly comply with peer-review integrity guidelines and safeguard proprietary feature-selection architectures prior to official publication, the raw backend data-preprocessing scripts and model training code are maintained in a secure, **private repository**. Full codebase access can be seamlessly granted to PhD admissions committees, reviewers, or prospective Principal Investigators (PIs) upon direct request via a secure contributor link.

---

## 📌 Project Abstract & Analytical Framework
Pulmonary, cardiovascular, neurological, and pancreatic diseases are complex disorders characterized by shared inflammatory and molecular dysregulation. MicroRNAs (miRNAs) function as vital post-transcriptional regulators of inflammation, metabolic functions, and immune responses across these conditions. 

This research establishes an integrative machine learning and SHAP (SHapley Additive exPlanations) framework for multi-disease classification using peripheral blood miRNA expression profiles to isolate robust biomarkers and decipher common inflammation-driven mechanisms across four major disease classes.

### 📊 Computational Workflow & Performance Metrics
* **Objective:** Design and validate a multi-disease transcriptomic classification framework across pulmonary, cardiovascular, neurological, and pancreatic conditions to extract highly generalizable disease signatures.
* **Disease Scope:** Chronic Obstructive Pulmonary Disease (**COPD**), **Lung Cancer**, Myocardial Infarction (**MI**), Multiple Sclerosis (**MS**), **Pancreatitis**, and Pancreatic Ductal Adenocarcinoma (**PDAC**).
* **Baseline Benchmarking:** Following multi-cohort matrix preprocessing, an ensemble **Random Forest** classification model was developed, achieving an initial baseline accuracy of **71%**.
* **Independent External Validation:** To rigorously evaluate model generalizability across platform variations, the classifier was subjected to testing against unseen independent datasets, successfully validating its predictive performance at **72% accuracy**.
* **SHAP-Driven Iterative Optimization:** Model-agnostic feature engineering was applied to refine the target feature space. Retraining the classifier strictly utilizing the **SHAP-selected top 20 optimal miRNA features** boosted final predictive capabilities, yielding an optimized multi-class classification accuracy of **79%**.
* **Pathway Convergence & Biological Signatures:** Downstream biological annotation revealed that the prioritized high-importance features converge significantly on core cross-disease metabolic, inflammatory, and hypoxic pathways—specifically **NF-κB, PI3K/Akt, MAPK, Wnt/β-catenin, and HIF-1α**. These targets show a unified regulatory influence over systemic cytokine production, hypoxia, and cellular proliferation across both inflammatory and malignant disease profiles.

---

## 🛠️ Computational Environment & Stack
The machine learning pipeline and explainable AI architectures were constructed using robust data science toolkits:
* **Feature Selection & ML:** Data science processing stack for Random Forest implementation, multi-class array configurations, and benchmark evaluations.
* **Explainable AI:** Model-agnostic frameworks (`shap`) for extraction of local and global feature attribution interpretations, including beeswarm layouts and predictive impact summary plots.
* **Bioinformatics Pipeline:** Public multi-cohort transcriptomic matrices compiled for systemic cross-comparisons.

---

## 📂 Repository Contents
* `README.md` — Complete theoretical, methodological, and architectural framework.
* `plots/` *(Optional Upload)* — Folder reserved for peer-reviewed SHAP summary beeswarm plots, Random Forest ROC curves, and pathway network graphs.

---

## 📄 Contact & Secure Code Requests
For academic inquiries, potential PhD advising discussions, or to request secure, private access to the backend machine learning scripts for verification, please reach out directly:
* **Researcher:** Aida Ferrutia Peter
* **Email:** aidaferrutia10@gmail.com
* **Institution:** Anna University
