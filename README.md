# Super-Resolution GAN (SRGAN)

## Overview
---
This repository contains an implementation of SRGAN (Super-Resolution Generative Adversarial Network) for enhancing low-resolution images to high-resolution images using deep learning. SRGAN is one of the most popular and effective approaches for image super-resolution tasks, leveraging adversarial learning to generate realistic, high-quality images.
The model is trained using the DIV2K dataset, a high-quality image dataset commonly used for super-resolution tasks
---

## 📂 File Overview
- **`ImageEnhancement.ipynb`**: 
  A Jupyter Notebook that includes the implementation of the SRGAN model, training pipeline, and evaluation metrics. It demonstrates:
  - Preprocessing of low-resolution and high-resolution images.
  - Architecture of the SRGAN (Generator and Discriminator models).
  - Training process using adversarial loss and content loss.
  - Performance evaluation and visualization of results.

---

## 🚀 Features
- **Super-Resolution**: Enhance image resolution by 4× while preserving fine details.
- **GAN-Based Learning**: Uses adversarial training to produce realistic textures.
- **Content Loss**: Incorporates perceptual loss to focus on high-level feature similarity.

---

## 🛠️ Installation & Setup

### Prerequisites
- Python 3.x
- Libraries: Pytorch, NumPy, OpenCV, Matplotlib, etc.

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/AmirrezaGholizadeh/SuperResolutionGAN.git
