# AI Healthcare Deep Learning

Deep learning applied to healthcare: medical image analysis, signal processing, NLP, and reinforcement learning for clinical decision support.


## Table of Contents

- [Overview](#overview)
- [Project: Blood Cell Classification](#project-blood-cell-classification)
- [Practical Labs](#practical-labs)
- [Course Topics](#course-topics)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [License](#license)


## Overview

This repository covers a wide range of deep learning techniques applied to real-world healthcare problems — from medical image classification to physiological signal analysis and autonomous glucose control. Each notebook is self-contained and designed to run on Google Colab with GPU runtime.


## Project: Blood Cell Classification

**Main project** — Classification of blood cell types using CNN and Vision Transformer architectures.

| Model | Architecture | Description |
|-------|-------------|-------------|
| Custom CNN | Convolutional Neural Network | Built from scratch for blood cell classification |
| Vision Transformer (ViT) | Transformer | Patch-based image classification with self-attention |
| VGG19 | Transfer Learning | Fine-tuned pretrained VGG19 on blood cell dataset |

**Notebook:** [`project_blood_cell_classification.ipynb`](https://colab.research.google.com/github/nolancacheux/AI-Healthcare-Deep-Learning/blob/main/project_blood_cell_classification.ipynb)


## Practical Labs

| # | Lab | Topic | Techniques |
|---|-----|-------|------------|
| 1 | [Heart Disease Prediction](notebooks/1_MLP_Heart_Disease.ipynb) | Tabular / Classification | Multi-Layer Perceptron, binary classification, feature engineering |
| 2 | [Lung Cancer Detection](notebooks/2_CNN_Lung_cancer.ipynb) | Medical Imaging | CNN, multi-class classification, image preprocessing |
| 3 | [Fetal Heart Rate Segmentation](notebooks/3_U_NET_FHR.ipynb) | Signal Segmentation | U-Net, physiological signal analysis, FHR baseline detection |
| 4 | [Multiple Sclerosis Diagnosis](notebooks/4_IEFs_transformer_CNN.ipynb) | Medical Imaging | Vision Transformers vs CNN, oligoclonal band detection, isoelectric focusing |
| 5 | [Foot Pose Detection](notebooks/5_Foot_Pose_Detection_SETR.ipynb) | Pose Estimation | SETR (Segmentation Transformer), temporal segmentation |
| 6 | [Glucose Control](notebooks/6_RL_Glucose_Control.ipynb) | Reinforcement Learning | RL agent for automatic blood glucose regulation |


## Course Topics

Comprehensive lecture materials covering the full deep learning pipeline for healthcare:

| # | Topic | Key Concepts |
|---|-------|-------------|
| 1 | **AI & Neural Networks** | Perceptrons, backpropagation, activation functions, loss functions, optimization |
| 2 | **Convolutional Neural Networks** | Convolution layers, pooling, feature maps, image classification architectures |
| 3 | **VAE, U-Net, GAN & Diffusion** | Variational autoencoders, image segmentation, generative adversarial networks, diffusion models |
| 4 | **NLP & Recurrent Neural Networks** | Word embeddings, RNN, LSTM, GRU, sequence-to-sequence, text classification |
| 5 | **Transformers** | Self-attention, multi-head attention, Vision Transformers (ViT), BERT, GPT |
| 6 | **Reinforcement Learning** | MDPs, Q-learning, policy gradient, deep RL, clinical applications |

Slides available in [`slides/`](slides/).


## Repository Structure

```
├── project_blood_cell_classification.ipynb   # Main project notebook
├── notebooks/
│   ├── 1_MLP_Heart_Disease.ipynb             # Lab 1: Heart disease prediction (MLP)
│   ├── 1_MLP_Heart_Disease_correction.ipynb  # Lab 1: Correction
│   ├── 2_CNN_Lung_cancer.ipynb               # Lab 2: Lung cancer detection (CNN)
│   ├── 3_U_NET_FHR.ipynb                     # Lab 3: Fetal heart rate (U-Net)
│   ├── 4_IEFs_transformer_CNN.ipynb          # Lab 4: MS diagnosis (ViT vs CNN)
│   ├── 5_Foot_Pose_Detection_SETR.ipynb      # Lab 5: Pose detection (SETR)
│   └── 6_RL_Glucose_Control.ipynb             # Lab 6: Glucose control (RL)
├── slides/                                    # Course lecture slides (PPTX)
├── data/                                      # FHR baseline dataset
└── docs/                                      # Project documentation
```


## Getting Started

All notebooks are designed for **Google Colab** with GPU runtime:

1. Click any notebook link above
2. Open in Google Colab
3. Set runtime to **GPU** (`Runtime > Change runtime type > T4 GPU`)
4. Run all cells

No local installation required — all dependencies are installed inline.


## License

MIT
