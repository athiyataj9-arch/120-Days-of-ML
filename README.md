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

## 📈 Daily Progress Log (Phase 3: Unsupervised Learning)

### **Week 1: Pattern Discovery through Clustering**

**Day 41: K-Means Clustering**
* **File:** `03_Unsupervised/01_Clustering/day41_kmeans.ipynb`
* **Reflection:** Started Unsupervised Learning by grouping data without labels. K-Means uses centroids to find the "center" of data clusters. It's fast but requires pre-defining the number of groups.


**Day 42: The Elbow Method**
* **File:** `03_Unsupervised/01_Clustering/day42_elbow_method.ipynb`
* **Reflection:** Learned how to mathematically find the optimal number of clusters ($K$). By plotting the Within-Cluster Sum of Squares (WCSS), I can find the "elbow" where adding more clusters provides diminishing returns.


**Day 43: Hierarchical Clustering & Dendrograms**
* **File:** `03_Unsupervised/01_Clustering/day43_hierarchical.ipynb`
* **Reflection:** Explored a "bottom-up" approach to clustering. Unlike K-Means, hierarchical clustering creates a tree-like structure (Dendrogram) that allows us to see how every data point relates to others before deciding on the final group count.


**Day 44: DBSCAN (Density-Based Clustering)**
* **File:** `03_Unsupervised/01_Clustering/day44_dbscan.ipynb`
* **Reflection:** Discovered how to handle non-spherical data (like moon shapes). DBSCAN groups points based on how "packed" they are. Bonus: it automatically identifies "noise" points that don't belong to any cluster.


---

## 📂 Repository Structure

```text
├── 01_Foundations/             # Phase 1: Completed ✅
├── 02_Supervised/              # Phase 2: Completed ✅
├── 03_Unsupervised/            # Phase 3: Active 🏗️
│   ├── 01_Clustering/          # Grouping similar data
│   │   ├── day41_kmeans.ipynb
│   │   ├── day42_elbow_method.ipynb
│   │   ├── day43_hierarchical.ipynb
│   │   └── day44_dbscan.ipynb
│   ├── 02_Dimensionality/      # (Coming Soon)
│   └── 03_Association/         # (Coming Soon)
├── assets/                     # Professional Plots
│   ├── day21_plot.png
│   ├── ...
│   ├── day41_plot.png
│   └── day44_plot.png
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
