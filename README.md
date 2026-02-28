# 🧠 Machine Learning Notes (PyTorch Practice)

> Personal ML learning repository  
> 基于 PyTorch 的机器学习学习与实践笔记

---

## 📌 About / 项目简介

This repository contains my hands-on learning experiments in Machine Learning and Deep Learning using **PyTorch**.

The goal is NOT only to run models, but to understand:

- data preprocessing
- tensor shapes
- training pipelines
- optimization strategies
- model generalization

本仓库用于记录我学习机器学习与深度学习的实践过程，重点包括：

- 数据预处理
- Tensor 形状理解
- 训练流程搭建
- 优化策略（learning rate / scheduler）
- 泛化能力理解

---

## 📂 Projects / 项目列表

---

### 🔢 1. MNIST MLP Classifier

**Task / 任务**

- Handwritten digit classification
- 使用多层感知机 (MLP) 识别手写数字

**Key Concepts / 关键学习点**

- PyTorch Dataset & DataLoader
- Neural Network basic structure
- ReLU activation
- Dropout regularization
- Training vs Evaluation mode
- Accuracy evaluation

**Model Structure / 网络结构**
- 784 → Hidden → Hidden → 10

---

### 🏠 2. California Housing Regression (MLP)

**Task / 任务**

- Predict housing prices using tabular data
- 使用 MLP 进行房价回归预测

**Dataset**

- sklearn California Housing dataset

**Key Concepts / 关键学习点**

- Train / Test split
- Feature standardization (StandardScaler)
- Tensor conversion & shape debugging
- Regression vs Classification differences
- MSE Loss
- Adam optimizer
- Learning Rate Scheduler (ReduceLROnPlateau)

**Model Structure / 网络结构**
- Input(8) → 64 → 32 → Output(1)

**Training Strategy / 训练策略**

- No dropout for small tabular model
- LR scheduler for automatic fine-tuning
- Monitor train/test loss

---

## 📊 Key Learnings / 重要学习总结

### EN

- Shape debugging is critical in PyTorch.
- Learning rate scheduling often matters more than changing model architecture.
- Tabular data does not always benefit from deep networks.
- Most performance gains come from data and features.

### 中文

- Tensor 的 shape 是 PyTorch 调试核心。
- 学习率调度的重要性往往大于改网络结构。
- 表格数据不一定适合复杂深度网络。
- 性能提升更多来自数据和特征工程。

---

## 🧩 Tech Stack

- Python
- PyTorch
- NumPy
- scikit-learn
- Jupyter Notebook

---

## 🚀 Future Plans / 后续学习计划

- CNN (Convolutional Neural Networks)
- Feature engineering on tabular data
- Comparing PyTorch vs sklearn models
- Model evaluation & visualization

---

## 👤 Author

Learning notes by **Sun**  
MSc Computer Science @ University of Bristol
