# ER-Treatment-Analysis-using-NLP
ER Treatment Analysis: Medication &amp; Chief Complaint Study


This repository contains analysis of Emergency Room (ER) treatment patterns, chief complaints, and their association with patient outcomes using Python, NLP, and statistical methods.

## **Project Objectives**

1. **Drug Co-Occurrence & Prescription Analysis**  
   - Identify frequently co-prescribed medications and treatment patterns.  
   - Visualize relationships using heatmaps and network graphs.

2. **Chief Complaint NLP & Symptom Topic Discovery**  
   - Clean and normalize free-text complaints.  
   - Apply LDA topic modeling to identify symptom clusters.

3. **Outcome Validation & Risk Quantification**  
   - Assess associations between treatments/complaints and patient outcomes.  
   - Calculate odds ratios and p-values using Chi-squared and Fisher’s exact tests.

---

## **Project Structure**

- `data/`: Raw dataset(s) used for analysis  
- `notebooks/`: Jupyter notebooks for step-by-step analysis  
- `scripts/`: Python scripts with reusable functions for preprocessing, analysis, and statistics  
- `outputs/`: Generated figures, wordclouds, and reports  
- `requirements.txt`: Python packages required  

---

## Key Features & Outputs

- **Medication Insights**
  - Top prescribed medications
  - Medication co-occurrence networks
  - Clustered patient treatment profiles

- **Chief Complaint Analysis**
  - Top complaints and their frequency
  - Word clouds for visual exploration
  - LDA topic modeling for symptom patterns

- **Outcome Association**
  - Mortality distribution across complaints and medications
  - Statistical testing (Chi-squared & Fisher’s exact)
  - Odds ratios for high-risk complaints


---


## **How to Run**

1. Clone the repo:  
```bash
git clone https://github.com/yourusername/ER-Treatment-Analysis.git
cd ER-Treatment-Analysis

pip install -r requirements.txt

```


---

## **License**

MIT License – free to use and adapt for research purposes.


> Data is available upon request. 
