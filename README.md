# 🧠 PyTorch Computer Vision Classifier

This is a beginner-to-intermediate level project built using **PyTorch** for image classification on the **FashionMNIST** dataset. The goal is to explore and compare different model architectures — from simple linear layers to convolutional neural networks (CNNs) — and understand the full deep learning workflow from data loading to evaluation and model saving.

---

## 📌 Features

- 🔹 **Dataset**: FashionMNIST (60,000 training / 10,000 test grayscale images)
- 🔹 **Models Implemented**:
  - `ModelV0`: Linear classifier (no hidden layers)
  - `ModelV1`: Multi-layer Perceptron with ReLU
  - `ModelV2`: CNN with two convolutional blocks
- 🔹 **Training & Evaluation**:
  - Custom training/testing loops
  - Accuracy calculation and visualization
  - Comparison of all models in a results DataFrame
- 🔹 **Visualization**:
  - Sample images and predictions
  - Confusion matrix with `torchmetrics` and `mlxtend`
- 🔹 **Model Saving & Reloading** using `torch.save` and `torch.load`

---

## 🖼️ Sample Output

> FashionMNIST contains grayscale images of clothing items like t-shirts, trousers, sandals, etc.  
> Here’s an example grid of images visualized from the dataset:

![Sample FashionMNIST](https://upload.wikimedia.org/wikipedia/commons/5/5a/Fashion-MNIST_Sample_Images.png)

---

## 🔧 Tech Stack

- **Python 3**
- **PyTorch**
- `torchvision`, `matplotlib`, `pandas`, `mlxtend`, `torchmetrics`
- Optional: Google Colab or local Jupyter Notebook environment

---

## 📂 File Structure

├── PyTorch_Computer_Vision.ipynb # Jupyter notebook (interactive)
├── pytorch_computer_vision.py # Script version of the same notebook
├── helper_functions.py # Accuracy function from Daniel Bourke's PyTorch repo
├── models/ # Folder to save trained model
│ └── pytorch_computer_vision_model_2.pth


🙌 Credits
Built as part of a hands-on PyTorch learning journey

Helper function from Daniel Bourke’s PyTorch Deep Learning Repo
