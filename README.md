# Investigating the Role of Spatial and Non-Spatial Attention in Visual Short-Term Memory

### Overview
This repository contains cleaned data and the finished article from my undergraduate dissertation for my BSc Psychology with Cognitive Neuroscience degree.  

The study investigated how spatial and non-spatial attention independently influence visual short-term memory (VSTM) performance, comparing recall accuracy for colour and orientation features. The project tested predictions from both slot-based and resource-based models of VSTM.

### Objectives
- Examine the independent and combined effects of spatial and non-spatial attention on recall accuracy.  
- Compare performance across different visual feature types (colour vs. orientation).  
- Evaluate whether results align more closely with slot-based or resource-based models of working memory.  

### Dataset Description
The dataset represents anonymized behavioural data collected from participants completing visual recall tasks under varying attentional conditions.

| Column | Description |
|---------|-------------|
| `ID` | Participant identifier (anonymised) |
| `A1C_S1` – `A2O_S4` | Accuracy and Reaction Time scores under different spatial/non-spatial attention conditions |
| `Condition` | Experimental condition label |
| `FeatureType` | Feature tested (Colour or Orientation) |

#### Files
- `data/dissertation_data.xlsx` — main dataset   
- `analysis/summary_statistics.xlsx` — descriptive and inferential results summary  
- `Dissertation/Dissertation_Project.docx` — full written dissertation  

---

### Analysis
Analyses were conducted using **JASP** and **Excel**:  
- **Descriptive statistics:** means, standard deviations, and condition comparisons  
- **Inferential analysis:** repeated-measures ANOVAs examining effects of spatial and non-spatial attention  
- **Visualization:** bar plots and interaction charts illustrating condition effects  

Although the original task code was developed in **Python** and **MATLAB**, only processed data and analysis outputs are provided here for confidentiality and reproducibility reasons.

---

### Visuals
Representative outputs from the analysis include:
- Mean accuracy by attention condition  
- Interaction effects between spatial and non-spatial attention  
- Feature-type performance comparisons  

*(Add your charts as images in `/visuals/` and reference them here, e.g.:)*  
`![VSTM Accuracy by Condition](visuals/vstm_accuracy_chart.png)`

---

### Tools Used
- **Excel** for data cleaning and descriptive analysis  
- **JASP** for statistical analysis and visualization  
- **Python** and **MATLAB** for experimental task design (not included)  
- **GitHub** for version control and portfolio presentation  

---

### Report
📄 Full dissertation: [`report/Dissertation_Report.pdf`](report/Dissertation_Report.pdf)

---

### Key Findings
- Spatial and non-spatial attention both significantly affected VSTM recall accuracy.  
- Colour and orientation recall exhibited distinct sensitivity to attentional manipulations.  
- Results provided partial support for a **hybrid model** of visual working memory, combining slot- and resource-based mechanisms.  

---

### Author
**Sion Pritchard**  
BSc Psychology with Cognitive Neuroscience  
[LinkedIn](https://linkedin.com/in/sion-pritchard) • [GitHub](https://github.com/SionPritchard)

---

### ⚖️ Disclaimer
All data has been anonymized and is included solely for educational and portfolio demonstration purposes.  
No personally identifiable information is contained within this repository.

