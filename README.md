# 3D Vision Super-Resolution

This repository provides an end-to-end PyTorch framework for **image super-resolution** using classical and deep learning–based approaches. The project focuses on training, evaluating, and comparing convolutional neural networks for single-image super-resolution.

Implemented architectures include **SRCNN**, **VDSR**, and **ResNet-based models**, along with standard super-resolution benchmarks and evaluation metrics.

---

## 🚀 Features

- Train super-resolution neural networks (SRCNN, VDSR, ResNet)
- Built-in support for standard datasets (BSD100, Set5, 91-Images)
- Quantitative evaluation using **PSNR** and **SSIM**
- Custom **Charbonnier Loss** implementation
- Modular data augmentation and preprocessing pipeline
- TensorBoard support for training monitoring
- Baseline comparison utilities
- Jupyter notebook demo with pretrained models

---

## 📂 Project Structure
├── train.py # Training script for all models
├── datasets.py # Custom dataset implementations (BSD100, Set5, 91-Images)
├── losses.py # Custom loss functions (Charbonnier Loss)
├── transformations.py # Data augmentation and preprocessing
├── utils.py # Helper utilities (visualization, seeding, metrics, AverageMeter)
├── compare_baselines.py # Script to compare trained models and baselines
├── demo.ipynb # Demo notebook with pretrained model inference
├── requirements.txt # Required Python dependencies
├── Super_Resolution_Project_Docu.pdf # Detailed project write-up

## 📂 Project Structure

```text
.
├── train.py
├── datasets.py
├── losses.py
├── transformations.py
├── utils.py
├── compare_baselines.py
├── demo.ipynb
├── requirements.txt
└── Super_Resolution_Project_Docu.pdf
