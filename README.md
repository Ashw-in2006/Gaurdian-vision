Guardian Vision Project: AI-Powered Real-Time Surveillance System 🚨🔍

Welcome to the Guardian Vision Project, an advanced real-time AI surveillance system designed to enhance safety and security in critical environments. This project utilizes Python, YOLOv5, and database integration to detect weapons, identify abnormal activities, and provide situational awareness through real-time alerts.
--------
Features 🌟

Real-Time Weapon Detection: Detects weapons and suspicious objects in live video feeds using YOLOv5's advanced deep-learning capabilities.

Abnormal Activity Recognition: Tracks and flags unusual objects or behaviors for improved situational awareness.

Real-Time Alerts: Provides immediate sound notifications using the winsound module when critical objects like weapons or mobile phones are detected.

Database Integration: Logs all detections, including object labels and coordinates, for future analysis and decision-making.

Smooth Video Processing: Uses OpenCV for efficient video capture and visualization in real time.

-----
Applications 🏢

The Guardian Vision Project is ideal for monitoring high-risk environments, such as:

Public spaces (airports, malls, etc.)

Offices and corporate buildings

Schools and educational institutions

Critical infrastructure zones

-------
Prerequisites ⚙️

Before getting started, ensure you have the following installed:

Python 3.8+

YOLOv5 (Clone the repository: https://github.com/ultralytics/yolov5)

Required Python libraries:

pip install -r requirements.txt

---

Installation 🚀

1. Clone this repository:

git clone https://github.com/your-username/guardian-vision-project.git  
cd guardian-vision-project


2. Install dependencies:
Install all required libraries listed in requirements.txt.

pip install -r requirements.txt


3. Download YOLOv5 weights:
Download the pre-trained YOLOv5 model weights (e.g., yolov5s.pt) from the YOLOv5 repository.


4. Run the application:
Execute the script to start real-time surveillance.

python main.py




---

Usage 📹

Live Detection: The system processes video feeds from a webcam or any video source in real time.

Sound Alerts: Receive auditory notifications when specific objects like weapons or cell phones are detected.

Database Logging: All detections (labels, bounding boxes, timestamps) are stored in the database for later review.

---

File Structure 📁

guardian-vision-project/  
│  
├── main.py                # Entry point of the application  
├── requirements.txt       # List of dependencies  
├── utils/                 # Utility scripts for data processing and visualization  
├── models/                # YOLOv5 model files  
├── database/              # Database integration scripts  
└── README.md              # Project documentation

---

Technologies Used 💻

Python: Core programming language for the project

YOLOv5: Deep learning model for object detection

OpenCV: Real-time video capture and processing

SQLite/MySQL: For logging and storing detection data

winsound: To generate real-time sound alerts

---

Future Enhancements 🔮

Multi-Camera Support: Monitor multiple feeds simultaneously.

Cloud Integration: Store detection logs and videos in the cloud for better scalability.

Mobile App: Provide real-time notifications on mobile devices.

Advanced Threat Analysis: Incorporate more detailed analysis of detected objects and behaviors.

---
License 📄

This project is licensed under the MIT License. See the LICENSE file for details.

---
Acknowledgments 🙏

Special thanks to the YOLOv5 team for their incredible work on object detection models.

---

Guardian Vision Project: Merging AI and safety for a secure future.
