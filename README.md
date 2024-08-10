# yolov8 and supervison for traffic management

## Overview

This project utilizes the YOLO (You Only Look Once) object detection model and the Supervision library for vehicle detection and tracking in videos. YOLO is a state-of-the-art object detection system that provides real-time object detection by dividing the input image into a grid and predicting bounding boxes and class probabilities for each grid cell. Supervision is a Python library for video processing, providing tools for object tracking, zone detection, and annotation.

## Features

- Detection and tracking of vehicles in videos.
- Utilizes YOLOv8 for object detection.
- Implements tracking of detected objects using the Supervision library.
- Annotates video frames with bounding boxes and object IDs.

## Prerequisites

- Python 3.x installed on your machine.
- GPU support for faster processing (recommended).
- NVIDIA GPU with CUDA support for YOLO acceleration.
- Installation of required Python packages specified in the `requirements.txt` file.

## Installation

1. Clone this repository to your local machine:
   ```
   git clone https://github.com/your-username/vehicle-detection.git
   ```

2. Install the required Python packages:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Ensure you have access to a GPU. You can use the `!nvidia-smi` command to check GPU availability.
   
2. Download the pre-trained YOLOv8 model:
   ```
   !gdown 'pre-trained-model-url'
   ```

3. Load the pre-trained YOLOv8 model and set up the Supervision library.

4. Run the provided scripts to detect and track vehicles in videos:
   ```
   python vehicle_detection_tracking.py
   ```

## Configuration

- Adjust the video input path and output path in the script according to your requirements.
- Customize YOLO model settings or Supervision parameters as needed for specific use cases.

## Results
https://drive.google.com/drive/folders/19ZZGfuVCEUZNebutpaXCDRVnJKhD1L9V

check above link for results.

## Credits

This project utilizes the YOLOv8 model from Ultralytics and the Supervision library for video processing tasks.

https://github.com/roboflow/supervision

https://github.com/ultralytics/ultralytics
