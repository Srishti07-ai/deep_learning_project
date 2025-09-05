# deep_learning_project

# 🐶🐱 Cats vs Dogs Classifier

A Convolutional Neural Network (CNN) built with **TensorFlow/Keras** to classify images of cats and dogs.  
The model is trained on the [Kaggle Cats vs Dogs dataset](https://www.kaggle.com/datasets/tongpython/cat-and-dog) and achieves **~70–80% validation accuracy**.

---

## 📂 Dataset
- Source: [Kaggle - Cats vs Dogs (Tongpython)](https://www.kaggle.com/datasets/tongpython/cat-and-dog)  
- Structure after preprocessing:  

- Images resized to **128×128** and pixel values normalized (0–1).  
- Split: **80% training, 20% validation**.

---

## 🛠️ Tech Stack
- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Google Colab  

---

## 🧠 Model Architecture
- **Conv2D → ReLU → BatchNormalization → MaxPooling**  
- **Conv2D → ReLU → BatchNormalization → MaxPooling**  
- **Conv2D → ReLU → BatchNormalization → MaxPooling**  
- **Flatten → Dense(128, ReLU) → Dropout**  
- **Dense(64, ReLU) → Dropout → Dense(1, Sigmoid)**  

---

## 🚀 Training
- Optimizer: **Adam**  
- Loss: **Binary Crossentropy**  
- Metrics: **Accuracy**  
- Epochs: **10–15**  

---

## 📊 Results
- Validation Accuracy: **~70–80%**  
- Training and validation accuracy/loss curves plotted for performance visualization.  

---

## ▶️ How to Run
1. Clone this repository:  
 ```bash
 git clone https://github.com/your-username/cats-vs-dogs-classifier.git
 cd cats-vs-dogs-classifier
```
#Install dependencies
pip install tensorflow matplotlib numpy

