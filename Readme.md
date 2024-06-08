# Face Recognition System

# Description

This project is a real-time face recognition system that captures video from a webcam, processes the frames to detect faces, and compares them against a known set of faces loaded from a CSV file. The system accurately identifies known individuals and displays their names on the video feed in real-time.

# Tech Stack

## Programming Language: Python

## Libraries and Frameworks:

### OpenCV: Real-time computer vision tasks such as capturing video from the webcam, detecting faces, and drawing rectangles around them.

### dlib: Efficient face detection capabilities, providing robustness in detecting faces under various conditions.

### NumPy: Numerical computations and array manipulations, facilitating data processing tasks in face recognition.

### face_recognition: Face detection, encoding, and comparison, utilizing pre-trained deep learning models for accurate face recognition.

### scikit-learn: Machine learning models such as classification and regression trees, enhancing face recognition accuracy through advanced algorithms.

# Key Features

Load and process images from a dataset to generate face encodings.
Implement live video capture using OpenCV to detect and recognize faces in real-time.
Use dlib for robust face detection to ensure accurate identification under various lighting and pose conditions.
Employ NumPy for efficient numerical computations, enhancing the performance of face recognition algorithms.
Leverage machine learning techniques such as classification and regression trees from scikit-learn to improve face recognition accuracy.

# Prepare the CSV file:

Create a CSV file named data.csv in the following format:
csv
Copy code
Name,ImagePath
John Doe,johndoe.jpg
Jane Smith,janesmith.jpg
Place the images in a folder named Data in the project directory.


# Project Workflow

## Data Preparation: Load images and their corresponding labels from a CSV file.

## Face Encoding: Encode faces using the face_recognition library, which utilizes deep learning models.

## Real-Time Video Processing: Capture video frames from the webcam using OpenCV for face detection and recognition.

## Advanced Face Detection: Utilize dlib for robust face detection to handle variations in lighting and pose.

## Numerical Computations: Employ NumPy for efficient numerical operations during face recognition tasks.

## Machine Learning Integration: Incorporate machine learning techniques such as classification and regression trees from scikit-learn to enhance face recognition accuracy.