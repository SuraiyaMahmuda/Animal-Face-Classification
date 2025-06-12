# 🐶 Animal Face Classification

This project implements a deep learning model to classify different **animal faces** using Convolutional Neural Networks (CNNs). It is designed to handle multi-class image classification tasks and was developed using **Python** and **TensorFlow/Keras** in a **Jupyter Notebook** environment.

---

## 🧠 Key Features

- 🖼️ Image preprocessing and augmentation  
- 🧠 CNN architecture for multi-class classification  
- 📈 Training visualization with accuracy/loss graphs  
- 📊 Evaluation using confusion matrix and metrics  
- 💾 Model saving and loading for inference  

---

## 🐾 **Dataset**

The dataset used includes face images of various animals (e.g., **cats**, **dogs**, **pandas**).

---

## 🚀 How It Works

1. **Data Preprocessing**  
   - Load image dataset  
   - Resize, normalize, and augment images  

2. **Model Building**  
   - Construct CNN with Conv2D, MaxPooling2D, Flatten, and Dense layers  
   - Use `categorical_crossentropy` as loss and `Adam` optimizer  

3. **Training**  
   - Fit model with training data and validate on test split  
   - Visualize accuracy and loss per epoch  

4. **Evaluation**  
   - Use accuracy, classification report, and confusion matrix  
   - Display random predictions for visual inspection  

---

## 🔧 Requirements

Install dependencies with:

```bash
pip install -r requirements.txt


