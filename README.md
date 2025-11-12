# 🧠 Brain Tumor Detection using CNN and Intelligent Water Drops (IWD) – MATLAB

**Branch:** Electronics and Communication Engineering (ECI)
**Semester:** 5th
**Course:** Digital Image Processing

---

## 📘 Project Overview

This project implements a **Brain Tumor Detection System** that integrates a **Convolutional Neural Network (CNN)** with the **Intelligent Water Drops (IWD)** optimization algorithm.
Developed in **MATLAB**, it automates the process of detecting and classifying brain tumors from MRI scans and provides an interactive **Graphical User Interface (GUI)** for visualization.

The system performs:

* MRI image preprocessing
* CNN-based tumor classification
* IWD-based optimization for improved accuracy
* Segmentation and visualization through MATLAB GUI

---

## ⚙️ Key Features

* 🧠 **Custom CNN Model:** Designed and trained on MRI images for tumor classification
* 💧 **Intelligent Water Drops (IWD):** Optimizes CNN parameters to enhance learning and convergence
* 🖥️ **MATLAB GUI (`brain_tumor_gui.m`):** Visual interface for selecting, testing, and visualizing MRI scans
* 🧩 **Dataset Support:** Works with publicly available MRI brain tumor datasets
* 📊 **Performance Metrics:** Displays Accuracy, Precision, Recall, and F1-score

---

## 🔬 Workflow Pipeline

```
MRI Image → Preprocessing → CNN Feature Extraction → IWD Optimization
         → Tumor Detection / Segmentation → GUI Visualization
```

---

## 🧮 Algorithm Components

### 1️⃣ Convolutional Neural Network (CNN)

* Extracts spatial and texture features from MRI images
* Trained to classify images into *Normal* or *Tumor* classes
* Architecture typically includes:

  * Convolutional layers
  * ReLU activation
  * Max Pooling layers
  * Fully Connected layer
  * Softmax output layer

### 2️⃣ Intelligent Water Drops (IWD)

* A nature-inspired optimization algorithm simulating river systems
* Used to fine-tune CNN hyperparameters (e.g., learning rate, filter size)
* Improves model convergence and detection accuracy

### 3️⃣ MATLAB GUI

* Provides an easy interface for:

  * Loading MRI images
  * Running CNN-IWD detection pipeline
  * Viewing segmentation output and metrics
* File: `brain_tumor_gui.m`

---

## 🧠 Dataset

Supported sources:

* [Kaggle – Brain MRI Images for Brain Tumor Detection](https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection)
* [Figshare – Brain Tumor MRI Dataset](https://figshare.com/articles/dataset/brain_tumor_dataset/1512427)


---

## 💻 Software Requirements

* MATLAB R2018a or later
* Deep Learning Toolbox
* Image Processing Toolbox
* (Optional) Parallel Computing Toolbox for faster CNN training

---

## 🚀 How to Run

### 🧩 Option 1 — Using the GUI

1. Open MATLAB and set the project root as the current directory
2. Run the command:

   ```matlab
   brain_tumor_gui.m
   ```
3. Use the GUI to:

   * Load MRI images
   * Perform CNN + IWD based detection
   * Visualize segmentation and metrics

### 🧠 Option 2 — Manual Execution

1. **Train CNN model:**

   ```matlab
   cnn_tumor_train
   ```
2. **Test or predict new images:**

   ```matlab
   cnn_tumor_test
   ```
3. The trained model will classify images as *Normal* or *Tumor* and output metrics.

---

## 📊 Expected Outputs

* Tumor detection accuracy (%)
* Precision, Recall, and F1-Score
* Visualization of:

  * Original MRI image
  * Predicted segmentation mask
  * Classified result

---

## ⚠️ Notes

* Ensure all required MATLAB toolboxes are installed before running the project.
* For large MRI images, resize them (e.g., 128×128 or 256×256) for efficient CNN training.
* The IWD optimization may increase training time but improves model accuracy.

---

## 📚 Future Enhancements

* Implement **3D MRI analysis** using volumetric CNNs
* Integrate **UNet or ResNet** architectures for advanced segmentation
* Add **Dice / IoU score visualization** in GUI
* Deploy as a standalone MATLAB app

---

## 📄 License & Credits

* Developed using MATLAB and GUIDE
* Course Project: **Digital Image Processing (ECI 5th Semester)**
---
