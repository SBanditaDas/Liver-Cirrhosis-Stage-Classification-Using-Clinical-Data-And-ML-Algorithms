<<<<<<< HEAD
=======


>>>>>>> d59139a (files added)
---

# 🧾 Liver Cirrhosis Stage Detection – Predicting Disease Progression from Clinical Data

_Using Random Forest classification to predict liver cirrhosis stages based on patient data from a Mayo Clinic study (1974–1984)._

---
<<<<<<< HEAD
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
- <a href="#final-recommendations">Final Recommendations</a>
- <a href="#author--contact">Author & Contact</a>

---

<h2><a class="anchor" id="overview"></a>Overview</h2>
=======

### overview :
>>>>>>> d59139a (files added)

This project predicts the histologic stage of liver cirrhosis using clinical data collected from patients over a 10-year period. The pipeline includes data cleaning, encoding, normalization, exploratory analysis, and Random Forest classification — all built and executed in a Kaggle kernel.

---

<<<<<<< HEAD
<h2><a class="anchor" id="project-problem"></a>Project Problem</h2>
=======
### Project Problem :
>>>>>>> d59139a (files added)

Early detection of liver cirrhosis progression can improve treatment outcomes. This project aims to:
- Predict cirrhosis stage (1, 2, or 3) from patient data  
- Identify key clinical indicators of disease severity  
- Support medical decision-making with interpretable ML models  

---

<<<<<<< HEAD
<h2><a class="anchor" id="dataset"></a>Dataset</h2>
=======
### Dataset :
>>>>>>> d59139a (files added)

- Source: Mayo Clinic study on primary biliary cirrhosis (1974–1984)  
- Format: CSV file with 25,000 patient records  
- Features include:  
  - Demographics (Age, Sex)  
  - Clinical indicators (Bilirubin, Albumin, Copper, SGOT, etc.)  
  - Symptoms (Ascites, Edema, Spiders)  
<<<<<<< HEAD
  - Target: `Stage` (1, 2, or 3)
  - `liver_cirrhosis.csv`: Dataset
  - `liver_cirrhosis_stage_detection.ipynb`: Kaggle notebook
  - `README.md`: Project summary


---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>
=======
  - Target: `Stage` (1, 2, or 3)  

---
### Tools & Technologies :
>>>>>>> d59139a (files added)

- Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)  
- Kaggle Kernels (Notebook execution and visualization)  
- GitHub (Version control and portfolio hosting)  

---

<<<<<<< HEAD
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
=======
### Data Cleaning & Preparation :
>>>>>>> d59139a (files added)

- Encoded categorical features (Sex, Drug, Edema, etc.)  
- Normalized numerical features using `StandardScaler`  
- Verified absence of missing values  
- Split dataset into training and test sets  

---
<<<<<<< HEAD

<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)</h2>

**Stage Distribution:**  
- Balanced across stages 1, 2, and 3  

**Feature Correlations:**  
- Strong correlation between Bilirubin, Albumin, and Stage  

**Visuals:**  
- Correlation heatmap  
- Boxplots for key features  
- Stage distribution bar chart  

---

<h2><a class="anchor" id="modeling--evaluation"></a>Modeling & Evaluation</h2>
=======
### Modeling & Evaluation :
>>>>>>> d59139a (files added)

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
<<<<<<< HEAD
git clone https://github.com/SBanditaDas/Liver-Cirrhosis-Stage-Detection.git
```
- Open the notebook in Kaggle or Jupyter:
🔗 [liver_cirrhosis_stage_detection.ipynb](liver_cirrhosis_stage_detection.ipynb)

- Run all cells to reproduce results and visuals

---
<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>

- Explore ensemble models like XGBoost for improved accuracy
- Add SHAP or LIME for feature explainability
- Integrate with clinical dashboards for real-time prediction
- Validate with external datasets for generalization
---

<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Sushree Bandita Das**  
 
 📧 Email: sushreebanditadas01@gmail.com  
🔗 [LinkedIn](http://www.linkedin.com/in/sushree-bandita-das-160651309)  
🔗 [Portfolio](http://datascienceportfol.io/sushreebanditadas01)

---
=======
git clone https://github.com/SBanditaDas/liver-cirrhosis-stage-detection.git
```

2. Open the notebook in Kaggle or Jupyter:  
   🔗 [liver_cirrhosis_stage_detection.ipynb](https://github.com/SBanditaDas/liver-cirrhosis-stage-detection/blob/main/liver_cirrhosis_stage_detection.ipynb)

3. Run all cells to reproduce results and visuals  
---

### Author : Sushree Bandita Das 

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
>>>>>>> d59139a (files added)
