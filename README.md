# Computer Vision Course Assignment: Object Detection with VisDrone 2019

## Overview

Welcome to the Object Detection assignment for the Computer Vision course! In this assignment, you will be working on object detection using the VisDrone 2019 dataset. The goal is to build a model that can detect and localize objects in aerial images.

### Getting Started

1. **Join the Kaggle Competition:**
  - Follow the competition link provided to join the Kaggle competition.
  - Familiarize yourself with the competition data and evaluation metric.

2. **Clone this repository to your local machine:**
     ```bash
     git clone https://github.com/mshamrai-teaching/object-detection-visdrone-*your-name*
     ```
3. **Navigate to the project directory:**
      ```bash
       cd object-detection-visdrone-*your-name*
      ```

### Guidelines

* Dataset:
  * The VisDrone 2019 dataset is provided for this competition.
* Model:
  * Build or find a model for object detection.
  * Transfer learning is highly encouraged; you can use pre-trained models or fine-tune them.
* Baseline:
  * The baseline used in this competition is a secret.
  * Your goal is to beat the baseline using your own model architecture and training strategy.
* Evaluation:
  * Models will be evaluated based on mean average precision score. 
  * You will be evaluated based on the leaderboard score.
 
### Hints

* Single-Stage vs. Two-Stage Detectors:
  * Consider experimenting with both single-stage and two-stage detectors.
  * Single-stage detectors (e.g., YOLO, SSD) are known for their simplicity and real-time performance.
  * Two-stage detectors (e.g., Faster R-CNN) often achieve higher accuracy at the cost of increased computational complexity.
* Augmentations:
  * Experiment with data augmentations to enhance model generalization.
  * Consider augmentations like random crop, random rotation, and horizontal flip to increase dataset diversity.

### Submission

To submit your solution commit your files to the `main` branch. 

Ensure your final submission includes:
* Source code (object_detection_visdrone.py or similar).
* A brief report (report.md or similar) explaining your model architecture, training strategy, and any challenges faced.

### Evaluation

Your solution will be evaluated based on the mAP with IoU thresholds ranging from 0.5 to 0.95 on the VisDrone validation set and the quality of the visualization of detection results.

Good luck, and may the best object detection model prevail! If you have any questions, feel free to reach out.
