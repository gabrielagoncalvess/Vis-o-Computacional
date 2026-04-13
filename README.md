# Vis-o-Computacional

# 🪨 Mineral Classification using Deep Learning
---

## 📖 Overview

This project applies **Deep Learning techniques (Convolutional Neural Networks - CNNs)** to classify mineral images, focusing on the identification of:

- 🪨 Spodumene
- 🟠 Copper-bearing materials

The system learns visual patterns from images and predicts the mineral class based on pixel-level features.

---

## 🎯 Objective

To develop an **automated image classification model** capable of identifying mineral types using computer vision techniques, reducing manual classification effort in geological analysis.

---

## 🧠 Model Architecture

- Convolutional Neural Network (CNN)
- Feature extraction layers (Conv2D + ReLU + MaxPooling)
- Fully connected classification layers
- Softmax output for multi-class prediction

---

## 📊 Dataset

The dataset consists of labeled images of mineral samples:

| Class | Description |
|------|------------|
| Spodumene | Lithium-bearing mineral |
| Copper | Copper ore samples |

Images were preprocessed with:
- Resizing
- Normalization
- Data augmentation (rotation, flip, zoom)

---

## ⚙️ Methodology

1. 📥 Image dataset collection  
2. 🧹 Preprocessing and normalization  
3. 🔀 Train/test split  
4. 🧠 CNN model training  
5. 📊 Model evaluation  
6. 🔮 Image classification prediction  

---

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 🚀 Technologies Used

- Python 🐍
- TensorFlow / Keras 🤖
- OpenCV 📷
- NumPy 🔢
- Matplotlib 📊

---

## 🔍 Example Prediction

Input: Mineral image  
Output:
- Spodumene → 0.92 probability
- Copper → 0.08 probability

---

## 📌 Applications

- Mining industry automation ⛏️
- Mineral exploration support
- Geological classification systems
- AI-assisted ore identification

---

## 👩‍🔬 Author

Project developed for research in:
- Artificial Intelligence 🤖
- Mining Engineering ⛏️
- Computer Vision 📷

---

## 📜 License

Academic and research use only.
