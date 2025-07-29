# 🧠 Handwritten Digit Classifier

This project implements a **Multi-Layer Perceptron (MLP)** neural network using **PyTorch** to classify **handwritten digits** from the MNIST dataset. It is designed as a ** AI/ML project**, suitable for academic showcase and placement portfolios.

---

## ✨ Features

- Custom PyTorch `Dataset` and `DataLoader` pipeline
- Reads raw MNIST `.idx` files using `idx2numpy`
- Fully connected MLP with ReLU activations
- Trains with **Stochastic Gradient Descent (SGD)**
- Simple, readable architecture for easy understanding

---

## 🏗️ Model Architecture

Input: 784 (flattened 28x28 image)
→ Linear(784 → 128) + ReLU
→ Linear(128 → 64) + ReLU
→ Linear(64 → 10) → Output (digit class)


---

## 📁 Dataset

The project uses the original **MNIST** dataset in `.idx` format:
- `train-images.idx3-ubyte`
- `train-labels.idx1-ubyte`

You can download it from [https://www.kaggle.com/datasets/hojjatk/mnist-dataset](https://www.kaggle.com/datasets/hojjatk/mnist-dataset) and upload to Colab `/content/`.

---

### Example Output:
- Final Training Accuracy: **96.89%**
- Loss: Decreasing steadily to near 0.013 (before any instability)

## 🚀 How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Upload the MNIST `.idx` files to `/content/`
3. Run all cells to train the model
4. View the training loss and predictions

---


