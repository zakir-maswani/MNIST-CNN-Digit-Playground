# 🧠 **MNIST Digit Recognition using CNN**

This project is an **end-to-end implementation** of a **Convolutional Neural Network (CNN)** trained on the **MNIST handwritten digits dataset**, achieving **99% accuracy**, and deployed using **Streamlit** for real-time digit prediction.

---

## 🚀 Project Overview

The goal of this project is to build, train, and deploy a deep learning model that can accurately recognize handwritten digits (0–9).  
The trained CNN model is integrated into a Streamlit web application where users can upload an image of a handwritten digit and get instant predictions.

---

## ✨ Features

- CNN-based handwritten digit classification  
- Trained on MNIST dataset with **99% accuracy**  
- Streamlit web application  
- Real-time digit prediction  
- Clean and modular project structure  

---

## 🛠 Tech Stack

- Python  
- TensorFlow / Keras  
- NumPy  
- Pillow  
- Streamlit
- Pandas
- Matplotlib
- Seaborn
- Streamlit 

---

## 🧠 Model Details

- Input Shape: `28 × 28 × 1`
- Architecture:
  - Conv2D
  - MaxPooling
  - Flatten
  - Dense Layers
  - Softmax Output Layer
- Optimizer: Adam  
- Loss Function: Categorical Crossentropy  
- Accuracy Achieved: **~99%**

---

## ▶️ How to Run the Project Locally

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/mnist-digit-recognition-cnn-streamlit.git
cd mnist-digit-recognition-cnn-streamlit

---

## 3️⃣ Run the Streamlit App
```bash
streamlit run app.py
