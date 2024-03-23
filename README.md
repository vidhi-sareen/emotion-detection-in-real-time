
<div align="centered">
  <img src="https://github.com/vidhi-sareen/emotion-detection-in-real-time/blob/main/emotion_detection.png" alt="Emotion Detection" title="Real-Time Emotion Detection" width="600" height="400">
</div>

## Real Time Emotion Detection using Deep Learning

This project implements real-time emotion detection using Convolutional Neural Networks (CNN). The system is capable of distinguishing between 7 categories of emotions: angry, disgust, fear, happy, neutral, sad, and surprise.

## Technologies Used
- CNN (Convolutional Neural Networks)
- OpenCV
- TensorFlow

## How it Works
The system utilizes a CNN architecture trained on a dataset containing labeled facial expressions corresponding to the 7 emotion categories mentioned above. OpenCV is used for capturing real-time video feed from a webcam or other video sources. The captured frames are then processed using the CNN model implemented with TensorFlow to predict the dominant emotion displayed on the face in each frame.

## Usage
1. Ensure you have Python installed on your system.
2. Install the required dependencies: `pip install opencv-python tensorflow`.
3. Clone or download this repository.
4. Run the provided script for real-time emotion detection.

## Future Improvements
- Incorporating more sophisticated deep learning architectures for better accuracy.
- Enhancing the user interface for better interaction and visualization.
- Expanding the dataset to include more diverse facial expressions for improved generalization.
