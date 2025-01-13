# Welding Defect Detection using YOLOv11

## Project Overview
This project focuses on detecting welding defects such as cracks, holes, and imperfections in welding seams using YOLOv11. The goal is to automate the quality control process in manufacturing by accurately identifying defects in welding images.

## Problem Statement
The primary objective is to detect welding defects from images to improve the manufacturing process and prevent faulty welding jobs from being used in production.

## Models Used
- **YOLOv11**: Chosen for its speed and real-time object detection capabilities, YOLOv11 is highly efficient in detecting and classifying defects in welding images.

## Dataset
- **Number of Images**: 4314 images
- **Classes**: Bad Welding (defective), Good Welding (non-defective)
- **Source**: from roboflow

## Implementation Details
- **Model Architecture**: YOLOv11 architecture is used for object detection tasks.
- **Training Parameters**:
  - Batch Size: 16
  - Learning Rate: 0.0025
  - Epochs: 50
  - Image Size: 640x640
- **Evaluation Metrics**: mAP (mean Average Precision), Precision, Recall.
  


