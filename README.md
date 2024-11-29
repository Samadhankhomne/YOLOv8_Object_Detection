# YOLOv8_Object_Detection
# YOLOv8 Object Detection

Real-time object detection using YOLOv8 on video streams and images. This project demonstrates how to use the YOLOv8 model to detect objects with bounding boxes, class labels, and confidence scores. It includes dynamic handling of COCO classes and visualization using OpenCV, making it beginner-friendly and customizable.

---

## Features

- **YOLOv8 Implementation**  
  Utilizes the latest YOLOv8 model for real-time object detection.
  
- **Pretrained Weights**  
  Leverages COCO-pretrained weights (`yolov8n.pt`) for detecting 80 common object classes.

- **Dynamic Class Handling**  
  Reads and processes class names dynamically from a user-specified file (e.g., `coco.txt`).

- **Video and Image Processing**  
  Supports both image and video input, including real-time webcam feeds or pre-recorded video files.

- **Object Visualization**  
  Displays detected objects with bounding boxes, class labels, and confidence scores using OpenCV.

- **Customizable Confidence Threshold**  
  Allows users to set detection confidence levels for filtering predictions.

- **Color-Coded Classes**  
  Generates random colors for class visualization for easier distinction of detected objects.

- **Scalable Frame Size**  
  Includes frame resizing functionality to optimize model performance on different hardware.

- **Easy-to-Modify Pipeline**  
  Structured code for adding additional features like saving results or post-processing detections.

- **Real-Time Termination**  
  Includes a termination condition for live feeds using the 'Q' key.

- **Beginner Friendly**  
  Step-by-step comments and structured code to help beginners understand object detection workflows.

---

## Requirements

- Python 3.8+
- [Ultralytics YOLO](https://github.com/ultralytics/ultralytics)
- OpenCV
- Numpy
- A COCO class file (`coco.txt`) with the list of 80 class names.

Install the required Python libraries using the following command:
```bash
pip install ultralytics opencv-python numpy
