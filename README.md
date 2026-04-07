# 120 Days of Machine Learning: From Foundations to MLOps 🚀

This repository documents my 120-day journey of mastering Machine Learning, from mathematical foundations to deploying production-grade models.

## 🗺️ Progress Roadmap

| Phase | Focus | Status |
| :--- | :--- | :--- |
| **01** | **Foundations (Math, Stats & Preprocessing)** | ✅ **Completed** |
| **02** | **Supervised Learning (Regression & Classification)** | ✅ **Completed** |
| **03** | **Unsupervised Learning (Clustering & Rules)** | ✅ **Completed** |
| **04** | **Deep Learning (Neural Networks, CV & GenAI)** | ✅ **Completed** |
| **05** | **Natural Language Processing (NLP & Transformers)** | 🏗️ **In Progress (Day 85/120)** |

---

## 📈 Phase 1 Log: Math & Preprocessing (Days 1–20)

* **Mathematics:** Linear Algebra (Matrices/Tensors), Calculus (Gradients), and Probability.
* **Statistics:** Descriptive stats, Hypothesis testing, P-values, and Correlation analysis.
* **Preprocessing:** Handling missing values, Outlier detection, and Feature Scaling (Standardization/Normalization).

---

## 📈 Phase 2 Log: Supervised Learning (Days 21–45)

* **Regression:** Simple/Multiple Linear Regression, Lasso (L1), and Ridge (L2) Regularization.
* **Classification:** Logistic Regression, K-Nearest Neighbors (**KNN**), and Support Vector Machines (**SVM**).
* **Ensemble Methods:** Decision Trees, **Random Forest**, and Gradient Boosting (**XGBoost**, LightGBM).

---

## 📈 Phase 3 Log: Unsupervised Learning (Days 46–58)

* **Clustering:** K-Means, Hierarchical Clustering, and DBSCAN for density-based grouping.
* **Dimensionality Reduction:** Principal Component Analysis (**PCA**) and t-SNE for 2D/3D visualization.
* **Association:** Apriori Algorithm for market basket analysis and pattern discovery.

---

## 📈 Phase 4 Log: Deep Learning & Computer Vision (Days 59–80)

* **Days 59-65: ANN Foundations:** Multi-Layer Perceptrons, Backpropagation, and Activation Functions (ReLU, Sigmoid).
* **Days 66-70: CNN Mechanics:** Convolutional layers, Max-Pooling, Dropout, and Batch Normalization.
* **Days 71-76: SOTA & Detection:** Transfer Learning with **ResNet50** and real-time detection using **YOLOv8**.
* **Days 77-80: Generative AI:** Denoising **Autoencoders**, Variational Autoencoders (VAEs), and **GANs**.

---

## 📈 Phase 5 Log: NLP & Text Engineering (Days 81–85)

* **Day 81: Tokenization Suite** – Implemented NLTK `word_tokenize` and `TweetTokenizer` for social media data.
* **Day 82: Normalization** – Comparison of **PorterStemmer** vs. **WordNetLemmatizer** for root-word extraction.
* **Day 83: Text Cleaning** – Pipeline for removing stopwords and punctuation to reduce feature noise.
* **Day 84: TF-IDF Vectorization** – Statistical weighting of terms to identify document-specific keywords.
* **Day 85: Word Embeddings** – Training **Word2Vec** models with Gensim to capture semantic similarities.

---

## 📂 Repository Structure

```text
├── 01_Foundations/             # Math, Stats, and EDA (Days 1-20)
├── 02_Supervised_Learning/      # Regression & Classification (Days 21-45)
├── 03_Unsupervised_Learning/    # Clustering & PCA (Days 46-58)
├── 04_DeepLearning/            # CNNs, YOLOv8, and GANs (Days 59-80)
│   ├── 01_Foundations/
│   └── 02_ComputerVision/
├── 05_NLP/                     # Current Focus (Days 81-120)
│   └── 01_Text_Preprocessing/
│       ├── day81_tokenization.ipynb
│       ├── day82_stemming_lemmatization.ipynb
│       ├── day83_stop_words_cleaning.ipynb
│       ├── day84_tfidf_vectorizer.ipynb
│       └── day85_word2vec_embeddings.ipynb
├── requirements.txt            # Project dependencies
└── README.md                   # Project documentation
```
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
