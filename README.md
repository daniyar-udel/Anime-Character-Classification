# Anime Character Classification

## Project Overview
This project focuses on building a deep learning model for classifying **15 main anime characters** from images.  
The dataset is imbalanced, so preprocessing and balancing techniques were applied.  
Multiple deep learning approaches were tested, ranging from simple neural networks to state-of-the-art architectures like **EfficientNet** and **Vision Transformers (ViT)**.

---

## Methodology

**Dataset:**
- Source: [Top 15 Anime Main Characters – Kaggle](https://www.kaggle.com/datasets/tarundalal/top-15-anime-main-charcters)  
- 15 classes (anime characters).  
- Images normalized and resized to a consistent size.  
- Split into training, validation, and test sets.  

**Modeling approach:**
- Dense Neural Network (baseline).  
- CNN trained from scratch.  
- Transfer Learning:  
  - **EfficientNet**  
  - **Vision Transformer (ViT)**  

**Training setup:**
- Device: GPU.  
- Optimizers: Stochastic Gradient Descent (SGD), Adam.  
- Loss function: Cross-Entropy.  

**Evaluation metrics:**
- Accuracy  
- Classification report  

---

## Results

- **Dense Neural Network:** poor performance (baseline).  
- **CNN (from scratch):** improved performance.  
- **EfficientNet (Transfer Learning):** ~90–95% accuracy.  
- **Vision Transformer (ViT):** strong results, comparable to EfficientNet.  

Transfer learning significantly outperforms training from scratch, demonstrating the value of pre-trained models for image classification tasks.

---

## Business Impact

- Enables automatic recognition of anime characters in images.  
- Can serve as the foundation for apps, fan tools, or anime-related content categorization.  
- Demonstrates the application of **CNNs, EfficientNet, and Vision Transformers** in a real-world image classification problem.  
- Serves as a case study in **transfer learning** for imbalanced datasets.  

---
