# CamVid Urban Scene Segmentation

A deep learning project for **semantic segmentation of road scenes** using the CamVid dataset. The goal is to classify every pixel in an image into meaningful urban-driving categories such as road, building, vehicle, pedestrian, sign, sky, and vegetation.

This repository is part of my computer vision portfolio and demonstrates an end-to-end segmentation workflow: data preparation, augmentation, model training, evaluation, and visual inspection of predictions.

---

## Why this project matters

Semantic segmentation is a core task in modern computer vision systems used in autonomous driving, robotics, smart infrastructure, and industrial inspection. Unlike image classification, segmentation requires dense pixel-level understanding, which makes it a strong showcase of applied deep learning.

---

## Project highlights

- Built a pixel-level segmentation pipeline for urban scene understanding.
- Worked with the CamVid dataset for road-scene semantic segmentation.
- Implemented preprocessing and augmentation workflows for image-mask pairs.
- Trained deep learning models for multi-class segmentation.
- Evaluated qualitative prediction masks against ground-truth annotations.
- Practiced production-oriented ML workflow habits: clean structure, reproducibility, and clear experiment tracking.

---

## Technical stack

| Area | Tools / Concepts |
|---|---|
| Language | Python |
| Deep Learning | PyTorch |
| Computer Vision | Semantic segmentation, pixel-level classification |
| Data Processing | NumPy, Pandas, image preprocessing |
| Experimentation | Training loops, validation, loss tracking |
| Deployment-readiness | Reproducible project structure, documented workflow |

---

## Typical workflow

```bash
# 1. Clone the repository
git clone https://github.com/harshjoshi23/CamVid-obj-segmentation.git
cd CamVid-obj-segmentation

# 2. Create an environment
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run training / notebooks depending on the project structure
```

> Note: exact commands may vary depending on the current notebook/script layout. The repository is intended as a project showcase and learning-oriented segmentation implementation.

---

## What I learned

This project strengthened my understanding of:

- Image-mask dataset handling
- Pixel-wise loss functions
- Segmentation model training
- Visual debugging of model predictions
- Computer vision evaluation workflows
- The difference between classification, detection, and segmentation tasks

---

## Portfolio context

This project connects directly with my broader AI/ML work in computer vision and segmentation. It also supports my later work on industrial CT scan segmentation, where similar concepts are applied to inspection and quality-control problems.

---

## About me

I am **Harshvardhan Joshi**, an AI/ML Engineer focused on machine learning systems, LLM workflows, backend automation, and production-oriented AI engineering.

- GitHub: [harshjoshi23](https://github.com/harshjoshi23)
- LinkedIn: [harshvardhanjoshi23](https://www.linkedin.com/in/harshvardhanjoshi23)
