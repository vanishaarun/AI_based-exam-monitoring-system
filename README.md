.

📘 AI Based Smart Exam Monitoring System

An intelligent system designed to monitor online/offline examinations using advanced AI technologies such as face recognition, object detection, behavior analysis, and cheating alerts.

🚀 Project Overview

The AI Based Smart Exam Monitoring System automatically monitors students during exams using real-time video analysis. It detects multiple faces, mobile phones, suspicious activities, and identifies if the candidate is absent or engaging in unethical behavior. The system helps improve exam integrity and reduces manual invigilation effort.

🎯 Features

🎥 Real-time webcam monitoring

👤 Face recognition to verify the registered candidate

👥 Multiple face detection alert

📱 Mobile phone detection

🔄 Head & eye movement tracking

🎧 Earphone / suspicious object detection

⚠ Live cheating alert system

📩 Automatic report generation

🖥️ Simple & user-friendly interface

🧰 Tech Stack

Python

OpenCV – real-time video processing

TensorFlow / Mediapipe – detection models

Flask / Streamlit(optional) – UI

Numpy, imutils – image operations

📁 Project Structure
AI-Smart-Exam-Monitoring/
│
├── main.py
├── face_detection.py
├── mobile_detection.py
├── multiple_face_alert.py
├── report_generator.py
│
├── models/
│   ├── face_model.pb
│   ├── mobile_detection_model.tflite
│
├── assets/
│   ├── logo.png
│   ├── alert_sound.wav
│
├── screenshots/
│   ├── demo1.png
│   ├── demo2.png
│
└── README.md

🔧 How to Run
1. Install Dependencies
pip install -r requirements.txt

2. Run the Main App
python main.py

3. Optional (Run Web Version)
streamlit run app.py

📸 Demo Screens

(Add your screenshots here)

![Demo Screen 1](screenshots/demo1.png)
![Demo Screen 2](screenshots/demo2.png)

📑 Output Report

The system generates a detailed report containing:

Exam start & end time

Cheating attempts

Number of faces detected

Alerts triggered

Images captured during suspicious events

🛡️ Use Cases

Online examinations

Computer-based tests

Colleges / Universities

Remote hiring assessments

Proctoring platforms

🏆 Advantages

✔ Automated monitoring
✔ Accurate detection
✔ Reduces manual invigilation
✔ Works in real-time
✔ Easy to integrate

⚠️ Limitations

❌ Requires stable lighting
❌ Limited accuracy on low-quality cameras
❌ Works best on a single person per frame

🤝 Contributing

Contributions are welcome!
Feel free to create issues or pull requests.

📄 License

This project is licensed under the MIT License.

🙌 Author

Vanisha Arun
AI & Data Science Enthusiast
