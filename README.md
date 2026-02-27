# Object-Detection-by-Yolov8-on-Pascal-Voc-2007
This project implements an end-to-end object detection pipeline using YOLOv8 on the Pascal VOC 2007 dataset.  
The workflow includes dataset conversion (VOC → YOLO format), GPU training on Google Colab, evaluation, and inference visualization.

---
<img width="747" height="558" alt="image" src="https://github.com/user-attachments/assets/f6a7cf6e-617b-4d15-bc15-824397f619d9" />


## 🚀 Project Overview

- Dataset: Pascal VOC 2007
- Model: YOLOv8n
- Framework: Ultralytics YOLOv8
- Training Device: NVIDIA Tesla T4 (Google Colab)
- Epochs: 100
- Image size: 640
- Batch size: 16

---

## 📂 Project Structure
voc.yaml # Dataset configuration file
yolov8n.pt # Pretrained weights
convert_voc_to_yolo.py
trainmodel.ipynb
README.md
