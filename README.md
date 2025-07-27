# Vehicle Speed Estimation using YOLOv8 and OpenCV

This project implements a vision-based traffic monitoring system capable of detecting, tracking, and estimating the speed of vehicles in video footage. The solution uses the YOLOv8 object detection model and OpenCV to process input video and compute vehicle speed based on a known real-world distance.

## Key Features

- **Object Detection**: Detects cars using the YOLOv8 deep learning model.
- **Multi-Object Tracking**: Maintains consistent IDs for vehicles using ByteTrack.
- **Speed Estimation**: Computes vehicle speed (in km/h) using frame-based timing and known distance calibration.
- **Visual Output**: Generates annotated video with bounding boxes, speed labels, and vehicle counts.
- **Customizable Setup**: Adjustable parameters for detection zones and physical distance estimation.

## System Requirements

- Python
- Ultralytics YOLOv8
- OpenCV
- NumPy