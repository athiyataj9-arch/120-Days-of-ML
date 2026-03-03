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
* **Reflection:** NumPy is the backbone of ML performance. Mastered how to manipulate data dimensions without slow Python loops.

**Day 02: Pandas & Data Wrangling**
* **File:** `01_Foundations/day02_pandas.ipynb`
* **Concepts:** Duplicate removal, Outlier handling with `.mask()`, and Mean Imputation.
* **Reflection:** Learned that data cleaning is iterative. Using `.fillna()` and `.drop_duplicates()` is essential for model reliability.

**Day 03: Exploratory Data Analysis (EDA)**
* **File:** `01_Foundations/day03_visualization.ipynb`
* **Concepts:** Distribution plots (Histograms), KDE, and Correlation Heatmaps.
* **Reflection:** Visualization reveals what raw numbers hide. Heatmaps are crucial for identifying feature redundancy.

**Day 04: Statistics for Machine Learning**
* **File:** `01_Foundations/day04_statistics.ipynb`
* **Concepts:** Central Tendency (Mean/Median), Standard Deviation, and Z-Scores.
* **Reflection:** Understood how Z-scores help identify outliers mathematically rather than just visually.

---

## 📂 Repository Structure
```text
├── 01_Foundations/         # Math, Stats, NumPy, Pandas
│   ├── day01_numpy.ipynb   # Day 1: Array manipulation
│   ├── day02_pandas.ipynb  # Day 2: Data cleaning
│   ├── day03_visualization.ipynb # Day 3: EDA
│   └── day04_statistics.ipynb    # Day 4: Stats
├── 02_Supervised/          # Regression, Classification, Boosting
├── 03_Unsupervised/        # Clustering, Dimensionality Reduction
├── 04_DeepLearning/        # Neural Networks, CNN, Transformers
├── 05_MLOps/               # FastAPI, Docker, Cloud Deployment
├── 06_Interview_Prep/      # Scratch Implementations & Theory
├── data/                   # Raw & Processed Datasets
└── requirements.txt        # Dependencies

## 🛠️ Tech Stack
* **Language:** Python 3.10+
* **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, Scipy
* **Environment:** VS Code, Jupyter Notebooks, Git

---

## ⚙️ Setup Instructions

### 1. Activate Virtual Environment
Depending on your operating system, run the following in your terminal:

**Windows:**
```bash
ml_env\Scripts\activate

### 2. Mac/Linux Activation
If you are on a Unix-based system, use the following command:
```bash
source ml_env/bin/activate

### 3. Install Dependencies
Ensure you have the latest versions of the required libraries by running:
```bash
pip install -r requirements.txt

---