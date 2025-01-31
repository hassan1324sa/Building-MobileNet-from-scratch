# Building MobileNet from Scratch 🚀📱

![MobileNet Architecture](assets/mobilenet_arch.png) <!-- Add your own diagram or image -->

This repository contains a **from-scratch implementation of MobileNet** (V1, V2, and V3) using PyTorch. MobileNet is a lightweight deep learning architecture optimized for mobile and embedded vision applications, leveraging depthwise separable convolutions for efficiency.

---

## Table of Contents
- [Key Features](#key-features)
- [Installation](#installation)
- [Quick Start](#quick-start)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [References](#references)

---

## Key Features 🌟
- ✅ **From-Scratch Implementation**: No high-level framework wrappers—pure PyTorch code.
- 📱 **MobileNet Versions**: Supports V1, V2, and V3 architectures.
- ⚡ **Efficient Layers**: Depthwise separable convolutions, inverted residuals (V2/V3), and squeeze-excitation blocks (V3).
- 📊 **Training Scripts**: Train models on custom datasets or benchmarks (e.g., CIFAR-10, ImageNet).
- 🧩 **Pre-trained Weights**: Optional download links for pretrained models.

---

## Installation 🛠️

1. **Clone the repository**:
   ```bash
   git clone https://github.com/hassan1324sa/Building-MobileNet-from-scratch.git
   cd Building-MobileNet-from-scratch

   Install dependencies (Python 3.8+ and PyTorch 1.10+ required):

pip install -r requirements.txt



## Training 🏋️♂️
### Train MobileNetV2 on CIFAR-10:

python train.py \
    --model mobilenet_v2 \
    --dataset cifar10 \
    --epochs 100 \
    --batch_size 64 \
    --lr 0.01 \
    --save_dir checkpoints
