# Drowsiness Detection System

## Overview

This Python script utilizes computer vision techniques and a pre-trained deep learning model to detect drowsiness in a live video stream. It employs OpenCV for face and eye detection, and TensorFlow/Keras for predicting eye status (open or closed). When the system detects closed eyes for a specific duration, it triggers an alert to indicate potential drowsiness.

### Author

- **Name:** Revanthraja M
- **GitHub:** [Revanthraja GitHub Profile](https://github.com/Revanthraja)

## Prerequisites

- Python 3
- OpenCV (`cv2`)
- NumPy
- TensorFlow
- Keras
- playsound
- Haarcascades for Face and Eye detection (`haarcascade_frontalface_default.xml`, `haarcascade_lefteye_2splits.xml`, `haarcascade_righteye_2splits.xml`)
- Pre-trained drowsiness detection model (`drowiness_new7.h5`)

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/Revanthraja/Drowsiness-Detection.git
Install the required Python librarie
pip install opencv-python numpy tensorflow keras playsound
Place the Haarcascades and the pre-trained model (drowiness_new7.h5) in the data directory.

Run the script:


python drowsiness_detection.py
The live video stream will open, detecting faces and eyes in real-time.

If the eyes remain closed for a specific duration, a drowsiness alert will be triggered.

Press q to exit the program.

Configuration
alarm.mp3: Customize the alarm sound by replacing alarm.mp3 in the data directory.
Contributing
Contributions are welcome! Feel free to open issues or pull requests for any improvements or bug fixes.

License
This project is licensed under the MIT License.

Feel free to modify this template to suit your preferences or add more information about the project as needed.

