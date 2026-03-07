# 120 Days of Machine Learning: From Foundations to MLOps 🚀

This repository documents my 120-day journey from Python data science foundations to production-grade Machine Learning Engineering.

## 🗺️ The Roadmap

| Phase | Focus | Status |
| :--- | :--- | :--- |
| **01** | **Foundations (Math, Stats & Preprocessing)** | 🏗️ **Active** |
| **02** | **Supervised Learning (Regression/Trees)** | ⏳ Pending |
| **03** | **Unsupervised Learning (Clustering/PCA)** | ⏳ Pending |
| **04** | **Deep Learning (PyTorch/CNN/NLP)** | ⏳ Pending |
| **05** | **MLOps & Deployment (FastAPI/Docker)** | ⏳ Pending |
| **06** | **Interview Prep & System Design** | ⏳ Pending |

---

## 📈 Daily Progress Log

### 📂 Phase 1: Foundations (Days 1–20)

**Day 01: NumPy Essentials**
* **File:** `01_Foundations/day01_numpy.ipynb`
* **Concepts:** Array Shaping, Vectorization, and Axis-based Aggregation.
* **Reflection:** NumPy is the backbone of ML performance.

**Day 02: Pandas & Data Wrangling**
* **File:** `01_Foundations/day02_pandas.ipynb`
* **Concepts:** Duplicate removal, Outlier handling, and Mean Imputation.
* **Reflection:** Data cleaning is iterative and essential for model reliability.

**Day 03: Exploratory Data Analysis (EDA)**
* **File:** `01_Foundations/day03_visualization.ipynb`
* **Concepts:** Distribution plots (Histograms), KDE, and Correlation Heatmaps.
* **Reflection:** Visualization reveals what raw numbers hide.

**Day 04: Statistics for Machine Learning**
* **File:** `01_Foundations/day04_statistics.ipynb`
* **Concepts:** Central Tendency, Standard Deviation, and Z-Scores.
* **Reflection:** Understood how Z-scores help identify outliers mathematically.

**Day 05: Linear Algebra Essentials**
* **File:** `01_Foundations/day05_linear_algebra.ipynb`
* **Concepts:** Dot Products and Matrix Multiplication.
* **Reflection:** Realized that Neural Networks are essentially series of matrix multiplications.

**Day 06: Calculus & Optimization**
* **File:** `01_Foundations/day06_math_for_ml.ipynb`
* **Concepts:** Derivatives and Gradient Descent logic.
* **Reflection:** Understanding how gradients guide models to the lowest error.

**Day 07: SQL for Data Science (Pandas Joins)**
* **File:** `01_Foundations/day07_sql_for_ds.ipynb`
* **Concepts:** Inner/Left Joins and Complex Aggregations.
* **Reflection:** Merging datasets correctly is vital for building complete feature sets.

**Day 08: Feature Engineering**
* **File:** `01_Foundations/day08_feature_engineering.ipynb`
* **Concepts:** Standard Scaling and One-Hot Encoding.
* **Reflection:** Scaling prevents large-range features from dominating the model.

**Day 09: Time Series Analysis**
* **File:** `01_Foundations/day09_timeseries.ipynb`
* **Concepts:** DateTime Indexing, `.resample()`, and Rolling Windows.
* **Reflection:** Learned to smooth out noisy data and extract trends using moving averages.

**Day 10: Pivot Tables & Advanced Aggregation**
* **File:** `01_Foundations/day10_pivot_tables.ipynb`
* **Concepts:** `.pivot_table()` and `.groupby().agg()`.
* **Reflection:** Mastered data summarization for high-level decision making.

**Day 11: Matrix Inversion**
* **File:** `01_Foundations/day11_matrix_inversion.ipynb`
* **Concepts:** Determinants and Inverse Matrices ($A^{-1}$).
* **Reflection:** Learned how to "undo" matrix transformations to solve systems of linear equations.

**Day 12: High-Dimensional Tensors**
* **File:** `01_Foundations/day12_tensors.ipynb`
* **Concepts:** 3D Tensors, Shape manipulation, and Reshaping.
* **Reflection:** Tensors are the multi-dimensional containers for all Deep Learning data. Mastering `.reshape()` is key to data prep.

**Day 13: Probability & Normal Distribution**
* **File:** `01_Foundations/day13_probability.ipynb`
* **Concepts:** Normal Distribution (Bell Curve), Mean, Standard Deviation, and Z-Scores.
* **Reflection:** Understood how the Gaussian distribution acts as the "default" assumption for many ML models and how to identify outliers using Z-scores.

**Day 14: Hypothesis Testing**
* **File:** `01_Foundations/day14_hypothesis_testing.ipynb`
* **Concepts:** Null vs. Alternative Hypothesis, T-Tests, and P-Values.
* **Reflection:** Learned how to mathematically validate if a model improvement is statistically significant or just random noise—crucial for A/B testing features.

**Day 15: Sampling Techniques**
* **File:** `01_Foundations/day15_sampling.ipynb`
* **Concepts:** Train-Test Split and Stratified Sampling.
* **Reflection:** Learned how to properly partition data to ensure the model generalizes well. Stratification is key for maintaining class balance.

**Day 16: Handling Imbalanced Data**
* **File:** `01_Foundations/day16_imbalanced_data.ipynb`
* **Concepts:** Random Over-sampling and SMOTE (Synthetic Minority Over-sampling Technique).
* **Reflection:** Mastered techniques to fix "biased" datasets. SMOTE is powerful because it creates synthetic data points rather than just duplicating existing ones.

---

├── 01_Foundations/             # Phase 1: Math, Stats, & Preprocessing
│   ├── day01_numpy.ipynb
│   ├── ...
│   ├── day11_matrix_inversion.ipynb
│   ├── day12_tensors.ipynb
│   ├── day13_probability.ipynb
│   ├── day14_hypothesis_testing.ipynb
│   ├── day15_sampling.ipynb
│   └── day16_imbalanced_data.ipynb
├── 02_Supervised/              # Regression, Classification, Boosting
├── 03_Unsupervised/            # Clustering, Dimensionality Reduction
├── 04_DeepLearning/            # Neural Networks, CNN, Transformers
├── 05_MLOps/                   # FastAPI, Docker, Cloud Deployment
├── 06_Interview_Prep/          # Scratch Implementations & Theory
├── data/                       # Raw & Processed Datasets
├── .gitignore                  # Keeps your repo clean (ignores ml_env/)
└── requirements.txt            # Dependencies (numpy, pandas, sklearn, imblearn)


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
