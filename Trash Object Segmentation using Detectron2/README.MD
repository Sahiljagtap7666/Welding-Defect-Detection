# Trash Object Segmentation using Detectron2 Faster R-CNN

## Project Overview
This project focuses on segmenting trash objects in images using Detectron2's Faster R-CNN model. 
## Problem Statement
The main objective is to segment and classify trash objects in images to support waste management and recycling efforts.

## Models Used
- **Detectron2 Faster R-CNN**: Chosen for its advanced segmentation capabilities, particularly useful in accurately identifying and classifying trash objects.

## Dataset
- **Number of Images**: 3,167 images
- **Train Images**: 3,057 images
- **valid Images**: 110 images
- **Classes**: Trash objects like paper, plastic, and metal.
- **Source**: https://universe.roboflow.com/taco-9911u/taco-trash-annotations-in-context-bumvw/dataset/10#

## Implementation Details
- **Model Architecture**: Faster R-CNN with FPN for object segmentation.
- **Training Parameters**:
  - Batch Size: 8
  - Learning Rate: 0.0025
  - iteration: 560
  - Image Size: 640x640
- **Evaluation Metrics**:
- mAP50:12.912
- mAP50-0.95:9.62



