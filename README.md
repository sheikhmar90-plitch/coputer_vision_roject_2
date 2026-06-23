# 🧠 Computer Vision Projects using Deep Learning

This repository contains two deep learning-based computer vision projects:

1. 🐱🐶 Cat vs Dog Image Classification using CNN  
2. 🔄 Transfer Learning using Pretrained Models (ResNet50 & VGG16)

---

# 📌 1. Cat vs Dog Classification (CNN)

## 📖 Overview
This project uses a Convolutional Neural Network (CNN) to classify images of cats and dogs. The model learns visual patterns such as edges, textures, and shapes to distinguish between the two classes.

---

## ⚙️ Technologies Used
- Python  
- TensorFlow / Keras  
- CNN (Convolutional Neural Network)  
- NumPy  
- Matplotlib  

---

## 🧠 Workflow
- Dataset loading (Cat vs Dog images)  
- Image preprocessing and normalization  
- Data augmentation  
- CNN model building  
- Training and validation  
- Performance evaluation  

---

## 📊 Results
- Model successfully learned binary classification  
- Accuracy and loss curves plotted  
- Predictions tested on unseen images  

---

# 📌 2. Transfer Learning (ResNet50 & VGG16)

## 📖 Overview
This project applies transfer learning using pretrained deep learning models (ResNet50 and VGG16) trained on ImageNet. These models are fine-tuned on a custom dataset (Fruit-360) for multi-class image classification.

---

## ⚙️ Technologies Used
- Python  
- TensorFlow / Keras  
- ResNet50 (Pretrained on ImageNet)  
- VGG16 (Pretrained on ImageNet)  
- ImageDataGenerator  
- NumPy  
- Matplotlib  

---

## 🧠 Workflow
- Dataset loading (Fruit-360 dataset)  
- Image resizing (224×224)  
- Data augmentation and normalization  
- Loading pretrained models  
- Freezing base layers  
- Adding custom classification head  
- Training models  
- Evaluation and comparison  

---

## 📊 Model Performance

| Model     | Train Accuracy | Validation Accuracy |
|-----------|---------------|---------------------|
| ResNet50  | ~69%          | ~72%                |
| VGG16     | ~17%          | Low performance     |

---

## 🔍 Key Observations
- ResNet50 performed significantly better than VGG16  
- ResNet showed strong feature extraction and generalization  
- VGG16 underperformed on this dataset  
- Transfer learning improved performance compared to training from scratch  

---

# 🏁 Final Conclusion

This project demonstrates the effectiveness of deep learning in image classification tasks:

- CNN works well for simple binary classification (Cat vs Dog)  
- Transfer learning improves performance for large multi-class datasets  
- ResNet50 is more powerful than VGG16 for complex image recognition tasks  

Overall, ResNet50 is the best performing model in this project.

---

# 👩‍💻 Author
Maryam Fatima
---
