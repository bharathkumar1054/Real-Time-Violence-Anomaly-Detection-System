# Real-Time Violence and Anomaly Detection System

## Introduction

Security and surveillance have become increasingly important in modern society. Traditional surveillance systems require constant monitoring by humans, which is time-consuming and prone to human error. To address this challenge, intelligent surveillance systems can be developed using artificial intelligence and computer vision.

The **Real-Time Violence and Anomaly Detection System** is designed to automatically monitor video streams and detect violent or abnormal activities. By analyzing video frames using machine learning and computer vision techniques, the system can identify suspicious behavior and help improve security monitoring.

This project demonstrates how artificial intelligence can assist in building smarter and more efficient surveillance systems.

---

## Problem Statement

Monitoring surveillance cameras manually is difficult, especially in crowded areas such as public places, campuses, shopping malls, and transportation hubs. Human operators may miss important events due to fatigue or the large number of cameras being monitored.

The goal of this project is to develop an automated system that can:

* Analyze video footage in real time
* Detect violent or unusual activities
* Assist security personnel by identifying suspicious events automatically

---

## Objectives

The main objectives of this project are:

* To build a system that can detect violent activities from surveillance videos.
* To analyze video frames using computer vision techniques.
* To apply machine learning or deep learning models for activity recognition.
* To create an automated monitoring system that reduces manual surveillance effort.

---

## System Overview

The system processes video input and analyzes each frame to detect abnormal or violent behavior. If suspicious activity is detected, the system can generate alerts or mark the detected frames.

This approach helps improve response time in emergency situations and supports smarter surveillance systems.

---

## Technologies Used

The project is developed using the following technologies:

* **Python** – Main programming language used for development
* **OpenCV** – Used for video processing and computer vision tasks
* **NumPy** – Used for numerical operations and data handling
* **Machine Learning / Deep Learning** – Used for activity detection and classification

---

## System Architecture

The working process of the system can be described in the following steps:

1. **Video Input**

   * The system receives video input from a camera or video file.

2. **Frame Extraction**

   * The video is divided into individual frames using OpenCV.

3. **Preprocessing**

   * Frames are resized and processed to prepare them for analysis.

4. **Feature Extraction**

   * Important features related to movement and behavior are extracted.

5. **Violence / Anomaly Detection**

   * A machine learning model analyzes the features and classifies the activity as normal or abnormal.

6. **Output**

   * The system displays the results and highlights suspicious activity.

---

## Project Structure

Real-Time-Violence-Anomaly-Detection-System
│
├── dataset
│   Contains video data used for training or testing
│
├── models
│   Stores trained machine learning or deep learning models
│
├── src
│   Source code files for processing and detection
│
├── app.py
│   Main program used to run the project
│
├── requirements.txt
│   List of required Python libraries
│
└── README.md
Project documentation

---

## Installation Guide

### 1. Clone the Repository

git clone https://github.com/bharathkumar1054/Real-Time-Violence-Anomaly-Detection-System.git

### 2. Navigate to the Project Folder

cd Real-Time-Violence-Anomaly-Detection-System

### 3. Install Required Libraries

pip install -r requirements.txt

---

## Running the Project

Run the main program using the following command:

python app.py

The system will start processing the video and detecting violent or abnormal activities.

---

## Applications

This project can be applied in several real-world scenarios:

* Public safety monitoring
* Smart city surveillance systems
* Campus security systems
* Crime detection and prevention
* Automated CCTV monitoring

---

## Future Improvements

Although the current system demonstrates the concept of automated surveillance, several improvements can be made:

* Improve detection accuracy using advanced deep learning models
* Integrate the system with real-time CCTV networks
* Send automated alerts to security personnel
* Deploy the system on cloud platforms for large-scale monitoring
* Add a dashboard for monitoring multiple cameras

---

## Conclusion

The **Real-Time Violence and Anomaly Detection System** demonstrates how artificial intelligence and computer vision can be used to enhance surveillance systems. By automatically detecting suspicious activities in video streams, the system reduces the need for continuous manual monitoring and helps improve security response time.

This project highlights the potential of AI-based solutions in building smarter and more efficient security systems.

---

## Author

**Bharath Kumar Golla**

GitHub Profile:
https://github.com/bharathkumar1054
