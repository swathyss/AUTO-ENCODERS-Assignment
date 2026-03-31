# 🔢 Autoencoder Implementation using MNIST (Deep Learning)



A deep learning project focused on building and training a **basic Autoencoder** to reconstruct handwritten digit images from the **MNIST dataset**.

---

## 🚀 Run Notebook in Google Colab

Click the button below to open the notebook directly in Google Colab.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_NOTEBOOK_LINK_HERE)

---

# 📘 Project Overview

This project implements a **deep learning Autoencoder model** that learns how to compress and reconstruct images.

The project covers the complete deep learning pipeline including:

* Dataset loading and exploration
* Data preprocessing
* Encoder–Decoder architecture design
* Model training and validation
* Model evaluation
* Visualization of reconstruction results

The goal is to build a model that can **learn efficient representations (latent space)** and reconstruct images with minimal information loss.

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

| Feature         | Description  |
| --------------- | ------------ |
| Total Images    | 70,000       |
| Training Images | 60,000       |
| Test Images     | 10,000       |
| Image Size      | 28 × 28      |
| Color Type      | Grayscale    |
| Classes         | Digits (0–9) |

---

# 🧹 Data Preprocessing

Before training the autoencoder, several preprocessing steps were applied:

### ✔ Normalization

Pixel values were scaled to the range **0–1**.

### ✔ Reshaping

Images were reshaped to match the model input dimensions.

---

# 🧠 Autoencoder Model Architecture

The model consists of two main components:

### 🔹 Encoder

* Compresses input images into a **lower-dimensional latent representation**
* Extracts important features

### 🔹 Decoder

* Reconstructs images from latent representation
* Produces output of the same size as input (28×28)

---

# ⚙ Model Training

The autoencoder model was trained using the **training dataset** and validated on validation data.

### Training Details

* Loss Function: Mean Squared Error (MSE)
* Optimizer: Adam
* Epochs: As defined in notebook
* Batch Size: As defined in notebook

Training progress was monitored using:

* Training Loss
* Validation Loss

---

# 📊 Model Evaluation

After training, the model was evaluated using the **test dataset**.

### Evaluation Outputs

* Model summary
* Training vs validation loss curves
* Reconstruction performance

---

# 🔍 Prediction & Visualization

To better understand the model’s performance:

### ✔ Loss Curve

* Training loss vs validation loss plotted

### ✔ Reconstruction Comparison

* Original vs reconstructed images shown side-by-side

---

# 🛠 Tech Stack

| Tool               | Purpose                 |
| ------------------ | ----------------------- |
| Python             | Programming language    |
| TensorFlow / Keras | Deep learning framework |
| NumPy              | Numerical computation   |
| Matplotlib         | Visualization           |

---

# 📁 Repository Structure

```
autoencoder-mnist/

│
├── DL_Assignment_3_AutoEncoders.ipynb
├── README.md
└── DL Assignment 3 - Auto Encoders.pdf
```

---

# 🚀 How to Run the Project

### 1️⃣ Open the Notebook

Click the **Google Colab button above**.

---

### 2️⃣ Install Required Libraries

```python
pip install tensorflow numpy matplotlib
```

---

### 3️⃣ Run the Notebook

Run all cells sequentially to:

* Load dataset
* Preprocess data
* Train autoencoder
* Evaluate model
* Visualize reconstruction results

---

# 🧠 Key Learning Outcomes

✔ Understanding Autoencoders
✔ Dimensionality reduction
✔ Neural network architecture design
✔ Image reconstruction
✔ Model evaluation techniques
✔ Visualization of results

---

# 📌 Results Summary

The autoencoder successfully learns to compress and reconstruct handwritten digit images.

* Loss decreases over training
* Reconstructed images resemble original digits
* Model captures key features effectively

---

# 📌 Academic Submission

This repository was created as part of a **Deep Learning assignment** to demonstrate the design, training, and evaluation of an **Autoencoder model** using the MNIST dataset.

---
