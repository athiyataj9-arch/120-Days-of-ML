# 120 Days of Machine Learning: From Foundations to MLOps 🚀

This repository documents my 120-day journey of mastering Machine Learning, from data preprocessing to deploying production-grade models.

## 🗺️ Progress Roadmap

| Phase | Focus | Status |
| :--- | :--- | :--- |
| **01** | **Foundations (Math, Stats & Preprocessing)** | ✅ **Completed** |
| **02** | **Supervised Learning (Regression & Classification)** | ✅ **Completed** |
| **03** | **Unsupervised Learning (Clustering & Rules)** | ✅ **Completed** |
| **04** | **Deep Learning (Neural Networks, CV & NLP)** | 🏗️ **Active (Day 70/120)** |

---

## 📈 Phase 4 Log: Deep Learning

### **Part 1: Foundations & Scaling (Days 59-66)**
* **Optimization:** Implemented **Gradient Descent** and **Adam** optimizers.
* **Regularization:** Applied **Dropout** and **L2** to handle the Bias-Variance tradeoff.
* **Automation:** Integrated `EarlyStopping` to optimize training time and model weight restoration.

### **Part 2: Computer Vision & CNNs (Days 67-70)**
Teaching machines to extract spatial features and "see" patterns in pixel data.

* **Day 67-68: Convolutional Mechanics**
  - Explored **Kernels/Filters** for feature mapping.
  - Used **Max Pooling** and **Padding** to manage spatial dimensions.

* **Day 69: MNIST Digit Classifier**
  - Built a multi-layer **CNN** that achieves high accuracy in recognizing handwritten digits.
  - Developed a full pipeline: `Conv2D -> Pooling -> Flatten -> Dense`.

* **Day 70: Data Augmentation**
  - Implemented real-time image transformation layers (`RandomRotation`, `RandomFlip`, `RandomZoom`).
  - **Goal:** Improve model generalization by exposing it to synthetic variety.
  

---

## 📂 Repository Structure

```text
├── 04_DeepLearning/
│   ├── 01_Foundations/         # Tabular Deep Learning & Optimization
│   │   ├── ...
│   │   └── day66_capstone.ipynb
│   └── 02_ComputerVision/      # Image Processing & CNNs
│       ├── day67_convolutions.ipynb
│       ├── day68_pooling_padding.ipynb
│       ├── day69_mnist_cnn.ipynb
│       └── day70_augmentation.ipynb
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
