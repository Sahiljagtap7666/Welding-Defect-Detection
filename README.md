# Welding Defect Detection and Trash Object Segmentation Projects

## Overview
This repository contains four deep learning projects focused on object detection and segmentation using cutting-edge models: YOLOv11 and Detectron2 Faster R-CNN. Each project targets a specific task: welding defect detection and trash object segmentation, with a comparative analysis of the models' performance.

---

## Projects and Results

### 1. Welding Defect Detection using YOLOv11
- **Task**: Detect and classify welding defects in images.
- **Performance Metrics**:
  - **mAP50-95**: 35.8%
  - **mAP50**: 60.3%
  - **Precision**: 62.2%
  - **Recall**: 63.2%
- **Model**: YOLOv11, known for its high accuracy and efficiency in real-time object detection.

---

### 2. Welding Defect Detection using Detectron2 Faster R-CNN
- **Task**: Detect and classify welding defects in images using Detectron2's Faster R-CNN.
- **Performance Metrics**:
  - **mAP50-95**: 30.145%
  - **mAP50**: 55.16%
- **Model**: Detectron2’s Faster R-CNN, optimized for precise region-based object detection.

---

### Comparison of Welding Defect Detection Models
| Metric          | YOLOv11          | Detectron2 Faster R-CNN |
|------------------|------------------|--------------------------|
| **mAP50-95**    | **35.8%**        | 30.145%                 |
| **mAP50**       | **60.3%**        | 55.16%                  |
| **Precision**    | **62.2%**        | -                       |
| **Recall**       | **63.2%**        | -                       |

**Key Insights**:
- YOLOv11 outperforms Detectron2 Faster R-CNN in both mAP50 and mAP50-95 for welding defect detection.
- YOLOv11 is more effective for tasks requiring higher accuracy and real-time application.

---

### 3. Trash Object Segmentation using YOLOv11
- **Task**: Segment trash objects in images.
- **Performance Metrics**:
  - **mAP50**: 27%
  - **mAP50-95**: 21.8%
  - **Box Precision**: 52%
  - **Box Recall**: 26.8%
  - **Mask Precision**: 52.2%
  - **Mask Recall**: 26.9%
- **Model**: YOLOv11, extended for instance segmentation tasks.

---

### 4. Trash Object Segmentation using Detectron2 Faster R-CNN
- **Task**: Segment trash objects in images using Detectron2's implementation of Faster R-CNN.
- **Performance Metrics**:
  - **mAP50**: 12.912%
  - **mAP50-95**: 9.62%
- **Model**: Detectron2’s Faster R-CNN, focused on precise instance segmentation.

---

### Comparison of Trash Object Segmentation Models
| Metric               | YOLOv11         | Detectron2 Faster R-CNN |
|-----------------------|-----------------|--------------------------|
| **mAP50**            | **27%**         | 12.912%                 |
| **mAP50-95**         | **21.8%**       | 9.62%                   |
| **Box Precision**     | **52%**         | -                       |
| **Box Recall**        | **26.8%**       | -                       |
| **Mask Precision**    | **52.2%**       | -                       |
| **Mask Recall**       | **26.9%**       | -                       |

---

## Conclusion
- **Welding Defect Detection**: YOLOv11 surpasses Detectron2 Faster R-CNN in precision, recall, and mAP metrics, proving to be the superior choice for this task.
- **Trash Object Segmentation**: YOLOv11 achieves significantly better results compared to Detectron2 Faster R-CNN, especially in mAP and precision.

---

## Repository Structure
