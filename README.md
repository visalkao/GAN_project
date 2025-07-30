# GAN Variants on MNIST

This repository contains PyTorch implementations of various Generative Adversarial Networks (GANs) trained on the MNIST dataset, including:

- Vanilla GAN
- Deep Convolutional GAN (DCGAN)
- Conditional GAN (cGAN)
- Wasserstein GAN (WGAN)

Each model is implemented from scratch and follows standard practices from relevant research papers.

---

## 📁 Repository Structure
├── data/ # MNIST data (auto-downloaded)
├── models/ # Generator and Discriminator definitions
├── sample.ipynb # Vanilla GAN training script
├── sample_DCGAN.ipynb # DCGAN training script
├── sample_cGAN.ipynb # Conditional GAN training script
├── sample_WGAN.ipynb # Wasserstein GAN training script
├── README.md # Project documentation
└── requirements.txt # Python dependencies


---

## 🧠 Models Overview

### 1. **Vanilla GAN**
- Basic GAN with fully connected networks.
- Uses binary cross-entropy loss.

### 2. **DCGAN**
- Uses deep convolutional layers.
- Based on the [DCGAN paper (Radford et al., 2015)](https://arxiv.org/abs/1511.06434).

### 3. **Conditional GAN (cGAN)**
- Conditions generation on digit labels.
- Concatenates labels with noise input.

### 4. **Wasserstein GAN (WGAN)**
- Uses Wasserstein loss and weight clipping.
- Better stability and convergence.

---

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/GAN_PROJECT.git
cd GAN_PROJECT
pip install -r requirements.txt
