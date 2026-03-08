# 120 Days of Machine Learning: From Foundations to MLOps 🚀

This repository documents my 120-day journey from Python data science foundations to production-grade Machine Learning Engineering.

## 🗺️ The Roadmap

| Phase | Focus | Status |
| :--- | :--- | :--- |
| **01** | **Foundations (Math, Stats & Preprocessing)** | ✅ **Completed** |
| **02** | **Supervised Learning (Regression/Trees)** | 🏗️ **Active** |
| **03** | **Unsupervised Learning (Clustering/PCA)** | ⏳ Pending |
| **04** | **Deep Learning (PyTorch/CNN/NLP)** | ⏳ Pending |
| **05** | **MLOps & Deployment (FastAPI/Docker)** | ⏳ Pending |
| **06** | **Interview Prep & System Design** | ⏳ Pending |

---

## 📈 Daily Progress Log

### 📂 Phase 1: Foundations (Days 1–20)

**Day 01 - Day 14: Core Math & Statistics**
* (Previous entries retained: NumPy, Pandas, EDA, Linear Algebra, Calculus, Matrix Inversion, Tensors, Probability, and Hypothesis Testing.)

**Day 15: Sampling Techniques**
* **File:** `01_Foundations/day15_sampling.ipynb`
* **Concepts:** Train-Test Split and Stratified Sampling.
* **Reflection:** Learned how to properly partition data to ensure the model generalizes well. Stratification is key for maintaining class balance.

**Day 16: Handling Imbalanced Data**
* **File:** `01_Foundations/day16_imbalanced_data.ipynb`
* **Concepts:** Random Over-sampling and SMOTE (Synthetic Minority Over-sampling Technique).
* **Reflection:** Mastered techniques to fix "biased" datasets. SMOTE is powerful because it creates synthetic data points rather than just duplicating existing ones.

**Day 17: Feature Scaling (Standardization vs. Normalization)**
* **File:** `01_Foundations/day17_scaling.ipynb`
* **Concepts:** StandardScaler ($Z$-score) and MinMaxScaler (0-1 range).
* **Reflection:** Understood that distance-based models (like KNN or SVM) fail without scaling because large-magnitude features dominate the distance calculation.

**Day 18: Categorical Encoding**
* **File:** `01_Foundations/day18_encoding.ipynb`
* **Concepts:** One-Hot Encoding (Nominal) and Label Encoding (Ordinal).
* **Reflection:** Learned to convert text to math. One-hot is great for unordered categories (Colors), while Label encoding preserves rank (Small, Medium, Large).

**Day 19: Handling Missing Values (Imputation)**
* **File:** `01_Foundations/day19_imputation.ipynb`
* **Concepts:** SimpleImputer (Mean/Median/Mode strategy).
* **Reflection:** Dropping data is a last resort. Imputation allows us to keep the dataset size intact by filling holes with statistical averages.

**Day 20: Feature Selection & Correlation**
* **File:** `01_Foundations/day20_feature_selection.ipynb`
* **Concepts:** Correlation Heatmaps and Feature Redundancy.
* **Reflection:** Finished the Foundations phase! Learned that removing highly correlated features reduces model complexity and prevents "multicollinearity" issues.

---

## 📂 Repository Structure

```text
├── 01_Foundations/             # Phase 1: Math, Stats, & Preprocessing
│   ├── day01_numpy.ipynb
│   ├── ...
│   ├── day17_scaling.ipynb
│   ├── day18_encoding.ipynb
│   ├── day19_imputation.ipynb
│   └── day20_feature_selection.ipynb
├── 02_Supervised/              # Phase 2: Regression, Classification, Boosting
├── 03_Unsupervised/            # Phase 3: Clustering, Dimensionality Reduction
├── 04_DeepLearning/            # Phase 4: Neural Networks, CNN, Transformers
├── 05_MLOps/                   # Phase 5: FastAPI, Docker, Cloud Deployment
├── 06_Interview_Prep/          # Phase 6: Scratch Implementations & Theory
├── data/                       # Raw & Processed Datasets
├── .gitignore                  # Ignores ml_env/, __pycache__, etc.
└── requirements.txt            # Dependencies (numpy, pandas, sklearn, imblearn, seaborn)


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
