# Architecture & Ownership Plan

## System Overview

Image → Feature Learning → Normality Modeling → Anomaly Scoring → Heatmap → Decision

The system is designed to simulate real-world industrial anomaly detection, where only normal data is available during training.

---

## Technical Lead (Samy)

Responsible for:
- Model architecture design
- Loss function implementation
- Anomaly scoring logic
- Threshold selection strategy
- Evaluation methodology
- System integration
- Final documentation

---

## Teammate 1 — Data & Experiment Engineer

Responsible for:
- Dataset loading
- Data augmentation
- Experiment tracking
- Training pipeline support

---

## Teammate 2 — Visualization & Deployment Engineer

Responsible for:
- Heatmap visualization
- FastAPI implementation
- Streamlit UI
- Demo preparation