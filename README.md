# Car Detection with YOLO

This project implements real-time car detection and tracking using the YOLO (You Only Look Once) object detection model. The detection is applied to video frames, and the system is capable of drawing bounding boxes around detected cars.

---

## 🚗 Project Overview

- Uses YOLOv11n pretrained model for detecting cars in video streams.
- Processed video frame by frame from a given input video file.
- Draws bounding boxes around detected cars in each frame.
- counts the number of detected cars.
- Displays the confidence score for each detection.

---

## 🧾 Requirements

Install the following dependencies:

```bash
pip install opencv-python
pip install ultralytics
```
---
## 🧠 Model Details
- Model Used: YOLO (You Only Look Once)
- Model Version: YOLOv11n (from Ultralytics)
- Detected Class: Cars (class_id = 2, COCO dataset)
- Model Source: Pretrained YOLOv11n from Ultralytics model hub
  
---

## ▶️ How to Run
1. Open the Jupyter Notebook file : `Tracking_Car_using_YOLO.ipynb`
2. Run All cells
3. The model will read the input video, detect cars in each frame, and write the result to an output video file named `output_tracking.mp4`
   
The output video will display:

  - Bounding boxes around detected cars
  - Total car count per frame
  - and confidence score for each detection

