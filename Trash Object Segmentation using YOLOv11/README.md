### ** Trash Object Segmentation using YOLOv11**


# Trash Object Segmentation using YOLOv11

## Project Overview
This project aims to segment trash objects in real-time using YOLOv11. By identifying and classifying trash items, the project contributes to waste management and environmental conservation efforts.

## Problem Statement
The goal is to automate the trash segmentation process, enabling more efficient waste sorting and recycling.

## Models Used
- **YOLOv11**: Chosen for its real-time capabilities in segmenting and identifying objects in images.

## Dataset
- **Number of Images**: 3,167 images
- **test Images**: 3,057 images
-**Valid Images**: 110 images

- **Classes**: Various trash objects (paper, plastic, metal, etc .)
- **Source**: https://universe.roboflow.com/taco-9911u/taco-trash-annotations-in-context-bumvw

## Implementation Details
- **Model Architecture**: YOLOv11 architecture for object segmentation.
- **Training Parameters**:
  - Batch Size: 16
  - Epochs: 20
  - Image Size: 640x640
- **Evaluation Metrics**:
  - mAP50:27%
  - mAP50-0.95:21.8%
  - Box Precision: 52%
  - Box recall: 26.8%
  - mask Precision: 52.2%
  - mask recall: 26.9%



  






