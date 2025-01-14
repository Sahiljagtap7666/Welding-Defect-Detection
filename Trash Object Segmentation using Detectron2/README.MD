# Trash Object Segmentation using Detectron2 Faster R-CNN

## Project Overview
This project focuses on segmenting trash objects in images using Detectron2's Faster R-CNN model. Detectron2 is known for its accuracy in segmentation tasks, making it an ideal choice for this project.

## Problem Statement
The main objective is to segment and classify trash objects in images to support waste management and recycling efforts.

## Models Used
- **Detectron2 Faster R-CNN**: Chosen for its advanced segmentation capabilities, particularly useful in accurately identifying and classifying trash objects.

## Dataset
- **Number of Images**: 3,000 images
- **Classes**: Trash objects like paper, plastic, and metal.
- **Source**: Custom dataset.

## Implementation Details
- **Model Architecture**: Faster R-CNN with FPN for object segmentation.
- **Training Parameters**:
  - Batch Size: 16
  - Learning Rate: 0.02
  - Epochs: 50
  - Image Size: 640x640
- **Evaluation Metrics**: mAP, IoU, Precision, Recall.



