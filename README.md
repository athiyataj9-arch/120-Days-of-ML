# 120 Days of Machine Learning: From Foundations to MLOps 🚀

This repository documents my 120-day journey of mastering Machine Learning, from data preprocessing to deploying production-grade models.

## 🗺️ Progress Roadmap

| Phase | Focus | Status |
| :--- | :--- | :--- |
| **01** | **Foundations (Math, Stats & Preprocessing)** | ✅ **Completed** |
| **02** | **Supervised Learning (Regression & Classification)** | ✅ **Completed** |
| **03** | **Unsupervised Learning (Clustering & Rules)** | ✅ **Completed** |
| **04** | **Deep Learning (Neural Networks, CV & NLP)** | 🏗️ **Active (Day 68/120)** |

---

## 📈 Phase 4 Log: Deep Learning

### **Part 1: Foundations & Scaling**
Moving from simple math neurons to multi-layer architectures and advanced optimization theory.

* **Day 59-60: Optimization & Loss**
  - Implemented **Gradient Descent** and explored **MSE vs. Binary Cross-Entropy**.
  ![Gradient Descent](assets/day59_plot.png)

* **Day 61-62: Regularization**
  - Tackled the **Bias-Variance Tradeoff** and implemented **Dropout** and **L2** to stop overfitting.
  ![Overfitting vs Underfitting](assets/day61_plot.png)

* **Day 63-64: Architecture & Tuning**
  - Built multi-layer **DNNs** and experimented with **Learning Rates** and **Batch Sizes**.

* **Day 65-66: Automation & Capstone**
  - Integrated `EarlyStopping` callbacks and finalized the foundations phase with an end-to-end classification pipeline.
  ![Early Stopping](assets/day65_earlystopping.png)

### **Part 2: Computer Vision (CNNs)**
Transitioning from tabular data to spatial feature extraction in images.

* **Day 67: Convolutional Layers (The "Eyes")**
  - Implemented `Conv2D` layers using sliding kernels to detect edges, textures, and patterns.
  - *Key Concept: Automatic Feature Extraction.*

* **Day 68: Spatial Reduction (Pooling & Padding)**
  - Applied **Max Pooling** to downsample feature maps and **Padding** to maintain spatial dimensions at image borders.

---

## 📂 Repository Structure

```text
├── 04_DeepLearning/
│   ├── 01_Foundations/         # Tabular Deep Learning
│   │   ├── day59_gradient_descent.ipynb
│   │   ├── ...
│   │   └── day66_capstone.ipynb
│   └── 02_ComputerVision/      # Image Processing & CNNs
│       ├── day67_convolutions.ipynb
│       └── day68_pooling_padding.ipynb
├── assets/                     # Visual Gallery of Learning
└── requirements.txt            # Project dependencies (Tensorflow 2.21.0+)
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
