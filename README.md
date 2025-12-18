# YOLOv7-GUI-Object-Detection
This project is a desktop-based Object Detection application built using YOLOv7 and PyTorch, 
with a modern GUI implemented using CustomTkinter.

The application allows users to select an image or video file and perform real-time object detection, 
displaying bounding boxes, class labels, and confidence scores. 
The processed output is automatically saved for later use.

## Features

- YOLOv7 object detection using PyTorch
- Supports image and video files
- Real-time detection with bounding boxes and confidence scores
- Transparent bounding boxes with class-specific colors
- Multithreaded processing to keep the GUI responsive
- Start / Stop detection control
- Automatic output saving (image or video)
- Clean and modern GUI using CustomTkinter
- Ready for EXE packaging (PyInstaller compatible)

## Application Interface
<img width="1917" height="1031" alt="GUI" src="https://github.com/user-attachments/assets/d1bd2cde-77f2-4960-b795-59ea0e90d98d" />

## Technologies & Libraries

- Python 3.10+
- PyTorch
- YOLOv7
- OpenCV
- CustomTkinter
- PIL (Pillow)
- NumPy
- Threading
  
## How It Works

1. The YOLOv7 model is loaded using PyTorch with CPU/GPU auto-selection.
2. The user selects an image or video through the GUI.
3. Detection runs in a separate thread to avoid freezing the interface.
4. Each frame is preprocessed and passed to YOLOv7.
5. Non-Maximum Suppression (NMS) is applied to filter overlapping detections.
6. Bounding boxes and labels are drawn on the frame.
7. The processed output is displayed and saved automatically.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/yolov7-gui-object-detection.git

'pip install -r requirements.txt'

## Use Cases

- Computer Vision learning and experimentation
- Object detection demos
- Surveillance and video analysis
- AI portfolio and academic projects

## Author

Developed by **Alhousainy Abdelrahman**  
AI & Computer Vision Engineer  
