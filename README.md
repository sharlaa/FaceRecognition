# Face Detection using OpenCV

## Description
CV CS UGM
Sharla Nur Raissa (23/516320/PA/22093).
This project implements real-time face detection using OpenCV's Haarcascade Classifier. It detects faces from images and webcam in real-time and draws bounding boxes around them. As a part of the assignment, i added new data of Carlos Moya (from the original dataset), Nabila Yumna (My friend), and my face. I added my friend as one of the two new individual since i thought it will be nice to try it live with them later on in class! I will explain how to run down below.

## How to Run

1. Clone this repository:
    ```bash
    git clone https://github.com/sharlaa/FaceRecognition.git
    cd FaceRecognition
    ```

2. Install required libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Open and run the notebook:
    - `face detection cv.ipynb`

4. Steps inside the notebook:
    - Load face detection model (Haarcascade)
    - Run detection on sample images
    - Perform real-time detection using webcam

## Requirements
- Python 3.8+
- OpenCV
- Numpy
- Matplotlib

(Install all dependencies via `requirements.txt`)

## Example Outputs
- Real-time Face Detection:
  ![Webcam Detection Example](screenshots/detection_sharla_raissa.png)
  ![Webcam Detection Example](screenshots/detection_george.png)

## Repository Link
https://github.com/sharlaa/FaceRecognition


