<div align="center">

# 🌍 Global Terrorism Analysis
### In-Depth Analysis and Prediction of Global Terrorism
#### A Synergistic Approach using EDA and Advanced ML Models

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Viz-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

📄 **Published Research** | Learnet Publication · ResearchGate · ISBN Verified  
🎓 **B.Tech Final Year Project** | Dept. of CSE, College of Engineering & Management, Kolaghat  
🏛️ Affiliated to **MAKAUT, West Bengal**

</div>

---

## 📌 About the Project

This is a **published research project** analyzing over **181,000 terrorist incidents** from the [Global Terrorism Database (GTD)](https://www.start.umd.edu/gtd) spanning **1970 to 2017**. The project combines deep Exploratory Data Analysis (EDA) with advanced Machine Learning models to uncover patterns in global terrorism and predict whether an attack will succeed.

The study reveals critical insights — from the **2014 global peak in terrorist activity**, to the **geographic shift of terrorism toward the Middle East post-2010**, to the dominance of **ISIL as the most active terrorist organization** in the dataset.

> 💡 This project was developed as a team. My personal contribution covers the **Data Preprocessing, Exploratory Data Analysis (EDA), and all Data Visualizations** — 15+ charts and maps built using Matplotlib, Seaborn, and Plotly.

---

## 👥 Team

| Name | Contribution |
|---|---|
| **Ayan Saha** | Data Preprocessing · EDA · All Data Visualizations |
| Anamitra Bagchi | ML Model Implementation |
| Deepanjali Paul | ML Pipeline & Deep Learning |
| Mayuri Chatterjee | Model Evaluation & Reporting |

**Supervisor:** Prof. Pallab Mandal, Dept. of CSE

---

## 📊 Dataset Overview

| Property | Detail |
|---|---|
| **Source** | Global Terrorism Database (GTD) via Kaggle |
| **Time Period** | 1970 – 2017 |
| **Total Records** | 181,691 rows · 135 columns |
| **Key Features Used** | Year, Region, Country, Attack Type, Target Type, Weapon Type, Success, Casualties |

---

## 🔬 Project Workflow

```
Raw Dataset (GTD)
      │
      ▼
 Data Preprocessing
 (Select 14 columns, rename, handle nulls, remove duplicates)
      │
      ▼
 Exploratory Data Analysis (EDA)
 (15+ visualizations — trends, hotspots, groups, correlations)
      │
      ▼
 Feature Selection
 (Random Forest importance scores → top features retained)
      │
      ▼
 ML / DL Model Training
 (Logistic Regression · Random Forest · XGBoost · Neural Network)
      │
      ▼
 Evaluation & Results
 (Accuracy · Precision · Recall · F1 Score · AUC-ROC)
```

---

## 📈 My Contribution — Data Visualizations & EDA

All visualizations below were built by me as part of the EDA phase.

### 1. 📅 Terrorist Activities Per Year
> Count plot showing attacks from 1970–2017. **2014 had the highest number of attacks globally**, aligning with the rise of ISIL.

### 2. 🌐 Terrorist Activities by Region Over Time
> Area chart revealing how **Middle East & North Africa** and **South Asia** exploded in activity post-2010, while Western Europe peaked in the 1970s–80s.

### 3. 🗺️ Animated Choropleth World Map *(Most Impressive)*
> Interactive Plotly map animated year-by-year showing countries color-coded by attack count. Clearly shows the **geographic shift of global terrorism** over 5 decades.

### 4. ☁️ Word Cloud — Terror Groups
> Frequency-based word cloud where **ISIL appears largest**, followed by Taliban and Boko Haram, confirming their dominance in the dataset.

### 5. 🥧 Pie Chart — Top 10 Target Types
> **Private citizens & property** account for the largest share of targets, followed by Military and Police, showing terrorism is directed more at civilians than infrastructure.

### 6. 📉 Regression Plot — Pakistan Casualties vs Year
> Seaborn + Plotly dual regression scatter showing an **upward trend in deaths** in Pakistan, with a sharp spike around 2010 during the Taliban insurgency.

### 7. 🌡️ Correlation Heatmap
> Multivariate heatmap revealing that kills and wounds are positively correlated, and suicide attacks correlate moderately with attack success.

### 8. 🌳 Sunburst Chart — Region → Attack Type → Target Type
> 3-level hierarchical chart showing South Asia experiences the highest bombings targeting police and military, while Middle East shows similar patterns.

### 9. 🔷 Dendrogram — Hierarchical Clustering of Regions
> Regions clustered by attack type similarity — **South Asia, Sub-Saharan Africa, and Middle East cluster together**, while Western Europe and North America form separate groups.

### 10. 📊 Attack Type vs Success Rate
> Horizontal bar chart showing **Hostage Taking (Barricade)** has the highest success rate (~100%), while Assassination has the lowest among listed attack types.

### 11. 🫧 Bubble Scatter — Kills by Year & Country
> Log-scale interactive Plotly chart where bubble size = kill count, revealing a few catastrophic mass-casualty events among mostly smaller attacks.

### 12. 🏙️ Top 10 Cities & Countries
> **Baghdad** tops the most attacked cities by a wide margin. **Iraq, Pakistan, Afghanistan** lead the most affected countries.

---

## 🤖 ML Models (Team Contribution)

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---|---|---|---|
| Logistic Regression | 89.1% | 0.891 | 1.000 | 0.942 |
| **Random Forest** | **90.2%** | **0.911** | **0.986** | **0.947** |
| XGBoost | 90.2% | 0.910 | 0.986 | 0.947 |
| Neural Network | 90.0% | 0.906 | 0.993 | 0.947 |

> **Random Forest and XGBoost achieved the highest accuracy at 90.2%**, with Random Forest having the best precision.

---

## 🛠️ Tech Stack

**Data Handling**
- `Python 3` · `Pandas` · `NumPy`

**Data Visualization** *(My Contribution)*
- `Matplotlib` · `Seaborn` · `Plotly Express` · `WordCloud` · `Folium`

**Machine Learning**
- `Scikit-Learn` (Logistic Regression, Random Forest, Feature Selection)
- `XGBoost` (Gradient Boosting Classifier)
- `TensorFlow Keras` (Neural Network)
- `imbalanced-learn` (SMOTE for class imbalance)

**Environment**
- `Google Colab` · `Jupyter Notebook`

---

## 💡 Key Findings

- 📌 **2014 was the peak year** for global terrorist attacks
- 📌 **ISIL is the most active terrorist group** in the dataset (by attack count)
- 📌 **Baghdad is the most attacked city** in the world
- 📌 **Iraq is the most affected country**
- 📌 Terrorism **shifted from Latin America (1980s) to Middle East (2010s)**
- 📌 **Suicide attacks have higher success rates** than non-suicide attacks
- 📌 **Private citizens are the #1 target type** — surpassing military and government
- 📌 **Hostage-taking has the highest attack success rate** (~100%)
- 📌 Attacks with high fatalities also tend to cause more injuries (positive correlation)
- 📌 South Asia & Middle East cluster together in attack-type similarity

---

## 🚀 Future Scope

- Real-time data integration via GTD/news APIs
- Web/mobile app for live prediction by security analysts
- REST API deployment using FastAPI or Flask
- Geo-spatial risk mapping with GIS tools
- Explainable AI (SHAP/LIME) for model interpretability
- AutoML pipeline for continuous model retraining

---

## 📚 Publication

> This project was **published by Learnet Publication** and is available on **ResearchGate** with a verified **ISBN number**.

---

## 📁 Repository Structure

```
global-terrorism-analysis/
│
├── GlobalTerrorism_Analysis.ipynb   # Main notebook
├── README.md                        # This file
└── assets/                          # Charts and visualization screenshots
```

---

## ▶️ How to Run

```bash
# 1. Clone the repository
git clone https://github.com/YOURCODERAYAN/global-terrorism-analysis.git

# 2. Open in Google Colab or Jupyter
# Upload GlobalTerrorism_Analysis.ipynb

# 3. Upload the GTD dataset from Kaggle
# https://www.kaggle.com/datasets/START-UMD/gtd

# 4. Run all cells in order
```

---

<div align="center">

Made with 🧠 + 📊 by **Ayan Saha** and team  
College of Engineering & Management, Kolaghat · MAKAUT, West Bengal

</div>
