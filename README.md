# Facial-Emotion-Recognition-using-OpenCV-and-Deepface
This project uses DeepFace and OpenCV for real-time facial emotion detection. It captures video from the webcam, detects faces, and displays emotion labels on the screen. It's one of the shortest codes for real-time emotion tracking.

## Dependencies

- [deepface](https://github.com/serengil/deepface): A deep learning library with pre-trained models for facial emotion detection, built on TensorFlow.
- [OpenCV](https://opencv.org/): An open-source computer vision library for processing images and videos.

## Usage
### Initial steps:
- Git clone this repository Run: `git clone git@github.com:JagadeeshAjjada/Facial_Emotion_Recognition_using_OpenCV_and_Deepface.git`
- Run: `cd Facial_Emotion_Recognition_using_OpenCV_and_Deepface`
1. Install the required dependencies:
   - You can use `pip install -r requirements.txt`
   - Or you can install dependencies individually:
      - `pip install deepface`
      - `pip install tf_keras`
      - `pip install opencv-python`

2. Download the Haar cascade XML file for face detection:
   - Visit the [OpenCV GitHub repository](https://github.com/opencv/opencv/tree/master/data/haarcascades) and download the `haarcascade_frontalface_default.xml` file.

3. Run the code:
   - Execute the Python script.
   - The webcam will open, and real-time facial emotion detection will start.
   - Emotion labels will be displayed on the frames around detected faces.
