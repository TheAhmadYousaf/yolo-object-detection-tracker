# 🎯 Real-Time Object Detection & Tracking
### YOLOv8 + ByteTrack | Google Colab Notebook

## Overview
Upload any image or video from your PC and this notebook will:
- Detect objects using **YOLOv8** (pretrained on 80 COCO classes)
- Track each object with a **unique color-coded ID** using ByteTrack
- Measure **FPS and inference time**
- Run a **confidence threshold experiment** (0.25 / 0.50 / 0.75)
- Export all results as images, charts, and annotated video

---

## Results Preview

### Detection Output
![Detection Result](results/result_detection.png)

### Confidence Threshold Experiment
![Threshold Experiment](results/A3_threshold_experiment.png)

### Tracking with Unique IDs
![Tracking](results/B1_tracking_image.png)

### FPS & Inference Time Chart
![FPS Chart](results/B2_fps_chart.png)

### Video Preview Frames
![Video Preview](results/B2_video_preview.png)

### Performance Summary
![Summary](results/C3_summary.png)

---

## How to Run

1. Open the notebook in Google Colab  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TheAhmadYousaf/yolo-object-detection-tracker/blob/main/Object_Detection_Tracking%20(1).ipynb)

2. Run all cells — libraries install automatically
3. When prompted, **upload your image or video** from your PC
4. Results are saved and downloaded as a ZIP automatically

---

## Project Structure
```
yolo-object-detection-tracker/
│
├── Object_Detection_Tracking.ipynb   ← Main notebook
├── README.md
└── results/                          ← All output images and charts
    ├── result_detection.png
    ├── A3_threshold_experiment.png
    ├── B1_tracking_image.png
    ├── B2_fps_chart.png
    ├── B2_video_preview.png
    ├── C2_threshold_chart.png
    └── C3_summary.png
```

## Tech Stack
| Tool | Purpose |
|------|---------|
| YOLOv8n | Object detection model |
| ByteTrack | Multi-object tracking |
| OpenCV | Video processing |
| Matplotlib | Charts and visualization |
| Google Colab | Runtime environment |

## Parts Covered
| Part | Description |
|------|-------------|
| A | Detection + bounding boxes + confidence threshold experiment |
| B | ByteTrack tracking with unique IDs + FPS analysis |
| C | Performance table across 6 scenarios + summary |
