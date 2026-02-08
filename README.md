# AI Agent for Continuous Internal Audit in Banking

This repository contains the full implementation of an **AI agent–based continuous internal audit framework** for the banking sector.  
The framework is designed to support **risk-based audit decision-making**, **fraud monitoring**, and **governance oversight** using publicly available Canadian financial fraud data.

The project accompanies an academic research paper prepared for submission to the **Journal of International DBA Studies (JIDS)**.

---

##  Project Overview

Traditional internal audit functions in banking are often periodic and retrospective, limiting their ability to respond to rapidly evolving fraud and compliance risks. This project proposes and implements an **AI-driven audit agent** that enables:

- Continuous risk assessment  
- Explainable anomaly detection  
- Audit-ready decision support  
- Scalable audit prioritization without transaction-level loss data  

The system is **audit-aligned**, **explainable**, and **privacy-aware**, making it suitable for real-world banking environments.

---

##  Dataset

The framework uses publicly available data from the **Canadian Anti-Fraud Centre (CAFC)**:

- **Dataset:** Fraud and Cybercrime Reports (2021–2025)  
- **Records:** 350,361 cases  
- **Source:** Government of Canada Open Data Portal  

Due to confidentiality constraints, financial losses are reported in categorical ranges rather than exact amounts. The implementation accounts for this using **audit-appropriate risk proxies**.

---

##  Methodology Summary

1. Data harmonization (bilingual schema handling)  
2. Exploratory data analysis (EDA)  
3. Audit risk feature engineering  
4. Composite audit risk scoring  
5. Continuous anomaly detection  
6. AI audit agent reasoning layer  

---

##  Key Outputs

- Composite audit risk scores  
- Anomaly flags for continuous monitoring  
- Explainable audit findings  
- CSV outputs for reproducibility  
- LaTeX-ready figures and tables  

---

##  Installation

```bash
pip install pandas numpy scikit-learn matplotlib
```

(Optional)
```bash
pip install sentence-transformers
```

---

##  Research Context

This project supports a DBA-level research study on **AI agents in banking internal audit**, focusing on explainability, governance alignment, and managerial decision support.

Target journal: **Journal of International DBA Studies (JIDS)**

---

##  Author

**Ayesha Anzer**  
Artificial Intelligence & Risk Analytics  
Canada

---

##  License

Academic and research use only. Please cite appropriately.
