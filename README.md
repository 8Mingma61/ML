# 🍎 Apple Leaf Disease Classification with CNN and Grad-CAM

This project focuses on the **classification of apple leaf diseases** using a **custom Convolutional Neural Network (CNN)** and provides **visual explanations with Grad-CAM**.  
The goal is to help in early detection of apple diseases to support **precision agriculture** and improve crop yield.

---

## 🚀 Features
- Custom **CNN model** trained on apple leaf disease dataset.
- Supports classification of **Black Rot, Apple Scab, Cedar Rust, and Healthy leaves**.
- **Grad-CAM visualization** for interpretable AI, showing disease-affected regions.
- Data augmentation for better generalization.
- End-to-end pipeline: **training → evaluation → visualization**.

---

## 📂 Project Structure
apple-disease-classification/
│
├── data/                     # Dataset (not uploaded to GitHub; add link or script to download)
│   ├── train/                 # Training images
│   ├── val/                   # Validation images
│   └── test/                  # Test images
│
├── src/                      # Source code
│   ├── train.py               # Training script
│   ├── evaluate.py            # Model evaluation script
│   ├── gradcam.py             # Grad-CAM visualization
│   ├── dataset.py             # Dataset loading + preprocessing
│   └── model.py               # Custom CNN model definition
│
├── notebooks/                # Jupyter notebooks for experiments
│   └── apple_cnn_experiments.ipynb
│
├── models/                   # Saved models / checkpoints
│   └── custom_cnn.pth
│
├── results/                  # Output results (figures, heatmaps, overlays)
│   ├── accuracy_curve.png
│   ├── loss_curve.png
│   └── gradcam_samples/
│
├── requirements.txt          # List of dependencies
├── README.md                 # Project documentation (overview, usage, etc.)
├── LICENSE                   # License (e.g., MIT)
└── .gitignore                # Files/folders to ignore (datasets, models, etc.)
