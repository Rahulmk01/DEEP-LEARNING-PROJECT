# DEEP LEARNING

COMPANY NAME : CODTECH IT SOLUTION 

NAME : KOLANKAR RAHUL MADAN

DOMAIN NAME : DATA SCIENCE

INTERNSHIP DURATION : 6 WEEKS

INTERN ID :  CTIS5094

MENTOR : NEELA SANTOSH

# Handwritten Digit Classification using CNN (TensorFlow)

## 📌 Project Overview

This project implements a **Deep Learning model using Convolutional Neural Network (CNN)** to classify handwritten digits (0–9).
The model is trained on the **MNIST dataset**, which contains thousands of labeled handwritten digit images.

The goal of this project is to demonstrate how deep learning can automatically recognize patterns in image data and perform accurate classification.

---

## 🎯 Objective

* Build a deep learning model for image classification.
* Train the model to recognize handwritten digits.
* Visualize training results such as accuracy and loss graphs.
* Evaluate the performance of the trained model.

---

## 🗂 Dataset

The project uses the **MNIST Handwritten Digit Dataset**.

Dataset details:

* 70,000 grayscale images
* Image size: 28 × 28 pixels
* Classes: digits from **0 to 9**
* Training images: 60,000
* Testing images: 10,000

---

## ⚙️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* VS Code

---

## 🧠 Model Architecture

The CNN model consists of the following layers:

1. Convolution Layer (Feature extraction)
2. ReLU Activation
3. Max Pooling Layer
4. Convolution Layer
5. Max Pooling Layer
6. Flatten Layer
7. Dense Layer
8. Output Layer (Softmax)

This architecture helps the model learn patterns in image pixels and classify digits accurately.

---

## 🚀 How to Run the Project

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/digit-classification-cnn.git
cd digit-classification-cnn
```

### 2️⃣ Create Virtual Environment

```
python -m venv venv
```

### 3️⃣ Activate Virtual Environment

Windows:

```
venv\Scripts\activate
```

### 4️⃣ Install Required Libraries

```
pip install tensorflow numpy matplotlib
```

### 5️⃣ Run the Model

```
python cnn_model.py
```

---

## 📊 Output

After running the program:

* The model will train on the MNIST dataset
* Training progress will be shown with **epochs**
* Test accuracy will be printed
* Accuracy graph will be displayed

Example output:

```
Epoch 1/5
Epoch 2/5
...
Test Accuracy: 0.98
Predicted Digit: 7
```

---

## 📈 Result

The CNN model achieves approximately **97–99% accuracy** on the MNIST test dataset, demonstrating the effectiveness of deep learning for image classification tasks.

---

## 📌 Project Structure

```
Task 2/
│
├── venv/
├── cnn_model.py
└── README.md
```

---

## 📚 Learning Outcome

Through this project, we learned:

* Basics of Deep Learning
* Image classification using CNN
* Using TensorFlow for model development
* Training and evaluating neural networks
* Visualizing model performance

---

## 👨‍💻 Author

Rahul Kolankar
