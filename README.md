# 120 Days of Machine Learning: From Foundations to MLOps 🚀

This repository documents my 120-day journey of mastering Machine Learning, from data preprocessing to deploying production-grade models.

## 🗺️ Progress Roadmap

| Phase | Focus | Status |
| :--- | :--- | :--- |
| **01** | **Foundations (Math, Stats & Preprocessing)** | ✅ **Completed** |
| **02** | **Supervised Learning (Regression & Classification)** | ✅ **Completed** |
| **03** | **Unsupervised Learning (Clustering & Rules)** | ✅ **Completed** |
| **04** | **Deep Learning (Neural Networks, CV & GenAI)** | ✅ **Completed (Day 80/120)** |
| **05** | **Natural Language Processing (NLP & Transformers)** | 🏗️ **Upcoming (Day 81)** |

---

## 📈 Phase 4 Log: Deep Learning & Computer Vision

### **Part 1: Foundations & CNNs (Days 59-70)**
* **Optimization:** Implemented Adam optimizer and Cross-Entropy loss logic.
* **CNN Mechanics:** Mastered Convolutions, Max Pooling, and Padding from scratch.
* **Augmentation:** Used `ImageDataGenerator` to improve model robustness and generalization.

### **Part 2: Transfer Learning & Detection (Days 71-76)**
* **SOTA Models:** Leveraged **VGG16** and **ResNet50** (Skip Connections) for feature extraction.
* **YOLOv8 Detection:** Implemented real-time Object Detection for multi-class tasks (Bus, Person).
* **Instance Segmentation:** Achieved pixel-level precision using **YOLOv8-seg** to generate object masks.

### **Part 3: Generative AI & Autoencoders (Days 77-80)**
* **Autoencoders (AE):** Built an "hourglass" architecture for dimensionality reduction.
* **Denoising AE:** Developed a Convolutional "Cleaner" to restore grainy or corrupted images.
* **VAEs:** Implemented the **Reparameterization Trick** to sample from a learned latent space.
* **GANs:** Orchestrated a competition between a **Generator** and **Discriminator** to create synthetic data.

---

## 📂 Repository Structure

```text
├── 04_DeepLearning/
│   ├── 01_Foundations/         # Tabular Deep Learning
│   └── 02_ComputerVision/      # Image Processing & Generative AI
│       ├── day74_yolo_intro.ipynb
│       ├── day75_object_detection.ipynb
│       ├── day76_segmentation.ipynb
│       ├── day77_autoencoders.ipynb
│       ├── day78_denoising.ipynb
│       ├── day79_vae.ipynb
│       └── day80_gans.ipynb
├── 05_NLP/                     # Upcoming Phase: Language Modeling
├── assets/                     # Visual Gallery (YOLO results, AE reconstructions)
└── requirements.txt            # Project dependencies (Tensorflow 2.21.0+, Ultralytics)
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
