# 120 Days of Machine Learning: From Foundations to MLOps 🚀

This repository documents my 120-day journey of mastering Machine Learning, from mathematical foundations to deploying production-grade models.

## 🗺️ Progress Roadmap

| Phase | Focus | Status |
| :--- | :--- | :--- |
| **01** | **Foundations (Math, Stats & Preprocessing)** | ✅ **Completed** |
| **02** | **Supervised Learning (Regression & Classification)** | ✅ **Completed** |
| **03** | **Unsupervised Learning (Clustering & Rules)** | ✅ **Completed** |
| **04** | **Deep Learning (Neural Networks, CV & GenAI)** | ✅ **Completed** |
| **05** | **Natural Language Processing (NLP & Transformers)** | 🏗️ **In Progress (Day 90/120)** |

---

## 📈 Phase 1 Log: Math & Preprocessing (Days 1–20)
* **Mathematics:** Linear Algebra (Matrices/Tensors), Calculus (Gradients), and Probability.
* **Statistics:** Descriptive stats, Hypothesis testing, P-values, and Correlation analysis.
* **Preprocessing:** Handling missing values, Outlier detection, and Feature Scaling.

---

## 📈 Phase 2 Log: Supervised Learning (Days 21–45)
* **Regression:** Simple/Multiple Linear Regression, Lasso (L1), and Ridge (L2).
* **Classification:** Logistic Regression, KNN, and Support Vector Machines (SVM).
* **Ensemble Methods:** Decision Trees, Random Forest, and Gradient Boosting (XGBoost, LightGBM).

---

## 📈 Phase 3 Log: Unsupervised Learning (Days 46–58)
* **Clustering:** K-Means, Hierarchical Clustering, and DBSCAN.
* **Dimensionality Reduction:** Principal Component Analysis (PCA) and t-SNE.
* **Association:** Apriori Algorithm for pattern discovery.

---

## 📈 Phase 4 Log: Deep Learning & Computer Vision (Days 59–80)
* **Days 59-65: ANN Foundations:** Multi-Layer Perceptrons and Backpropagation.
* **Days 66-70: CNN Mechanics:** Convolutional layers, Pooling, and Dropout.
* **Days 71-76: SOTA & Detection:** Transfer Learning (ResNet50) and YOLOv8.
* **Days 77-80: Generative AI:** Autoencoders, VAEs, and GANs.

---

## 📈 Phase 5 Log: NLP & Sequence Models (Days 81–90) 🏗️

### **Part 1: Text Preprocessing (Days 81-85)**
* **Day 81-83:** Mastered Tokenization, Normalization (Stemming/Lemmatization), and Text Cleaning.
* **Day 84:** Implemented TF-IDF Vectorization for statistical word importance.
* **Day 85:** Trained Word2Vec embeddings with Gensim to capture semantic relationships.

### **Part 2: Sequence Models (Days 86-90)**
* **Day 86:** Implemented basic **SimpleRNN** architectures in Keras.
* **Day 87-88:** Explored **LSTMs** and **GRUs** to solve the vanishing gradient problem.
* **Day 89:** Developed **Bidirectional RNNs** to capture context from both future and past.
* **Day 90:** Built **Stacked RNN** architectures for hierarchical language learning.

---

## 📂 Repository Structure

```text
├── 01_Foundations/             # Days 1-20
├── 02_Supervised_Learning/      # Days 21-45
├── 03_Unsupervised_Learning/    # Days 46-58
├── 04_DeepLearning/            # Days 59-80
├── 05_NLP/                     # Current Focus (Days 81-120)
│   ├── 01_Text_Preprocessing/  # Day 81-85
│   │   └── day85_word2vec_embeddings.ipynb
│   └── 02_Sequence_Models/     # Day 86-90
│       ├── day86_rnn_basics.ipynb
│       ├── day87_lstm_networks.ipynb
│       ├── day88_gru_networks.ipynb
│       ├── day89_bidirectional_rnns.ipynb
│       └── day90_stacked_rnns.ipynb
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
