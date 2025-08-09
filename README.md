# AI Deep Learning Animal Classification

An end-to-end deep learning image classification system for identifying animal subspecies using transfer learning with TensorFlow/Keras.  
Developed as part of a Machine Learning course project.

---

## 📌 Project Overview
This project classifies images into **4 animal subspecies** using a custom dataset of 4,000 images.  
It implements and compares multiple state-of-the-art convolutional neural network (CNN) architectures with transfer learning.

---

## 📂 Dataset
- **Total Images:** 4,000  
- **Classes:** Cheetah, Hyena, Jaguar, Tiger  
- **Data Collection:** Web scraping from various online sources  
- **Preprocessing:** Cleaning, resizing, normalization  
- **Splits:** 70% training, 15% validation, 15% testing  

---

## 🛠️ Technologies & Libraries
- **Programming Language:** Python  
- **Frameworks:** TensorFlow, Keras  
- **Models Used:**
  - ResNet50  
  - DenseNet121  
  - MobileNetV3  
- **Other Tools:** NumPy, Pandas, Matplotlib, Scikit-learn, BeautifulSoup/Selenium (for scraping)

---

## ⚙️ Features
- Custom dataset collection and preprocessing
- Transfer learning with multiple CNN architectures
- Model training, fine-tuning, and hyperparameter tuning
- Performance evaluation using:
  - Accuracy
  - Mean Average Precision (mAP)
  - Confusion Matrix
  - Training time comparison

---

## 📊 Results
| Model       | Accuracy |  mAP  | Training Time |
| ----------- | -------- | ----- | ------------- |
| ResNet50    | 92.5%    | 91.3% |    40 mins    |
| DenseNet121 | 94.1%    | 93.8% |    53 mins    |
| MobileNetV3 | 90.4%    | 89.7% |    52 mins    |
