# 120 Days of Machine Learning: From Foundations to MLOps 🚀

This repository documents my 120-day journey of mastering Machine Learning, from data preprocessing to deploying production-grade models.

## 🗺️ Progress Roadmap

| Phase | Focus | Status |
| :--- | :--- | :--- |
| **01** | **Foundations (Math, Stats & Preprocessing)** | ✅ **Completed** |
| **02** | **Supervised Learning (Regression & Classification)** | ✅ **Completed** |
| **03** | **Unsupervised Learning (Clustering & Rules)** | ✅ **Completed** |
| **04** | **Deep Learning (Neural Networks, CV & NLP)** | 🏗️ **Active (Day 66/120)** |

---

## 📈 Phase 4 Log: Deep Learning Foundations

Moving from simple math neurons to multi-layer architectures and advanced optimization theory.

### **The Mechanics of Learning**
* **Day 59: Gradient Descent**
  - Implemented the "Step-down" logic to minimize loss functions.
  ![Gradient Descent](assets/day59_plot.png)

* **Day 60: Loss Functions**
  - Explored **MSE** for regression and **Binary Cross-Entropy** for classification.

* **Day 61: The Bias-Variance Tradeoff**
  - Visualized why models that "memorize" noise fail on real-world data.
  ![Overfitting vs Underfitting](assets/day61_plot.png)

* **Day 62: Model Discipline (Regularization)**
  - Applied **Dropout** and **L2 Regularization** to ensure model robustness.

### **Scaling & Optimization (The "Big Leagues")**
* **Day 63: Deep Neural Networks (DNN)**
  - Stacking multiple hidden layers (`128 -> 64 -> 32`) to capture non-linear complex patterns.
  
* **Day 64: Hyperparameter Tuning**
  - Experimented with **Learning Rates** and **Batch Sizes** to find the "Sweet Spot" for convergence.

* **Day 65: Callbacks & Early Stopping**
  - Automated the training process using the `EarlyStopping` callback to prevent overfitting and save compute time.
  ![Early Stopping](assets/day65_earlystopping.png)

* **Day 66: Foundations Capstone**
  - Built an end-to-end classification pipeline combining Dropout, Batch Tuning, and Early Stopping.
  - **Result:** Successfully achieved high-accuracy generalization on synthetic real-world data.

---

## 📂 Repository Structure

```text
├── 04_DeepLearning/
│   └── 01_Foundations/         
│       ├── day59_gradient_descent.ipynb
│       ├── day60_loss_functions.ipynb
│       ├── day61_overfitting.ipynb
│       ├── day62_regularization.ipynb
│       ├── day63_full_dnn.ipynb
│       ├── day64_tuning.ipynb
│       ├── day65_callbacks.ipynb
│       └── day66_capstone.ipynb
├── assets/                     # Visual Gallery of Learning
└── requirements.txt            # Project dependencies (TensorFlow 2.21.0+)

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
