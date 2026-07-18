# MNIST-PROJECT-
Modified National Institute of Standards and Technology 
# Handwritten Digit Recognition using PyTorch (MNIST)

## 📌 Project Overview

This project is a Handwritten Digit Recognition System built using **PyTorch** and the **MNIST dataset**. The model is trained to recognize handwritten digits (0–9) using a simple Feedforward Neural Network (Artificial Neural Network).

After training, the model predicts the digit from an unseen handwritten image with high accuracy.

---

## 🚀 Features

- Loads the MNIST dataset automatically

- Converts images into PyTorch tensors

- Builds a Feedforward Neural Network

- Trains the model using the Adam optimizer

- Evaluates model accuracy on the test dataset

- Saves the trained model (`mnist.pth`)

- Displays a test image and predicts its digit

---

## 🛠️ Technologies Used

- Python

- PyTorch

- Torchvision

- Matplotlib

---

## 📂 Dataset

The project uses the **MNIST** dataset.

- 60,000 Training Images

- 10,000 Testing Images

- Image Size: 28 × 28 pixels

- Grayscale Images

- Classes: Digits 0–9

---

## 🧠 Model Architecture

The neural network consists of:

Input Layer:

- 784 neurons (28 × 28 image)

Hidden Layer 1:

- 128 neurons

- ReLU Activation

Hidden Layer 2:

- 64 neurons

- ReLU Activation

Output Layer:

- 10 neurons (Digits 0–9)

---

## ⚙️ Training Configuration

- Optimizer: Adam

- Loss Function: CrossEntropyLoss

- Batch Size: 64

- Epochs: 5

- Learning Rate: 0.001

---

## 📈 Results

The model achieves approximately **97–98% accuracy** on the MNIST test dataset.

Example Output:

```

Using device: CPU

Epoch 1/5 | Loss: ...

Epoch 2/5 | Loss: ...

Epoch 3/5 | Loss: ...

Epoch 4/5 | Loss: ...

Epoch 5/5 | Loss: ...

Total Accuracy: 97.5%

Model Saved Successfully

```

---

## 📁 Project Structure

```

.

├── mnist.py          # Main training script

├── mnist.pth         # Saved trained model

├── data/             # MNIST dataset (auto-downloaded)

└── README.md

```

---

## ▶️ How to Run

### 1. Clone the repository

```bash

git clone https://github.com/yourusername/your-repository.git

```

### 2. Navigate to the project

```bash

cd your-repository

```

### 3. Install dependencies

```bash

pip install torch torchvision matplotlib

```

### 4. Run the project

```bash

python mnist.py

```

---

## 📚 What I Learned

Through this project, I learned:

- PyTorch basics

- Neural Networks

- Feedforward Networks

- DataLoader

- Model Training

- Backpropagation

- Loss Functions

- Optimizers

- Model Evaluation

- Saving and Loading Models

---

## 📌 Future Improvements

- Add Convolutional Neural Network (CNN)

- Build a GUI for digit prediction

- Allow prediction on custom handwritten images

- Improve model accuracy

- Deploy the model as a web application

---

## 👨‍💻 Author

**Manan Sharma**

B.Tech Computer Science Engineering

Learning Python, Machine Learning, and Deep Learning.
