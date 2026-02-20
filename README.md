# AttenRetina
Object detection algorithm for autonomous driving: Design and real-time performance analysis of AttenRetina model

###Overview

Accurate object detection is a key requirement for autonomous driving systems to safely identify pedestrians, cyclists, vehicles, and traffic signs. However, existing object detection models often struggle with complex backgrounds, occlusions, scale variations, and small objects in real-world driving environments.

This repository contains an implementation and experimental study of the AttenRetina object detection model, which enhances the RetinaNet framework using Feature Pyramid Networks (FPN) and attention mechanisms to improve detection performance.

###Method

AttenRetina combines:

Multi-scale feature fusion (FPN) for improved object detection at different scales

Attention-based feature enhancement to emphasize important regions and suppress background noise

###Experiments

The model is evaluated on:

MS COCO 2017

KITTI 2D Object Detection Dataset

Performance is measured using Precision, Recall, and mean Average Precision (mAP).
AttenRetina achieves strong improvements over baseline models, including an mAP of 0.86 on the KITTI dataset, demonstrating its effectiveness for autonomous driving scenarios.

###Note

This repository is intended for academic experimentation and internal evaluation.
