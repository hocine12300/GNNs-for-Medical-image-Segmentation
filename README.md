# GNN-based Medical Image Segmentation (Demo)

This repository provides a **minimal demo** of our method for medical image segmentation using **Graph Neural Networks (GNNs)**.

⚠️ The full implementation (models, training, weights) will be released after paper acceptance.

---

## 📌 Content

- `example.ipynb` → complete demo:
  - graph loading
  - inference
  - mask reconstruction via superpixels
  - visualization + Dice / IoU metrics

---

## 🚀 Quick Start

```bash
git clone https://github.com/hocine12300/GNN_Segmentation.git
cd GNN_Segmentation
pip install torch numpy matplotlib opencv-python
jupyter notebook example.ipynb
