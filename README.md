
# Object Detection Project 

## Project Overview
This project focuses on object detection using the YOLOv5 architecture. Specifically, we aim to build and evaluate the YOLOv5-m and YOLOv5-s models, and develop our object detection algorithm. The performance of all approaches will be compared.

Currently, only the YOLOv5-m implementation has been completed. The work on YOLOv5-s and our object detection algorithm is planned and will be updated in this README once completed.

## Goals
- Implement object detection using the YOLOv5-m and YOLOv5-s models.
- Train and evaluate both models on a subset of COCO data.
- Develop and train our object detection algorithm.
- Compare the results of YOLOv5-m, YOLOv5-s, and our algorithm using standard evaluation metrics.

## Dataset
We utilize 100 images from the COCO dataset for training and testing. The COCO dataset is a popular benchmark for object detection tasks due to its diverse and annotated images.

## Methodology
1. **YOLOv5-m Implementation**
   - Set up the YOLOv5-m model.
   - Train the model on the selected 100 COCO dataset images.
   - Evaluate its performance using standard metrics (precision, recall, mAP).

2. **YOLOv5-s Implementation** (Planned)
   - Set up the YOLOv5-s model.
   - Train the model on the same data.
   - Evaluate and compare its results with YOLOv5-m.

3. **Our Object Detection Algorithm** (Planned)
   - Develop our object detection algorithm.
   - Train and optimize the algorithm using the same dataset.
   - Evaluate and compare its results with the YOLOv5 models.

## Results
Currently, only the results of YOLOv5-m are available. The evaluation of YOLOv5-s and our object detection algorithm will be included in future updates.

## Project Structure
```
object-detection-project/
├── data/
│   └── coco_subset/          # 100 COCO images
├── models/
│   └── yolov5_m/            # YOLOv5-m implementation
│   └── yolov5_s/            # YOLOv5-s implementation (Planned)
├── our_algorithm/           # Our object detection algorithm (Planned)
├── results/                 # Evaluation results
├── run_yolov5_m.py          # Script for YOLOv5-m
├── run_yolov5_s.py          # Script for YOLOv5-s (Planned)
├── run_our_algorithm.py     # Script for our algorithm (Planned)
├── requirements.txt         # Dependencies
└── README.md
```



## Contributors
- **MSAHLI IHEB AND HELAOUI AMINE** (Project Lead)

