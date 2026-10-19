# Explicating Candidate miRNAs Involved in Inflammatory Pathways Across Pulmonary, Cardiovascular, Neurological, and Pancreatic Diseases: A Machine Learning and SHAP-Based Approach

## ⚠️ Academic & Publication Notice
> **Manuscript Status:** Publication Pipeline / In Preparation
> To strictly comply with peer-review integrity guidelines and safeguard proprietary feature-selection architectures prior to official publication, the raw backend data-preprocessing scripts and model training code are maintained in a secure, **private repository**. Full codebase access can be seamlessly granted to PhD admissions committees, reviewers, or prospective Principal Investigators (PIs) upon direct request via a secure contributor link.

---

## 📌 Project Abstract & Analytical Framework
This project presents an advanced multi-disease transcriptomic classification framework. The pipeline scales previous multi-system architectures by integrating pancreatic conditions alongside pulmonary, cardiovascular, and neurological states, analyzing pancreatic inflammation-driven mechanisms in direct relation to multi-system disorders.

### 📊 Computational Workflow & Performance Metrics
* **Objective:** Extend the multi-disease transcriptomic classification framework to incorporate pancreatic inflammation, providing deep insights into common inflammation-driven mechanisms underlying pancreatic conditions.
* **Disease Scope:** Chronic Obstructive Pulmonary Disease (**COPD**), **Lung Cancer**, Myocardial Infarction (**MI**), Multiple Sclerosis (**MS**), **Pancreatitis**, and Pancreatic Ductal Adenocarcinoma (**PDAC**).
* **Validation & Feature Engineering:** The baseline Random Forest model achieved **71% accuracy**, which successfully scaled to **72% upon independent external validation**.
* **Iterative Optimization:** Retraining the classifier strictly utilizing the **SHAP-selected top 20 optimal miRNA features** dramatically boosted model performance, yielding a final predictive accuracy of **79%**, indicating significantly enhanced predictive performance.
* **Pathway Convergence:** Key predictive targets were found to converge heavily on cross-disease metabolic, inflammatory, and hypoxic pathways (**NF-κB, PI3K/Akt, MAPK, Wnt/β-catenin, and HIF-1α**), regulating systemic cytokine production, hypoxia, and cellular proliferation across these diseases.

---

## 🛠️ Computational Environment & Stack
* **Feature Selection & ML:** Data science processing stack for Random Forest implementation, multi-class array configurations, and benchmark evaluations.
* **Explainable AI:** Model-agnostic frameworks for extraction of local and global feature attribution interpretations (beeswarm layouts and predictive impact summary plots).
* **Bioinformatics Pipeline:** Public multi-cohort transcriptomic matrices compiled for systemic cross-comparisons.

---

## 📂 Repository Contents
* `README.md` — Complete theoretical, methodological, and architectural framework.
* `plots/` *(Optional)* — Folder reserved for peer-reviewed SHAP summary beeswarm plots, Random Forest ROC curves, and pathway network graphs.

---

## 📄 Contact & Secure Code Requests
For academic inquiries, potential PhD advising discussions, or to request secure, private access to the backend machine learning scripts for verification, please reach out directly:
* **Researcher:** Aida Ferrutia Peter
* **Email:** aidaferrutia10@gmail.com
* **Institution:** Anna University
