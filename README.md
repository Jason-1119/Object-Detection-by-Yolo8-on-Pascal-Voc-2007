# Object-Detection-by-Yolo8-on-Pascal-Voc-2007
This project implements an end-to-end object detection pipeline using YOLOv8 on the Pascal VOC 2007 dataset.  
The workflow includes dataset conversion (VOC → YOLO format), GPU training on Google Colab, evaluation, and inference visualization.

---

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
├── VOCdevkit2007/ # Original Pascal VOC dataset
├── voc2007_yolo/ # Converted YOLO format dataset
│ ├── images/
│ └── labels/
├── voc.yaml # Dataset configuration file
├── yolov8n.pt # Pretrained weights
├── convert_voc_to_yolo.py
├── trainmodel.ipynb
└── README.md
