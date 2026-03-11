# 120 Days of Machine Learning: From Foundations to MLOps 🚀

This repository documents my 120-day journey from Python data science foundations to production-grade Machine Learning Engineering.

## 🗺️ The Roadmap

| Phase | Focus | Status |
| :--- | :--- | :--- |
| **01** | **Foundations (Math, Stats & Preprocessing)** | ✅ **Completed** |
| **02** | **Supervised Learning (Regression & Classification)** | 🏗️ **Active** |
| **03** | **Unsupervised Learning (Clustering/PCA)** | ⏳ Pending |
| **04** | **Deep Learning (PyTorch/CNN/NLP)** | ⏳ Pending |
| **05** | **MLOps & Deployment (FastAPI/Docker)** | ⏳ Pending |

---

## 📈 Daily Progress Log (Phase 2 Continued)

### **Week 2: Advanced Classification**

**Day 29: Support Vector Machines (SVM)**
* **File:** `02_Supervised/day29_svm.ipynb`
* **Reflection:** Mastered the concept of the "Maximum Margin Hyperplane." SVM doesn't just separate data; it finds the widest possible "buffer zone" between classes to ensure the model is robust against new, noisy data.


**Day 30: Naive Bayes**
* **File:** `02_Supervised/day30_naive_bayes.ipynb`
* **Reflection:** Explored probabilistic classification using Bayes' Theorem. Even though it "naively" assumes features are independent, it is incredibly fast and effective for high-dimensional data like text.


[Image of Bayes Theorem formula used in Naive Bayes classification]


---

### **Week 3: Tree-Based Models & Ensembles**

**Day 31: Decision Trees**
* **File:** `02_Supervised/day31_decision_trees.ipynb`
* **Reflection:** Visualized the model's logic as a flowchart. Learned how the algorithm uses **Gini Impurity** and **Entropy** to make the best possible splits at each node.


**Day 32: Random Forest (Ensemble Learning)**
* **File:** `02_Supervised/day32_random_forest.ipynb`
* **Reflection:** Stepped into **Ensemble Learning**. By training 100 different trees on random subsets of data and letting them "vote," the model significantly reduces overfitting and improves accuracy.


---

## 📂 Repository Structure

```text
├── 01_Foundations/             # Phase 1: Completed ✅
├── 02_Supervised/              # Phase 2: Active 🏗️
│   ├── day21_linear_regression.ipynb
│   ├── ...
│   ├── day28_knn.ipynb
│   ├── day29_svm.ipynb
│   ├── day30_naive_bayes.ipynb
│   ├── day31_decision_trees.ipynb
│   └── day32_random_forest.ipynb
├── assets/                     # Professional Plots
│   ├── day21_plot.png
│   ├── ...
│   ├── day29_plot.png
│   └── day31_plot.png
├── data/                       # Datasets
└── requirements.txt            # Project dependencies


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
