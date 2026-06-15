# Pedestrian Detection using YOLOv5, YOLOv8, and YOLOv10-Lite

## Project Overview

This project was completed as part of my internship at NIT Warangal and focuses on pedestrian detection using state-of-the-art YOLO object detection models.

The objective of this project is to detect pedestrians in images and videos and compare the performance of different YOLO architectures on benchmark pedestrian datasets. The project includes model training, validation, performance evaluation, and video-based inference.

---

## Objectives

- Detect pedestrians accurately in real-world scenarios.
- Train and evaluate multiple YOLO models.
- Compare model performance across different datasets.
- Analyze detection accuracy using standard evaluation metrics.
- Perform pedestrian detection on video data.

---

## Datasets Used

### PennFudanPed Dataset
The PennFudanPed dataset contains images of pedestrians captured in urban street environments and is widely used for pedestrian detection research.

### WiderPerson Dataset
The WiderPerson dataset is a large-scale pedestrian detection dataset containing diverse pedestrian instances under various environmental conditions and crowd densities.

---

## Models Implemented

- YOLOv5
- YOLOv8
- YOLOv10-Lite

### Model-Dataset Configuration

| Model | Dataset |
|---------|---------|
| YOLOv5 | PennFudanPed |
| YOLOv5 | WiderPerson |
| YOLOv8 | WiderPerson |
| YOLOv10-Lite | WiderPerson |

---

## Technologies Used

- Python
- Jupyter Notebook
- PyTorch
- OpenCV
- Ultralytics YOLO
- NumPy
- Matplotlib

---

## Project Workflow

1. Dataset collection and preparation
2. Data preprocessing
3. Model training
4. Model validation
5. Performance evaluation
6. Video-based pedestrian detection
7. Comparative analysis of YOLO models

---

## Evaluation Metrics

The models were evaluated using:

- Precision
- Recall
- mAP@50
- mAP@50-95

---

## Results

### Performance Comparison

| Model | Dataset | Precision | Recall | mAP@50 |
|---------|---------|---------|---------|---------|
| YOLOv5 | PennFudanPed | 52.2 | 66.4 | 53.9 |
| YOLOv8 | PennFudanPed | 98.2 | 98.0 | --   |
|YOLOv10-lite| PennFudanPed| 86.0| 96.5| 86.5|
| YOLOv5 | WiderPerson | 77.0 | 57.8 | 68.3 |
| YOLOv8 | WiderPerson | 76.1 | 52.8 | 63.6 |
| YOLOv10-Lite | WiderPerson | 70.8 | 51.7 | 61.3 |


## Sample Detection Results

The models successfully detected pedestrians in various scenes, including:

- Single pedestrian scenarios
- Multiple pedestrian scenarios
- Crowded environments
- Outdoor urban scenes

Sample output images are available in the `results` folder.

---

## Video Demonstration

A demonstration video showing pedestrian detection on real-world video data is available in the `demo` folder.

The video illustrates:

- Pedestrian localization
- Bounding box generation
- Detection confidence visualization
- Real-time inference capability

---

## Repository Structure

```
Pedestrian-Detection-Using-YOLO
│
├── notebooks/
│   ├── YOLOv5_PennFudanPed.ipynb
│   ├── YOLOv5_WiderPerson.ipynb
│   ├── YOLOv8_WiderPerson.ipynb
│   └── YOLOv10Lite_WiderPerson.ipynb
│
├── results/
│
├── demo/
│
├── requirements.txt
│
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Pedestrian-Detection-Using-YOLO.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Open Jupyter Notebook:

```bash
jupyter notebook
```

Run the required notebook for training, evaluation, or inference.

---

## Future Improvements

- Real-time webcam pedestrian detection
- Model optimization for edge devices
- Multi-object tracking integration
- Deployment as a web application
- Performance comparison with additional object detection models

---

## Internship Project

This project was developed during my internship to gain practical experience in computer vision, deep learning, object detection, and model evaluation using modern YOLO architectures.

---

## Author

Vavilapalli.Hemalatha

LinkedIn: www.linkedin.com/in/hemalatha-vavilapalli-a209542bb

GitHub: github.com/hemalatha208
