# Facial Emotion Detection System
---

FILENAME: README.txt <br>
AUTHOR: Reg Gonzalez <br>
CONTACT: regmckie@gmail.com <br>
DATE: 4/7/2026

---

### PROJECT DESCRIPTION:

This is a program that utilizes PyTorch, Torchvision, and OpenCV to create a facial emotion detection system. A 50K-instance dataset was obtained on Kaggle that includes samples of seven different emotions: angry, disgust, fear, happy, neutral, sad, and surprised. ML pipelines were designed to include data preprocessing, augmentation, training/validation splitting, and performance tracking. Real-time inference with OpenCV was implemented to detect and classify emotions from live webcam video output (to test this, you'll need to run the `Facial_Emotion_Detector_Local.ipynb` file in Jupyter Notebook). The user can also input their own video to test out the facial detection system by editing the line: `webcam = cv2.VideoCapture(0)` in the `Facial_Emotion_Detector.ipynb` file. Simply replace the `0` with the path to your video file.

---

### CODE AND RESOURCES:

**Python Version:** 3.14 <br>
**Packages:** Torch, Torchvision, OpenCV, PIL, Time <br>
**Dataset:** [Facial Emotion Recognition Dataset](https://www.kaggle.com/datasets/fahadullaha/facial-emotion-recognition-dataset)

---

### FILE DESCRIPTIONS:

**Facial_Emotion_Detector.ipynb:** Code for the facial emotion detection system. Includes a custom CNN for classifying the multi-class image dataset and includes ML pipelines for data preprocessing, augmentation, train/validation splitting, and performance tracking. Has code to implement real-time inference with OpenCV to detect & classify emotions from live webcam video output. Finally, includes optimized training with GPU acceleration, batch processing, and model checkpointing for best-performing epochs. <br><br>
**Facial_Emotion_Detector_Local.ipynb:** Contains much of the same code as `Facial_Emotion_Detector.ipynb`, except it runs the live webcam portion locally. Execute this in a Jupyter notebook. <br><br>
**emotion-detection-dataset:** The zip file of the dataset from Kaggle <br><br>
**processed_data:** Contains the data we used for this program; unzipped from `emotion-detection-dataset`.
