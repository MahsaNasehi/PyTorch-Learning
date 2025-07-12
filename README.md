# My Learning Course Repository

Welcome to my educational journey! 📚 
This repository contains a structured, 9-part course I completed, along with my personal notes and learnings from each section.

## Overview

- **Total Sections:** 9
- **Format:** Each section has its own file and contains relevant code, notebooks, or documents.
- **Goal:** To build foundational and practical knowledge step-by-step.

---

## Course Structure & Key Learnings

### 1️⃣ Section 1 - Linear Regression & Model Basics

**Description:**  
This section covers the fundamentals of building a simple linear regression model with PyTorch, including how to define, train, and save models.

**What I learned:**
- Building a **Linear Regression** model from scratch using `nn.Linear`
- Using **`L1Loss`** for regression tasks
- Saving and loading model weights using `model.state_dict()` and `torch.save()`

---
### 2️⃣ Section 2 - Binary & Multi-Label Classification

**Description:**  
This section introduces the concepts of binary and multi-label classification using PyTorch. It also explores loss functions, evaluation metrics, and decision boundary visualization.

**What I learned:**
- Implementing **binary classification** models
- Building **multi-label classification** systems
- Using the **`BCEWithLogitsLoss`** (Binary Cross Entropy with logits)
- Understanding the full **training** and **inference** pipeline:
  - Forward pass
  - Loss computation
  - Backward pass
  - Parameter update
  - Evaluation
- Visualizing model decisions with `plot_decision_boundary`
- Using `torchmetrics.Accuracy` for model evaluation

---
### 3️⃣ Section 3 - MNIST & FashionMNIST Classification

**Description:**  
This section focuses on image classification using the MNIST and FashionMNIST datasets. Various neural network architectures are explored, ranging from simple linear layers to more complex convolutional layers.

**What I learned:**
- How to perform classification on **MNIST** and **FashionMNIST** using:
  - Linear layers
  - Non-linear layers (with activation functions)
  - Convolutional Neural Networks (CNNs)
- How to use **`torchvision.datasets`** to load built-in datasets
- Working with **`DataLoader`** for batching and shuffling
- Implementing **loss functions** like `CrossEntropyLoss`
- Using **optimizers** such as `Adam` and `SGD`
- Tracking performance with:
  - **`torchmetrics`** (for accuracy and other metrics)
  - **confusion matrix** (via `mlxtend.plotting.plot_confusion_matrix`)
- Saving and loading trained models using `torch.save()` and `torch.load()`
---

### 4️⃣ Section 4 - Custom Image Classification with PyTorch

**Description:**  
This section focuses on training image classification models on custom datasets using PyTorch. It includes working with standardized folder structures, creating custom dataset classes, and writing flexible, device-agnostic code.

**What I learned:**
- How to structure image datasets in the standard format compatible with `ImageFolder`
- Using `torchvision.datasets.ImageFolder` to automatically load images and assign class labels
- Creating a **custom dataset class** (`ImageFolderCustom`) for more control and customization
- Loading and transforming images with `torchvision.transforms`
- Exploring folder contents with a helper function: `walk_through_dir()`
- Writing **device-agnostic code** using `torch.device` for compatibility with both CPU and GPU
- Visualizing model architecture and parameter details using `torchinfo.summary()`
- Training an image classification model on the **pizza_steak_sushi** dataset

---

### 5️⃣ Section 5 - [Section Title]
**Description:**  
_Short description of this section._

**What I learned:**
- Point 1
- Point 2
- Point 3

---

### 6️⃣ Section 6 - [Section Title]
**Description:**  
_Short description of this section._

**What I learned:**
- Point 1
- Point 2
- Point 3

---

### 7️⃣ Section 7 - [Section Title]
**Description:**  
_Short description of this section._

**What I learned:**
- Point 1
- Point 2
- Point 3

---

### 8️⃣ Section 8 - [Section Title]
**Description:**  
_Short description of this section._

**What I learned:**
- Point 1
- Point 2
- Point 3

---

### 9️⃣ Section 9 - [Section Title]
**Description:**  
_Final thoughts and wrap-up of the course._

**What I learned:**
- Point 1
- Point 2
- Point 3

---

## 🛠 How to Use This Repo

1. Clone the repository:
   ```bash
   git clone https://github.com/MahsaNasehi/PyTorch-Learning.git
