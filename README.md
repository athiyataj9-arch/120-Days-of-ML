# 120 Days of Machine Learning: From Foundations to MLOps 🚀

This repository documents my 120-day journey of mastering Machine Learning, from data preprocessing to deploying production-grade models.

## 🗺️ Progress Roadmap

| Phase | Focus | Status |
| :--- | :--- | :--- |
| **01** | **Foundations (Math, Stats & Preprocessing)** | ✅ **Completed** |
| **02** | **Supervised Learning (Regression & Classification)** | ✅ **Completed** |
| **03** | **Unsupervised Learning (Clustering & Rules)** | 🏗️ **Active (Day 49/120)** |

---

## 📈 Phase 3 Log: Unsupervised Learning

### **Week 1: Clustering Fundamentals**
* **Day 41-42:** Mastered **K-Means Clustering** and the **Elbow Method** to determine the optimal number of clusters ($K$) by analyzing WCSS.
* **Day 43-44:** Explored **Hierarchical Clustering** with Dendrograms and **DBSCAN** for density-based grouping to handle non-spherical data shapes.

### **Week 2: Dimensionality & Association Rules**

**Day 45-46: Principal Component Analysis (PCA)**
* **Reflection:** Learned to reduce feature dimensions while retaining maximum variance. Used Scree Plots to visualize how many components are needed to represent the data's "soul."
![PCA Variance](assets/day46_plot.png)

**Day 47: t-SNE Visualization**
* **Reflection:** Implemented t-SNE for non-linear dimensionality reduction. It proved superior to PCA for visualizing high-dimensional clusters like handwritten digits in 2D space.
![t-SNE Plot](assets/day47_plot.png)

**Day 48: Apriori Algorithm (Market Basket Analysis)**
* **Reflection:** Transitioned into Association Rule Mining. Learned to calculate **Support** and **Confidence** to find hidden relationships between products in transaction data.


**Day 49: ECLAT Algorithm**
* **Reflection:** Implemented a vertical approach to frequent itemset mining. Unlike Apriori, ECLAT focuses purely on **Support**, making it a faster and simpler tool for popularity discovery.

---

## 📂 Repository Structure

```text
├── 01_Foundations/             # Phase 1: Completed ✅
├── 02_Supervised/              # Phase 2: Completed ✅
├── 03_Unsupervised/            # Phase 3: Active 🏗️
│   ├── 01_Clustering/          # Days 41-44
│   ├── 02_Dimensionality/      # Days 45-47
│   └── 03_Association/         # Days 48-49 (Current)
├── assets/                     # Professional Plots & Visuals
└── requirements.txt            # Project dependencies (mlxtend, sklearn, etc.)

## 🛠️ Tech Stack
* **Language:** Python 3.10+
* **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, Scipy
* **Environment:** VS Code, Jupyter Notebooks, Git

## ⚙️ Setup Instructions
```
### 1. Activate Virtual Environment
Depending on your operating system, run the following in your terminal:
```
**Windows:**
```bash
ml_env\Scripts\activate
```
### 2. Mac/Linux Activation
If you are on a Unix-based system, use the following command:
```bash
source ml_env/bin/activate
```
### 3. Install Dependencies
Ensure you have the latest versions of the required libraries by running:
```bash
pip install -r requirements.txt
