# Forensic-Ready Explainable Intrusion Detection with Temporal Graph Modeling and Counterfactual Cyber Defense

## Description
This repository provides a comprehensive, reproducible implementation of a forensic-ready and explainable intrusion detection framework designed for modern cyber-physical systems, including Low-Altitude Intelligent Transportation Systems (LITS) such as UAV and drone-based networks.

The proposed framework moves beyond traditional detection-centric intrusion detection systems by introducing a unified, decision-oriented architecture that combines machine learning, temporal graph modeling, explainable artificial intelligence (XAI), and counterfactual reasoning. The goal is not only to detect malicious activities but also to support interpretable, actionable, and forensic-ready cyber defense.

In dynamic and distributed environments such as UAV networks and intelligent transportation systems, security monitoring requires the ability to understand evolving attack patterns, explain decisions to human operators, and provide guidance for mitigation. This repository addresses these challenges through an integrated pipeline that transforms raw network data into structured knowledge representations and decision-support insights.

---

## Key Contributions

- Development of a forensic-ready intrusion detection framework
- Integration of temporal graph modeling for dynamic attack analysis
- Incorporation of explainable AI techniques (SHAP, LIME)
- Counterfactual reasoning for actionable cyber defense (DiCE)
- Decision-support oriented architecture for human analysts
- Fully reproducible pipeline with Google Drive integration

---

## Repository Structure

.
├── notebooks/
│   └── forensic_ready_xai_ids_notebook.ipynb
├── data/
│   └── (datasets or links)
├── outputs/
│   ├── figures/
│   ├── tables/
│   └── reports/
├── src/
│   ├── preprocessing.py
│   ├── modeling.py
│   ├── explainability.py
│   ├── graph_modeling.py
│   └── counterfactuals.py
├── requirements.txt
└── README.md

---

## Methodology Overview

1. Data Preprocessing  
   Cleaning, normalization, encoding, and feature engineering.

2. Intrusion Detection  
   Training ML models (Random Forest, XGBoost).

3. Temporal Graph Modeling  
   Construction of dynamic interaction graphs.

4. Explainability  
   SHAP (global) and LIME (local) explanations.

5. Counterfactual Analysis  
   DiCE-based generation of mitigation scenarios.

6. Forensic Reporting  
   Export of structured outputs and analytics.

---

## Installation

```bash
git clone https://github.com/your-username/forensic-xai-ids.git
cd forensic-xai-ids
pip install -r requirements.txt
```

---

## Usage

Run the notebook in Google Colab:

```python
from google.colab import drive
drive.mount('/content/drive')
```

Outputs will be saved in:

/content/drive/MyDrive/Outputs/Forensic_Ready_XAI_IDS/

---

## Outputs

- Confusion matrices
- Feature importance plots (SHAP)
- Local explanations (LIME)
- Temporal graph insights
- Suspicious entity tables
- Counterfactual scenarios
- Summary reports

---

## Applications

- UAV and drone network security
- Cyber-physical system protection
- Intelligent transportation systems
- Explainable cybersecurity analytics

---

## Citation

@misc{Hamam2026ForensicXAIIDS,
  title={Forensic-Ready Explainable Intrusion Detection with Temporal Graph Modeling and Counterfactual Cyber Defense},
  author={Habib Hamam et al.},
  year={2026},
  note={GitHub repository}
}

---

## License
MIT License

---

## Contact
Habib Hamam
