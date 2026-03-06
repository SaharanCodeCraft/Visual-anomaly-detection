# Normexa

##  Overview

This project implements an unsupervised visual anomaly detection system that learns normal visual patterns and flags unseen defects without requiring labeled anomaly data.

Instead of classifying known defect types, the system models what "normal" looks like and identifies deviations from it.

This approach reflects real-world industrial and medical inspection scenarios where defects are rare, unpredictable, and often unlabeled.

---

##  Core Idea

Train only on normal images.

If the model struggles to reconstruct or represent a new image accurately, the deviation is treated as an anomaly.

Image → Feature Learning → Normality Modeling → Anomaly Score → Heatmap → Decision

---

## Key Features (Planned)

- Unsupervised training on normal images
- Image-level anomaly score
- Pixel-level heatmap visualization
- Confidence-based decision threshold
- Modular architecture
- Deployable inference API

---

## Real-World Applications

- Industrial quality inspection
- Medical image pre-screening
- Infrastructure surface monitoring

---

## 🛠 Tech Stack

- Python
- PyTorch
- OpenCV
- FastAPI
- Streamlit

---

## 📌 Project Status

Currently in Phase 1: Dataset understanding and pipeline setup.

Baseline anomaly model implementation coming next.
