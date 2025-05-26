# Crop-Disease-Detection
This repository provides trained deep learning models for detecting plant diseases using leaf images from the PlantVillage dataset. Models include CNN, EfficientNet, VGG16, and custom architectures.

## 🔍 Project Overview

Plant diseases pose a significant threat to global food security. This project applies deep learning to classify plant health status from leaf images.

We trained and evaluated five models:
- `model_CNN_GPU_` (Custom CNN optimized for GPU)
- `model_DN` (Custom Deep Network)
- `plant_disease_model_EfficientNet1`
- `plant_disease_model_EfficientNet1_final`
- `VGG16` (Transfer learning model)

## 🧠 Models

All trained models are stored in the `models/` directory.

| Model Name | Description |
|------------|-------------|
| `model_CNN_GPU_.keras` | Custom CNN with batch norm and dropout |
| `model_DN.keras` | Deeper custom CNN architecture |
| `plant_disease_model_EfficientNet1.keras` | EfficientNetB0 base model |
| `plant_disease_model_EfficientNet1_final.keras` | Fine-tuned EfficientNet |
| `VGG16_model.keras` | Transfer learning with VGG16 |

## 📁 Directory Structure

```bash
├── models/             # Saved .keras models
├── notebooks/          # Jupyter notebooks for training/evaluation
├── data/               # Placeholder for dataset
├── src/                # Source scripts for training and evaluation
├── requirements.txt    # Dependencies
├── README.md           # Project overview
└── LICENSE             # License info
