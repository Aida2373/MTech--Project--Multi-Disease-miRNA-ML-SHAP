# Explicating Candidate miRNAs Involved in Inflammatory Pathways Across Pulmonary, Cardiovascular, and Neurological Diseases: A Machine Learning and SHAP-Based Approach

## ⚠️ Academic & Publication Notice
> **Manuscript Status:** Publication Pipeline / In Preparation
> To strictly comply with peer-review integrity guidelines and safeguard proprietary feature-selection architectures prior to official publication, the raw backend data-preprocessing scripts and model training code are maintained in a secure, **private repository**. Full codebase access can be seamlessly granted to PhD admissions committees, reviewers, or prospective Principal Investigators (PIs) upon direct request via a secure contributor link.

---

## 📌 Project Abstract & Analytical Framework
This project systematically investigates the role of miRNA-mediated regulation in inflammatory pathways across multiple systemic groups. The primary focus is to isolate robust biomarkers and identify both shared and disease-specific molecular mechanisms driven by chronic inflammation and immune dysregulation.

### 📊 Computational Workflow & Performance Metrics
* **Objective:** Explore miRNA-mediated regulation across conditions strongly associated with chronic inflammation and immune dysregulation to isolate common and distinct transcriptomic signatures.
* **Disease Scope:** Chronic Obstructive Pulmonary Disease (**COPD**), **Lung Cancer**, Myocardial Infarction (**MI**), Heart Failure (**HF**), Multiple Sclerosis (**MS**), and **Glioma**.
* **Model Benchmarking:** Following extensive preprocessing of raw peripheral blood profiles, four distinct machine learning classifiers were developed and benchmarked. The **Random Forest** architecture achieved top-tier baseline performance with a predictive accuracy of **75%**.
* **Explainable AI Framework:** The top 20 predictive features were isolated using model-agnostic feature importance and thoroughly interpreted using **SHAP analysis** to evaluate the exact mathematical contributions of candidate miRNAs.
* **Biological Translation:** Functional pathways analysis revealed that the top-contributing miRNAs converge on critical inflammatory and oncogenic pathways including **NF-κB, PI3K/Akt, MAPK, and HIF-1α**, mapping the precise links between immune activation, oxidative stress, and multi-organ tumorigenesis.

#### ⚠️ Analysis of External Validation Constraints
To evaluate generalizability, independent external validation datasets were combined and harmonized using batch-effect correction. However, validation yielded lower accuracy due to several critical data constraints:
* **Missing Class Representation:** Validation datasets for specific conditions (notably **glioma and heart failure**) were entirely unavailable in the public domain, leading to incomplete representation of training classes.
* **Feature Space Inconsistencies:** The validation datasets originated from independent studies with varying experimental profiling platforms, resulting in limited feature overlap.
* **Data Heterogeneity:** Residual acquisition and preprocessing differences introduced technical variability that persisted despite batch correction, highlighting a strict need for standardized, large-scale multi-disease miRNA datasets.

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
* **Researcher:** Aida [Your Last Name]
* **Email:** [Your Academic Email Address]
* **Institution:** [Your Current University/Institute]
