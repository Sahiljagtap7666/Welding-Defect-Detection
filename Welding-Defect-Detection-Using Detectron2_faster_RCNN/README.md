# Welding Defect Detection using using Detectron2 faster-RCNN

## Project Overview
This project aims to detect welding defects like cracks and holes using Detectron2's Faster R-CNN model. Detectron2 provides high-quality and accurate detection, making it ideal for this task.

## Problem Statement
The goal is to identify welding defects and ensure that only defect-free welds are used in manufacturing, thus reducing production errors.


## Models Used
- **Detectron2 Faster R-CNN**: Used for its accuracy in detction tasks, especially for detecting fine-grained defects.

## Dataset
- **Number of Images**: 4314 images
- **Classes**: Bad Welding (defective), Good Welding (non-defective)
- **Source**: https://universe.roboflow.com/yolo-eh6cy/weld-quality-inspection-rei9l-3rsxl

## Implementation Details
- **Training Parameters**:
  - Batch Size: 16
  - Iterations: 844
  - Learning rate: 0.02
  - Image Size: 640x640
- **Evaluation Metrics**: mAP (mean Average Precision).
- mAP50-95: 30.145%
- mAP50:55.16%



