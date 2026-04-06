# FACEMASK DETECTION USING MACHINE LEARNING AND OPENCV

## 📌 Overview

This project focuses on real-time face mask detection using Machine Learning and OpenCV. The system is designed to identify whether a person is wearing a face mask or not through live video streams or images.

The solution can be integrated with CCTV cameras to monitor compliance with safety measures, making it especially useful during pandemic situations like COVID-19.

---

## 🚀 Features

* Real-time face mask detection
* Works with webcam and CCTV feeds
* High accuracy using deep learning models
* Easy integration and deployment

---

## 🛠️ Tech Stack

* Python
* TensorFlow
* Keras
* OpenCV
* NumPy
* Matplotlib
* SciPy

---

## 📂 Project Structure

```
facemask-detection/
│── dataset/
│── model/
│── detect_mask_video.py
│── train_mask_detector.py
│── README.md
```

---

## ⚙️ Requirements

Install the following dependencies before running the project:

```
tensorflow>=1.15.2
keras==2.3.1
imutils==0.5.3
numpy==1.18.2
opencv-python==4.2.0.*
matplotlib==3.2.1
scipy==1.4.1
```

Install using pip:

```
pip install -r requirements.txt
```

---

## ▶️ How to Run

### 1. Clone the repository

```
git clone <repository-url>
cd facemask-detection
```

### 2. Train the model

```
python train_mask_detector.py
```

### 3. Run detection

```
python detect_mask_video.py
```

---

## 📊 Output

* Detects faces in real-time
* Classifies as:

  * With Mask
  * Without Mask
* Displays results with bounding boxes and labels

---

## 🎯 Use Cases

* Public safety monitoring
* Office and workplace compliance
* Hospitals and healthcare centers
* Public transport systems

---

## 📌 Conclusion

This project demonstrates how machine learning and computer vision can be used to solve real-world problems by enhancing safety and ensuring compliance with health guidelines.

---

## 👤 Author

Developed as part of a learning project to explore machine learning, OpenCV, and real-time detection systems.
