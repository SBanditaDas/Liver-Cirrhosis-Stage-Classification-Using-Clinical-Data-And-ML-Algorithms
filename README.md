---

# 🧾 Liver Cirrhosis Stage Detection – Predicting Disease Progression from Clinical Data

_Using Random Forest classification to predict liver cirrhosis stages based on patient data from a Mayo Clinic study (1974–1984)._

---
![Python](https://img.shields.io/badge/Python-3.8-blue)
![Kaggle](https://img.shields.io/badge/Kaggle-Kernel-success)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#project-problem">Project Problem</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
- <a href="#modeling--evaluation">Modeling & Evaluation</a>
- <a href="#how-to-run-this-project">How to Run This Project</a>
- <a href="#author--contact">Author & Contact</a>

---

<h2><a class="anchor" id="overview"></a>Overview</h2>

This project predicts the histologic stage of liver cirrhosis using clinical data collected from patients over a 10-year period. The pipeline includes data cleaning, encoding, normalization, exploratory analysis, and Random Forest classification — all built and executed in a Kaggle kernel.

---

<h2><a class="anchor" id="project-problem"></a>Project Problem</h2>

Early detection of liver cirrhosis progression can improve treatment outcomes. This project aims to:
- Predict cirrhosis stage (1, 2, or 3) from patient data  
- Identify key clinical indicators of disease severity  
- Support medical decision-making with interpretable ML models  

---

<h2><a class="anchor" id="dataset"></a>Dataset</h2>

- Source: Mayo Clinic study on primary biliary cirrhosis (1974–1984)  

 ```
 
|    |   N_Days | Status   | Drug    |   Age | Sex   | Ascites   | Hepatomegaly   | Spiders   | Edema   |   Bilirubin |   Cholesterol |   Albumin |   Copper |   Alk_Phos |   SGOT |   Tryglicerides |   Platelets |   Prothrombin |   Stage |
|---:|---------:|:---------|:--------|------:|:------|:----------|:---------------|:----------|:--------|------------:|--------------:|----------:|---------:|-----------:|-------:|----------------:|------------:|--------------:|--------:|
|  0 |     2221 | C        | Placebo | 18499 | F     | N         | Y              | N         | N       |         0.5 |           149 |      4.04 |      227 |        598 |  52.7  |              57 |         256 |           9.9 |       1 |
|  1 |     1230 | C        | Placebo | 19724 | M     | Y         | N              | Y         | N       |         0.5 |           219 |      3.93 |       22 |        663 |  45    |              75 |         220 |          10.8 |       2 |
|  2 |     4184 | C        | Placebo | 11839 | F     | N         | N              | N         | N       |         0.5 |           320 |      3.54 |       51 |       1243 | 122.45 |              80 |         225 |          10   |       2 |
|  3 |     2090 | D        | Placebo | 16467 | F     | N         | N              | N         | N       |         0.7 |           255 |      3.74 |       23 |       1024 |  77.5  |              58 |         151 |          10.2 |       2 |
|  4 |     2105 | D        | Placebo | 21699 | F     | N         | Y              | N         | N       |         1.9 |           486 |      3.54 |       74 |       1052 | 108.5  |             109 |         151 |          11.5 |       1 |
```

---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)  
- Kaggle Kernels (Notebook execution and visualization)  
- GitHub (Version control and portfolio hosting)  

---

<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```
liver_cirrhosis_stage_detection/
│
├── README.md
├── liver_cirrhosis.csv                  # Dataset
├── liver_cirrhosis_stage_detection.ipynb  # Kaggle notebook
├── visuals/                             # Plots and charts
│   ├── stage_distribution.png
│   ├── heatmap.png
│   └── confusion_matrix.png
```
---

<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

- Encoded categorical features (Sex, Drug, Edema, etc.)  
- Normalized numerical features using `StandardScaler`  
- Verified absence of missing values  
- Split dataset into training and test sets  

---

<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)</h2>

**Stage Distribution:**  
- Balanced across stages 1, 2, and 3  

**Feature Correlations:**  
- Strong correlation between Bilirubin, Albumin, and Stage  

**Visuals:**  
- Correlation heatmap  
- Boxplots for key features  
- Stage distribution bar chart
<p align="center">
  <img src="https://github.com/SBanditaDas/Liver-Cirrhosis-Stage-Classification-Using-Clinical-Data-And-ML-Algorithms/blob/main/heatmap.png?raw=true" width="320"/>
  <img src="https://github.com/SBanditaDas/Liver-Cirrhosis-Stage-Classification-Using-Clinical-Data-And-ML-Algorithms/blob/main/confusion_matrix.png?raw=true" width="300"/>
  <img src="https://github.com/SBanditaDas/Liver-Cirrhosis-Stage-Classification-Using-Clinical-Data-And-ML-Algorithms/blob/main/stage_distribution.png?raw=true" width="300"/>
</p>

---

<h2><a class="anchor" id="modeling--evaluation"></a>Modeling & Evaluation</h2>

- Model: Random Forest Classifier  
- Accuracy: ~85% on test set  
- Evaluation Metrics:  
  - Precision, Recall, F1-score  
  - Confusion Matrix  
  - Feature Importance

---

<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

1. Clone the repository:  
```bash
git clone https://github.com/SBanditaDas/Liver-Cirrhosis-Stage-Detection.git
```
- Open the notebook in Kaggle or Jupyter:
🔗 [liver_cirrhosis_stage_detection.ipynb](https://www.kaggle.com/code/dasbanditasushree/liver-cirrhosis-stage-detection)

- Run all cells to reproduce results and visuals

---

<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Sushree Bandita Das**  
 
 📧 Email: sushreebanditadas01@gmail.com  
 
<h3 align="left"></h3> 
<p align="left">
  <a href="https://twitter.com/S_Bandita_Das" target="blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="S_Bandita_Das" height="30" width="40" />
  </a>
  <a href="http://www.linkedin.com/in/sushree-bandita-das-160651309" target="blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="sushree-bandita-das-160651309" height="30" width="40" />
  </a>
  <a href="https://github.com/SBanditaDas" target="blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/github.svg" alt="SBanditaDas" height="30" width="40" />
  </a>
  <a href="https://www.kaggle.com/dasbanditasushree" target="blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/kaggle.svg" alt="dasbanditasushree" height="30" width="40" />
  </a>

</p>

---
