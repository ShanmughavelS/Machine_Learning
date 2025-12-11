# Machine_Learning
A practical study of Convolutional Neural Networks (CNNs), focusing on how kernel size influences feature learning, generalization, and model behaviour. Includes code, visualizations, and a full tutorial based on the MNIST dataset.
# Project Files

-  [Final_Tutorial PDF](CNN_Kernel_size_comparison.pdf)
-  [Jupyter Notebook](Machine_Learning_11Dec.ipynb)
-  [Figures Folder](Figures/)

# CNN Kernel Size Comparison on MNIST  
A tutorial and experiment demonstrating how convolutional kernel size (3×3, 5×5, 7×7) affects feature extraction, learned filters, and model performance in Convolutional Neural Networks (CNNs).

This repository contains:

- ✔ A fully illustrated tutorial PDF  
- ✔ Jupyter Notebook with complete code  
- ✔ Visualizations of filters and feature maps  
- ✔ A comparative study across kernel sizes  

---

## 📂 Project Overview

This project explores how the **size of convolution kernels** influences:

- Model accuracy  
- Sharpness and interpretability of learned filters  
- Quality of feature maps  
- Generalization on small images  

We train three CNNs that differ only in their first convolutional kernel size:

| Model | Kernel Size | Purpose |
|-------|-------------|---------|
| Model A | 3×3 | Captures fine detail; standard in modern CNNs |
| Model B | 5×5 | Larger receptive field, smoother features |
| Model C | 7×7 | Very broad, oversmoothing on small images |

The experiment is conducted using the **MNIST** dataset.

---

