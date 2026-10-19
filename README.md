# Explicating Candidate miRNAs Involved in Inflammatory Pathways Across Pulmonary, Cardiovascular, Neurological, and Pancreatic Diseases: A Machine Learning and SHAP-Based Approach

## ⚠️ Academic & Publication Notice
> **Manuscript Status:** Publication Pipeline / In Preparation
> To strictly comply with peer-review integrity guidelines and safeguard proprietary feature-selection architectures prior to official publication, the raw backend data-preprocessing scripts and model training code are maintained in a secure, **private repository**. Full codebase access can be seamlessly granted to PhD admissions committees, reviewers, or prospective Principal Investigators (PIs) upon direct request via a secure contributor link.

---

## 📌 Project Abstract & Study Design
This project was designed to systematically investigate the role of miRNA-mediated regulation in inflammatory pathways across multiple disease groups, with a strict emphasis on identifying both shared and disease-specific molecular mechanisms driven by chronic inflammation and immune dysregulation.



### 📊 Study: Multi-System Interaction Analysis with Pancreatic Integration & External Validation
* **Objective:** Extended the core investigation to include pancreatic diseases alongside pulmonary, cardiovascular, and neurological conditions. Broadening the analysis to evaluate pancreatic inflammation enabled deep insights into the common inflammation-driven mechanisms underlying pancreatic conditions.
* **Data Source:** To further examine pancreatic comorbidities, miRNA datasets mapping **Lung Cancer, Chronic Obstructive Pulmonary Disease (COPD), Multiple Sclerosis (MS), Myocardial Infarction (MI), Pancreatitis, and Pancreatic Ductal Adenocarcinoma (PDAC)** were analyzed using an identical framework.
* **Validation & Feature Engineering:** The baseline Random Forest model achieved **71% accuracy**, which successfully scaled to **72% upon independent external validation**.
* **Iterative Optimization:** Retraining the classifier strictly using the **SHAP-selected top 20 optimal miRNA features** dramatically boosted model performance, yielding a final predictive accuracy of **79%**, indicating enhanced predictive performance.
* **Pathway Convergence:** Key predictive targets were found to converge heavily on cross-disease metabolic, inflammatory, and hypoxic pathways (**NF-κB, PI3K/Akt, MAPK, Wnt/β-catenin, and HIF-1α**), regulating systemic cytokine production, hypoxia, and cellular proliferation across these diseases.

---
## 🛠️ Computational Environment & Stack
The machine learning pipeline and explainable AI architectures were constructed using standard bioinformatic and data science toolkits:
* **Batch Correction:** `ComBat` framework for cross-platform data harmonization.
* **Feature Selection & ML:** Python machine learning stack (`scikit-learn`, `numpy`, `pandas`) for Random Forest implementation and benchmarking.
* **Explainable AI:** `shap` framework for local and global feature attribution interpretations (beeswarm and summary plots).
* **Bioinformatics Core:** Datasets curated from the NCBI Gene Expression Omnibus (GEO) repository.

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
