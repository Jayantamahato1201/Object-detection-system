# Real-Time Object Detection with YOLOv8

This project demonstrates real-time object detection using the YOLOv8 model and your webcam. It uses the [Ultralytics YOLO](https://github.com/ultralytics/ultralytics) library and OpenCV to detect and label objects in live video streams.

## Features
- Real-time object detection using YOLOv8s
- Draws bounding boxes and class labels on detected objects
- Simple Python script, easy to run
- Works on CPU (GPU optional if available)

## Demo
![YOLOv8 Real-Time Object Detection Demo](https://github.com/ultralytics/assets/raw/main/yolov8/yolov8-detect.gif)

## Requirements
- Python 3.8+
- OpenCV
- Ultralytics (YOLOv8)
- torch, torchvision

Install all dependencies with:
```bash
pip install -r requirements.txt
```

## Usage
1. Clone this repository or copy the files to your project directory.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the object detection script:
   ```bash
   python object_detection.py
   ```
4. The webcam window will open. Detected objects will be highlighted with bounding boxes and labels.
5. Press `q` to quit.

## File Structure
```
├── object_detection.py   # Main script for real-time detection
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

## Credits
- [Ultralytics YOLO](https://github.com/ultralytics/ultralytics)
- [OpenCV](https://opencv.org/)

## License
This project is for educational purposes. Refer to the YOLO and OpenCV repositories for their respective licenses. 