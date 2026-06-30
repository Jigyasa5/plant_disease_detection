#  Plant Disease Classification using CNN

---

## Project Overview

This project is a **Deep Learning-based Plant Disease Classification System** that identifies diseases in plant leaves using images. It is built using a **Convolutional Neural Network (CNN)** trained on the **PlantVillage Dataset**.

The model classifies leaf images into different categories such as:

- Healthy plants   
- Tomato diseases  
- Potato diseases  
- Pepper diseases  

---

## Dataset

**PlantVillage Dataset**

- 50,000+ images  
- 15+ plant disease classes used  
- Includes healthy and infected leaves  

---

##  Model Architecture

- Conv2D (32, 64, 128 filters)
- MaxPooling2D
- Flatten
- Dense (128 neurons)
- Dropout (0.5)
- Dense (Softmax output layer)

---

## Tech Stack

- Python   
- TensorFlow / Keras   
- NumPy  
- Matplotlib  
- Kaggle Notebook  

---

## Features

- Image-based plant disease detection  
- Multi-class classification  
- Training & validation accuracy plots  
- Model saving & loading  
- Prediction

---

## Model Performance

- Training Accuracy: ~97%  
- Validation Accuracy: ~92%  
