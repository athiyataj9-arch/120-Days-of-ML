# 120 Days of Machine Learning: From Foundations to MLOps 🚀

This repository documents my 120-day journey of mastering Machine Learning, from data preprocessing to deploying production-grade models.

## 🗺️ Progress Roadmap

| Phase | Focus | Status |
| :--- | :--- | :--- |
| **01** | **Foundations (Math, Stats & Preprocessing)** | ✅ **Completed** |
| **02** | **Supervised Learning (Regression & Classification)** | ✅ **Completed** |
| **03** | **Unsupervised Learning (Clustering & Rules)** | ✅ **Completed** |
| **04** | **Deep Learning (Neural Networks, CV & NLP)** | 🏗️ **Active (Day 72/120)** |

---

## 📈 Phase 4 Log: Deep Learning

### **Part 1: Foundations & Scaling (Days 59-66)**
* **Optimization & Loss:** Implemented Gradient Descent, Adam, and Cross-Entropy logic.
* **Automation:** Integrated `EarlyStopping` and `ModelCheckpoint` for efficient training.

### **Part 2: Computer Vision & CNNs (Days 67-70)**
* **CNN Mechanics:** Mastered Convolutions, Max Pooling, and Padding.
* **MNIST Digit Classifier:** Built a custom CNN to recognize handwritten digits.
* **Data Augmentation:** Used `RandomRotation` and `RandomFlip` to improve model generalization.

### **Part 3: Transfer Learning (Days 71-72)**
Leveraging pre-trained "State-of-the-Art" (SOTA) models to solve complex visual tasks with less data.

* **Day 71: VGG16 (The "Deeper" Classic)**
  - Implemented **VGG16** as a frozen base for feature extraction.
  - Learned the "Include Top = False" strategy to customize classification heads.

* **Day 72: ResNet50 (Skip Connections)**
  - Explored **Residual Learning** and why "Skip Connections" prevent vanishing gradients.
  - Compared ResNet's efficiency (lower parameters) vs. VGG16's simplicity.

---

## 📂 Repository Structure

```text
├── 04_DeepLearning/
│   ├── 01_Foundations/         # Tabular Deep Learning
│   │   └── ...
│   └── 02_ComputerVision/      # Image Processing & CNNs
│       ├── day67_convolutions.ipynb
│       ├── day68_pooling_padding.ipynb
│       ├── day69_mnist_cnn.ipynb
│       ├── day70_augmentation.ipynb
│       ├── day71_vgg16_transfer.ipynb
│       └── day72_resnet_residuals.ipynb
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
