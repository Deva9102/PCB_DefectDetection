PCB Defect Detection and Severity Scoring using YOLOv5

This project automates the detection and classification of Printed Circuit Board (PCB) defects using a YOLOv5-based deep learning model. 
It also introduces a **severity scoring system** and a **Tkinter GUI** for real-time inspection and usability.

---

 Overview

Manual PCB inspection is often error-prone and time-consuming.
This system:
- Detects six types of PCB defects with high accuracy.
- Assigns severity scores based on defect types.
- Displays annotated images and total severity in a GUI window.

---

Features

- **YOLOv5-based Object Detection** (custom trained on 100+ PCB images)
- **Defect Types Supported**:  
  - Missing_hole  
  - Mouse_bite  
  - Open_circuit  
  - Short  
  - Spur  
  - Spurious_copper
- **Severity Scoring** for each defect
- **Real-Time GUI** built with Tkinter
- Supports image upload, model inference, bounding box overlay, and captioning

---

Dataset Preparation

Converts XML annotations to YOLO format  
Splits data into training and validation sets  
Organizes files into YOLOv5-compatible structure  
Generates a data.yaml file for training


Dataset: Kaggle - PCB Defect Dataset

Model Base: Ultralytics YOLOv5
