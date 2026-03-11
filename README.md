# 🍎 Intelligent Image Classification System for Fruit Recognition

This project implements a **Deep Learning based Image Classification System** to recognize different types of fruits using **Convolutional Neural Networks (CNN)**.

The system automatically classifies fruit images into predefined categories with high accuracy.

This project was developed for the course:

**ICT 3212 – Introduction to Intelligent Systems**

---

## 👥 Team Information

**Team Name:** IntelliVersion

**Members**
- S. Abisan – ICT/2022/004
- S. Thuvaraka – ICT/2022/014
- S. Birunthatharan – ICT/2022/028
- S. Shajith – ICT/2022/108

---

## 📌 Project Overview

Image classification is an important task in **computer vision** where machines learn to identify objects inside images.

This project builds a **fruit recognition system** using a CNN model that can classify fruit images into multiple categories.

The project was developed in **two implementations**:

1. **Implementation 1 (Baseline Model)**  
   - Basic CNN architecture  
   - Image size: 128 × 128  
   - Achieved ~76% accuracy

2. **Implementation 2 (Improved Model)**  
   - Data augmentation  
   - Batch normalization  
   - Dropout regularization  
   - Hyperparameter tuning  
   - Achieved ~90% accuracy

---

## 🍍 Fruit Classes

The system can recognize the following **8 fruit categories**:

- Apple  
- Avocado  
- Banana  
- Grapes  
- Mangosteen  
- Orange  
- Pineapple  
- Pomegranate  


---

## 📁 Dataset Structure

The dataset is organized into **train, validation, and test folders**.

```
Fruit/
│
├── train/
│   ├── Apple
│   ├── Avocado
│   ├── Banana
│   ├── Grapes
│   ├── Mangosteen
│   ├── Orange
│   ├── Pineapple
│   └── Pomegranate
│
├── val/
│
└── test/
```

Each class contains images belonging to the corresponding fruit category.

---

## ⚙️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 🧠 Model Architecture

The CNN model includes:

- Convolutional Layers
- MaxPooling Layers
- Batch Normalization
- Dropout Regularization
- Fully Connected Dense Layers
- Softmax Output Layer

These layers allow the model to learn visual features such as **edges, shapes, and textures** from images.

---

## 🔧 Image Preprocessing

Before training the model, the following preprocessing steps were applied:

- Image resizing
- Pixel normalization
- Tensor conversion
- Dataset splitting
- Batch loading

---

## 📊 Model Performance

### Implementation 1
- Test Accuracy: **~76%**

### Implementation 2
- Test Accuracy: **89.63%**

Model improvements helped reduce **overfitting** and increased **generalization performance**. :contentReference[oaicite:1]{index=1}

---

## 📈 Improvements in Implementation 2

Key improvements made:

- Larger input size (224×224)
- Data augmentation
- Batch normalization
- Dropout layers
- Early stopping
- Learning rate scheduling

These improvements significantly enhanced classification accuracy. :contentReference[oaicite:2]{index=2}

---

## 💾 Saved Model

The trained model is stored externally due to GitHub size limitations.

**Model File**
```

CNN_MODEL_FRUIT_CLASSIFICATION_002.h5

```

**Download Model**
```

https://drive.google.com/drive/folders/1c-Dqwn5XU3gkcK36fI38m5QcTaXSF6fi

```

---

## 🚀 Future Improvements

Possible improvements include:

- Using larger datasets
- Applying transfer learning (ResNet, MobileNet)
- Real-time fruit recognition
- Mobile application integration
- Embedded system deployment

---

## 📄 Project Report

Full project documentation is available here:

**Implementation Report:**  
See the project PDF for detailed explanation of the dataset, model training, evaluation, and results. :contentReference[oaicite:3]{index=3}

---

## 📜 License

This project is created for **academic and educational purposes**.

