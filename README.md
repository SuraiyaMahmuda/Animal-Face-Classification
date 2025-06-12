# 🐶🐱 Animal Face Classification

This project implements a deep learning model to classify different **animal faces** using Convolutional Neural Networks (CNNs). It is designed to handle multi-class image classification tasks to leveraging transfer learning with modern CNN architectures and PyTorch, the model is trained on a structured dataset to recognize various animal faces with high accuracy.

---

## 🧠 Key Features

- 🖼️ Image preprocessing and augmentation  
- 🧠 CNN architecture for multi-class classification  
- 📈 Training visualization with accuracy/loss graphs  
- 📊 Evaluation using confusion matrix and metrics  
- 💾 Model saving and loading for inference  

---

## 🧰 Tools & Frameworks

- **Language**: Python 3.8+
- **Framework**: PyTorch
- **Libraries**:
  - torchvision
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - Pillow
- **Development Environment**:
  - Jupyter Notebooks
  - Google Colab / Local
- **Model**: ResNet50 (pretrained)

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

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/SuraiyaMahmuda/Animal-Face-Classification.git
   cd Animal-Face-Classification

 --- 

 ## 🧰 Results

|     🧪 Evaluation Metric      |       🔢 Score (%)        |
|------------------------------|---------------------------|
| Accuracy                     | 93.4%                     |
| Precision                    | 92.8%                     |
| Recall                       | 92.0%                     |
| F1-score                     | 92.4%                     |

