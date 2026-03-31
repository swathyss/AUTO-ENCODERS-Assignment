# 🔢 Autoencoder Implementation using MNIST (Deep Learning)

![Python](https://img.shields.io/badge/Python-3.9-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange)
![Model](https://img.shields.io/badge/Model-Autoencoder-green)
![Dataset](https://img.shields.io/badge/Dataset-MNIST-yellow)

A deep learning project focused on building and training a **basic Autoencoder** to reconstruct handwritten digit images from the **MNIST dataset**.

---

## 🚀 Run Notebook in Google Colab

Click below to open the notebook:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_NOTEBOOK_LINK_HERE)

---

# 📘 Project Overview

This project implements a **deep learning Autoencoder model** that learns how to compress and reconstruct images.

The workflow includes:

- Loading and preprocessing MNIST data  
- Designing encoder and decoder networks  
- Training the autoencoder  
- Evaluating reconstruction performance  
- Visualizing results  

The goal is to **learn efficient data representation (latent space)** and reconstruct images with minimal loss.

---

# 🎯 Objective

The main objectives of this project are:

🔹 Build an encoder to compress 28×28 images  
🔹 Build a decoder to reconstruct images  
🔹 Train the autoencoder on MNIST dataset  
🔹 Evaluate reconstruction quality  
🔹 Visualize original vs reconstructed images  
🔹 Analyze model performance  

---

# 📂 Dataset Information

The dataset used is the **MNIST Handwritten Digits Dataset**.

### Dataset Details

| Feature | Description |
|------|-------------|
| Total Images | 70,000 |
| Training Images | 60,000 |
| Test Images | 10,000 |
| Image Size | 28 × 28 |
| Color Type | Grayscale |
| Classes | Digits (0–9) |

---

# 🧹 Data Preprocessing

Before training, the following preprocessing steps were applied:

### ✔ Normalization
Pixel values scaled to **0–1** by dividing by 255.

### ✔ Reshaping
Images reshaped to match model input format.

---

# 🧠 Autoencoder Architecture

The model consists of two main parts:

### 🔹 Encoder
- Compresses input image into a **latent representation**
- Reduces dimensionality

### 🔹 Decoder
- Reconstructs the image from latent space
- Outputs image of original size (28×28)

---

# ⚙ Model Training

The autoencoder was trained using the MNIST training dataset.

### Training Details

- Loss Function: Mean Squared Error (MSE)  
- Optimizer: Adam  
- Epochs: (as used in notebook)  
- Batch Size: (as used in notebook)  

Training progress is monitored using:

- Training Loss  
- Validation Loss  

---

# 📊 Model Evaluation

After training, the model was evaluated on the **test dataset**.

### Evaluation Includes:

- Model Summary  
- Loss Curves (Training vs Validation)  
- Reconstruction Performance  

---

# 🔍 Visualization Results

To assess performance:

### ✔ Loss Curve
- Training vs Validation loss plotted

### ✔ Reconstruction Comparison
- Original images vs reconstructed images displayed side-by-side

---

# 🛠 Tech Stack

| Tool | Purpose |
|----|----|
| Python | Programming |
| TensorFlow / Keras | Deep Learning |
| NumPy | Numerical operations |
| Matplotlib | Visualization |

---

# 📁 Repository Structure
