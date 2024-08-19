# Vehicle Reidentification in Multi-Camera Setup

## Project Overview
This project benchmarks vehicle reidentification within a multi-camera tracking system. It leverages transfer learning, utilizing YOLOv8 for real-time object detection and ResNet-50 for feature extraction. The aim is to evaluate the system's performance in accurately reidentifying vehicles across multiple cameras in real-world traffic surveillance scenarios.

## Objectives
- Evaluate vehicle reidentification techniques in challenging conditions (low-light, image compression, object occlusions)
- Provide a benchmark framework for assessing reidentification capabilities
- Test the applicability of YOLOv8 and ResNet-50 in multi-camera vehicle tracking

## Dataset
The dataset was acquired from the AI City Challenge, providing real-world traffic surveillance data across multiple cameras.

## Methodology
1. **Object Detection**: YOLOv8 for tracking vehicles across multiple cameras
2. **Feature Extraction**: ResNet-50 to extract unique features for vehicle identification
3. **Reidentification**: Matching vehicle features across different camera feeds

## Technologies Used
- YOLOv8
- ResNet-50
- Python
- OpenCv



## Publication
This work was presented at IEEE HCCS 2023 at Cardiff University.

**Paper Title**: "Benchmarking Reidentification in Multi-Camera Tracking Systems with YOLOv8 and ResNet-50"

**Conference**: 2023 International Conference on Human-Centered Cognitive Systems (HCCS)

**DOI**: https://doi.org/10.1109/hccs59561.2023.10452624

**Citation**: 
Pal, S. and Dagiuklas, T. (2023). Benchmarking Reidentification in Multi-Camera Tracking Systems with YOLOv8 and ResNet-50. 2023 International Conference on Human-Centered Cognitive Systems (HCCS). Cardiff, UK 16 - 17 Dec 2023 IEEE.



## Contributors
- Shaurya Pal
- Tasos Dagiuklas
