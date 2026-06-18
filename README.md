# Real-Time Face Detection

A Python script that performs real-time face detection using OpenCV's Haar Cascade classifier and your webcam feed.

## Features

- Live webcam video capture
- Grayscale conversion for faster processing
- Face detection using Haar Cascade (`haarcascade_frontalface_default.xml`)
- Bounding boxes drawn around detected faces in real time
- Press `A` to exit the live feed

## Requirements

- Python 3.x
- OpenCV (`opencv-python`)

Install dependencies:
```bash
pip install opencv-python
```

## Usage

```bash
git clone https://github.com/AhadAhmad0/Real_Time_Face_Detection.git
cd Real_Time_Face_Detection
python Face_detection.py
```

Make sure `haarcascade_frontalface_default.xml` is in the same directory as the script.

## How It Works

The webcam feed is converted to grayscale, then passed to OpenCV's pretrained Haar Cascade classifier, which scans for face-like patterns and returns bounding box coordinates for each detected face.

## Author

**Ahad Ahmad** — [@AhadAhmad0](https://github.com/AhadAhmad0)
