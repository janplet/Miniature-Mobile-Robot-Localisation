# Constraint-Driven Neural Network Architecture Adaptation for Image Localisation

This repository contains the source files accompanying the paper:

**Constraint-Driven Neural Network Architecture Adaptation for Image Localisation on a Miniature Mobile Robot**
DOI: 10.1109/JSEN.2026.3674225
---

## Dataset

The grayscale image dataset used in this project is available on **IEEE DataPort**.
DOI: 10.21227/t9e0-we58
---

## Model and Deployment

- The [`tflite-model/`](./tflite-model/) directory contains the **Edge Impulse C++ library**, which enables running the model on an **RP2040 microcontroller** using the **Pico SDK**.
  
- The file [`434_88.eim`](./434_88.eim) is the **best-performing Edge Impulse model**, trained on images with a resolution of **88 × 88 pixels**.

- You can run this model using the **Edge Impulse Linux CLI tools**.

---

## Demonstration

The included video demonstrates real-time localisation of robots and rocks using an RP2040 microcontroller:

- 🟢 **Green markers** indicate inferred positions of robots  
- 🔴 **Red markers** indicate inferred positions of rocks  

---
