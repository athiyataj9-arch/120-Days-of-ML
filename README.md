# 120 Days of Machine Learning: From Foundations to MLOps 🚀

This repository documents my 120-day journey from Python data science foundations to production-grade Machine Learning Engineering.

## 🗺️ The Roadmap

| Phase | Focus | Status |
| :--- | :--- | :--- |
| **01** | **Foundations (Math, Stats & Preprocessing)** | ✅ **Completed** |
| **02** | **Supervised Learning (Regression & Classification)** | ✅ **Completed** |
| **03** | **Unsupervised Learning (Clustering/PCA)** | 🏗️ **Active** |
| **04** | **Deep Learning (PyTorch/CNN/NLP)** | ⏳ Pending |
| **05** | **MLOps & Deployment (FastAPI/Docker)** | ⏳ Pending |

---

## 📈 Daily Progress Log (Phase 2: Conclusion)

### **Week 5: Model Optimization & Handling Real-World Data**

**Day 37-38: Hyperparameter Tuning (Grid vs. Random Search)**
* **File:** `02_Supervised/day37_grid_search.ipynb` & `day38_random_search.ipynb`
* **Reflection:** Learned that "default" parameters are rarely the best. `GridSearchCV` is great for small sets, but `RandomizedSearchCV` is the industry secret for tuning large, complex models quickly without sacrificing much accuracy.


**Day 39: Handling Imbalanced Data (SMOTE)**
* **File:** `02_Supervised/day39_smote.ipynb`
* **Reflection:** Solved the "Accuracy Paradox." In datasets where 99% of cases are negative (like fraud), a model can be 99% accurate by doing nothing. I used SMOTE to create synthetic minority samples, forcing the model to actually learn the rare cases.


**Day 40: Phase 2 Capstone Project**
* **File:** `02_Supervised/day40_capstone.ipynb`
* **Reflection:** Brought it all together. Built an end-to-end pipeline that includes Feature Scaling, Class Balancing, and a Tuned XGBoost model. **Phase 2 Complete!**


---

## 📂 Repository Structure

```text
├── 01_Foundations/             # Phase 1: Completed ✅
├── 02_Supervised/              # Phase 2: Completed ✅
│   ├── day21_30_basics.ipynb
│   ├── ...
│   ├── day37_grid_search.ipynb
│   ├── day38_random_search.ipynb
│   ├── day39_smote.ipynb
│   └── day40_capstone.ipynb
├── 03_Unsupervised/            # Phase 3: Starting 🏗️
├── assets/                     # Visual Evidence
│   ├── day21_plot.png
│   ├── ...
│   └── day36_plot.png
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
