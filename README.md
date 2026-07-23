# Agricultural Pest Dtection Using YoloV5

**AI-Powered Agricultural Pest Detection using YOLOv5**

An end-to-end computer vision solution developed during my AI/ML Internship at the **Tamil Nadu e-Governance Agency (TNeGA)** to automate agricultural pest detection using deep learning.

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-red?logo=pytorch)
![YOLOv5](https://img.shields.io/badge/YOLOv5-ObjectDetection-success)
![OpenCV](https://img.shields.io/badge/OpenCV-ComputerVision-green?logo=opencv)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

# Overview

Agriculture is one of the most important sectors globally, yet crop losses caused by pests continue to affect productivity and food security. Traditional pest monitoring relies on manual inspection, which is time-consuming, labor-intensive, and susceptible to human error.

This project presents an AI-powered pest detection system built using **YOLOv5** to automatically detect agricultural pests from crop images. The solution is designed to support precision agriculture by enabling faster and more accurate pest identification.

This project was developed during my AI/ML Internship at the **Tamil Nadu e-Governance Agency (TNeGA)** as part of an initiative to explore practical applications of computer vision in agriculture.

> **Note**
>
> Due to organizational confidentiality and data privacy agreements, the original dataset, trained model weights, and certain implementation details cannot be publicly shared. This repository focuses on the implementation methodology, project architecture, and machine learning workflow.

---

# Problem Statement

Traditional pest identification presents several challenges:

- Manual inspection is time-consuming.
- Large agricultural fields require significant manpower.
- Delayed pest identification can lead to severe crop damage.
- Human inspection is prone to inconsistencies and errors.

The objective of this project is to automate pest detection using deep learning to improve detection speed, consistency, and scalability.

---

# Features

- Real-time agricultural pest detection
- YOLOv5-based object detection model
- Custom annotated dataset
- Image annotation using CVAT and Roboflow
- GPU-accelerated model training using PyTorch
- Bounding box visualization with confidence scores
- Data preprocessing and augmentation pipeline
- Modular project structure for future enhancements

---

# Project Workflow

```text
Agricultural Images
        │
        ▼
Image Annotation
(CVAT / Roboflow)
        │
        ▼
Data Preprocessing
        │
        ▼
Data Augmentation
        │
        ▼
YOLOv5 Model Training
        │
        ▼
Model Validation
        │
        ▼
Real-Time Inference
        │
        ▼
Pest Detection Results
```

---

# Technology Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Deep Learning | PyTorch, YOLOv5 |
| Computer Vision | OpenCV |
| Annotation | CVAT, Roboflow |
| Data Processing | NumPy, Pandas |
| Visualization | Matplotlib |
| Development Environment | Jupyter Notebook, Visual Studio Code |

---

# Repository Structure

```text
smart-pest-detection-yolov5/

├── assets/
├── configs/
├── data/
├── docs/
├── inference/
├── models/
├── notebooks/
├── preprocessing/
├── training/
├── README.md
├── requirements.txt
└── LICENSE
```

---

# Dataset

The dataset used in this project consists of annotated agricultural pest images collected during my internship.

**Dataset Information**

- Domain: Agriculture
- Image Type: Field images
- Annotation Format: YOLO
- Annotation Tools: CVAT and Roboflow
- Multiple pest classes

The original dataset is not publicly available due to confidentiality agreements.

---

# Installation

Clone the repository:

```bash
git clone https://github.com/sandhiyab17/smart-pest-detection-yolov5.git
```

Navigate to the project directory:

```bash
cd Agricultural-Pest-Detection-YOLOv5
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

# Usage

### Train the model

```bash
python training/train.py
```

### Validate the model

```bash
python training/val.py
```

### Run inference

```bash
python inference/detect.py --source path/to/image.jpg
```

---

# Evaluation

The model performance is evaluated using standard object detection metrics:

- Precision
- Recall
- Mean Average Precision (mAP)
- F1 Score
- Confusion Matrix

---

# Sample Results

After uploading screenshots, include them here.

| Input Image | Detection Output |
|-------------|------------------|
| <img width="340" height="353" alt="image" src="https://github.com/user-attachments/assets/e13cc13a-2e71-4261-ae0f-3e3371e02ddf" /> | <img width="362" height="288" alt="image" src="https://github.com/user-attachments/assets/280c40c2-78ce-4c97-8c51-4cefe11bcc2e" /> |

---

# Challenges

- Collecting and annotating agricultural images
- Handling varying environmental conditions
- Detecting small and overlapping pests
- Improving generalization across different crop types

---

# Future Work

Potential improvements include:

- Migration to newer object detection architectures
- Deployment on edge devices
- Cloud-based inference service
- Mobile application integration
- Continuous model retraining with new datasets

---

# Acknowledgements

I would like to thank:

- Tamil Nadu e-Governance Agency (TNeGA)
- My mentors and the AI/ML team
- Ultralytics for the YOLOv5 framework
- Roboflow
- CVAT
- PyTorch community

---

# License

This project is licensed under the MIT License.

---

# Author

**Sandhiya Balamurugan**

Bioinformatics Graduate | Artificial Intelligence & Machine Learning | Computer Vision

LinkedIn: http://www.linkedin.com/in/sandhiya17b

Email: sandhiyabalamurugann@gmail.com

---

If you found this repository useful, consider giving it a star.
