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

> 💡 This project was developed as a team. My personal contribution covers **Data Preprocessing, Exploratory Data Analysis (EDA), and all 22 Data Visualizations** built using Matplotlib, Seaborn, and Plotly.

---

## 🏆 Recognition

| Type | Detail |
|---|---|
| **Conference** | Presented at **STEP 2K25** — Smart Technology for Emerging Problems |
| **Organized by** | GMIT · Backed by IEEE and IET bodies |
| **Conference Date** | March 21–22, 2025 |
| **Publication** | Published by Learnet Publication on ResearchGate · ISBN Verified |
| **Published Paper** | [📄 View Published Paper](./ResearchPaper.pdf) |

---

## 👥 Team

| Name | Contribution |
|---|---|
| **Ayan Saha** | Data Preprocessing · EDA · All Data Visualizations |
| Anamitra Bagchi | ML Model Implementation |
| Deepanjali Paul | ML Pipeline & Deep Learning |
| Mayuri Chatterjee | Model Evaluation & Reporting |

**Supervisor:** Prof. Pallab Mandal, Assistant Professor — Dept. of CSE

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
 (Select 14 columns · Rename · Handle nulls · Remove duplicates)
      │
      ▼
 Exploratory Data Analysis (EDA)
 (22 visualizations — trends · hotspots · groups · correlations)
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

## 📈 Data Visualizations & EDA *(My Contribution)*

### 📊 Distribution Analysis
- Suicide Rate Frequency & Success Rate Comparison *(Bar Charts)*
- Top 10 Most Attacked Cities & Countries *(Bar Charts)*
- Top 10 Target Types *(Pie Chart)*
- Attack Type vs Success Rate *(Horizontal Bar Chart)*

### 📅 Temporal Trends
- Terrorist Activities Per Year *(Count Plot)*
- Terrorist Activities by Region Over Time *(Area Chart)*
- Seasonality — Monthly Attack Trends *(Line Chart)*
- Target Type Trends Over Time *(Line Chart)*
- Casualty Trends by Region Over Time *(Line Chart)*

### 🗺️ Geospatial Analysis
- Animated Choropleth Map — Kills by Country *(Plotly · Animated)*
- Animated Choropleth Map — Attack Count by Country *(Plotly · Red Gradient)*

### 🔗 Correlation & Clustering
- Correlation Heatmap — 6 Key Features *(Seaborn · Annotated)*
- Full Correlation Heatmap — All Numerical Features *(Seaborn · Coolwarm)*
- Regional Activity Heatmap Over Time *(Seaborn · Pivot)*
- Hierarchical Clustering Dendrogram *(Scipy · Ward Linkage)*

### 🌐 Interactive & Advanced Charts
- Word Cloud — Terror Groups *(WordCloud · Frequency-based)*
- Bubble Scatter — Kills by Year & Country *(Plotly · Log Scale)*
- Regression Plot — Pakistan Casualties vs Year *(Seaborn)*
- Interactive Regression Plot — Pakistan *(Plotly · OLS Trendline)*
- Sunburst Chart — Region → Attack Type → Target Type *(Plotly · 3-Level)*

---

## 🤖 ML Models *(Team Contribution)*

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---|---|---|---|
| Logistic Regression | 89.1% | 0.891 | 1.000 | 0.942 |
| **Random Forest** | **90.2%** | **0.911** | **0.986** | **0.947** |
| XGBoost | 90.2% | 0.910 | 0.986 | 0.947 |
| Neural Network | 90.0% | 0.906 | 0.993 | 0.947 |

> **Random Forest** achieved the best overall performance — highest precision (0.911) with tied accuracy of 90.2% and F1 score of 0.947.

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| **Data Handling** | Python 3 · Pandas · NumPy |
| **Visualization** *(My Part)* | Matplotlib · Seaborn · Plotly Express · WordCloud · Scipy |
| **Machine Learning** | Scikit-Learn · XGBoost |
| **Deep Learning** | TensorFlow · Keras |
| **Class Imbalance** | imbalanced-learn (SMOTE) |
| **Environment** | Google Colab |

---

## 💡 Key Findings

- 📌 **2014 was the peak year** — terrorist attacks peaked from 2012, hitting highest in 2014, followed by 2015 and 2016
- 📌 **ISIL, FMLN, and Taliban** are the three most prominent organizations in conducting terrorist activities
- 📌 **Suicide attacks have a higher success rate** than non-suicide attacks
- 📌 **Private citizens & property are the #1 target** — surpassing military, police, and government
- 📌 **Hostage Taking (Barricade) has the highest attack success rate** — approaching 100%
- 📌 Terrorism **shifted from Latin America & South Asia (1980s) to Middle East & Sub-Saharan Africa (post-2000)**
- 📌 **South Asia, Sub-Saharan Africa, and Middle East** share similar attack type profiles — cluster together in hierarchical analysis
- 📌 **High fatality attacks strongly correlate with high injury counts** across the dataset
- 📌 **Middle East & North Africa and South Asia** experienced the highest number of attacks, peaking around 2014–2015
- 📌 **Western Europe** was most active in the 1970s–80s and has significantly declined since

---

## 🚀 Future Scope

- Real-time data integration via GTD / news APIs
- Web or mobile app for live prediction by security analysts
- REST API deployment using FastAPI or Flask
- Geo-spatial risk mapping with GIS tools
- Explainable AI using SHAP / LIME for model interpretability
- AutoML pipeline for continuous model retraining

---

## 📁 Repository Structure

```
global-terrorism-analysis/
│
├── In_Depth_Analysis_of_Global_Terrorism_A_Synergystic_Approach_using_EDA_and_Advanced_ML_Models (2).ipynb   # Main notebook
├── paper.pdf                        # Published research paper
├── README.md                        # This file
└── assets/                          # Charts and visualization screenshots
```

---

## ▶️ How to Run

```bash
# 1. Clone the repository
git clone https://github.com/YOURCODERAYAN/global-terrorism-analysis.git

# 2. Open in Google Colab or Jupyter
#    Upload In_Depth_Analysis_of_Global_Terrorism_A_Synergystic_Approach_using_EDA_and_Advanced_ML_Models (2).ipynb

# 3. Upload the GTD dataset from Kaggle
#    https://www.kaggle.com/datasets/START-UMD/gtd

# 4. Run all cells in order
```

---

<div align="center">

Made with 🧠 + 📊 by **Ayan Saha** and team
College of Engineering & Management, Kolaghat · MAKAUT, West Bengal

</div>
