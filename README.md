# 🐾 Animal Detection using Faster R-CNN (PyTorch)

This project demonstrates how to train a custom object detection model using **Faster R-CNN with PyTorch** on a custom Animal Detection dataset downloaded from Roboflow.

The project covers the complete pipeline including dataset preparation, annotation cleaning, custom dataset creation, training, loss visualization, saving the trained model, and running inference with bounding box visualization.

---

## 🚀 Features

- Download dataset from Roboflow (YOLOv8 format)
- Clean invalid and empty annotation files
- Custom PyTorch Dataset and DataLoader
- Faster R-CNN with ResNet50 + FPN backbone
- Transfer learning using COCO pretrained weights
- Custom class training
- Loss visualization graph
- Model saving and loading
- Inference with bounding box visualization
- OpenCV visualization support

---

## 🧠 Model Architecture

- Model: Faster R-CNN
- Backbone: ResNet50 + FPN
- Framework: PyTorch
- Pretrained on: COCO dataset
- Custom classes: 4 animal classes + background

