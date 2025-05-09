# Project Title:
Secure Robotic Arm Control Using Face Authentication, Wyze Cam, and Blockchain

![image](https://github.com/user-attachments/assets/84f3bb54-561c-4fe1-938c-bec0d42db828)


# Description:

This project integrates robotics, computer vision, and cybersecurity to create a secure and intelligent robotic control system. The system uses a Wyze Cam v3 for real-time facial authentication, a Raspberry Pi 4 as the central processing hub, and an Arduino-controlled Adeept Robotic Arm for physical interaction. User authentication is verified through facial recognition using OpenCV and face_recognition. Once authorized, commands are sent to the Arduino to control servo motors. All control events are logged securely using blockchain technology, ensuring data integrity and traceability.

# Core Technologies:

    Wyze Cam v3 – Real-time video feed for face recognition

    Raspberry Pi 4 – Runs authentication + command logic

    Arduino UNO + Adeept Robotic Arm Kit – Robotic actuation

    OpenCV + face_recognition – Local facial authentication

    PySerial – Communication between Raspberry Pi and Arduino

    Docker – Hosting RTSP stream from Wyze Cam (wyze-bridge)

    Web3.py + Ethereum (testnet or local) – Secure logging via blockchain

# Features:

    Face-based user authentication (no passwords)

    Real-time video stream from Wyze Cam

    Multi-servo robotic control via serial interface

    Secure logging of movement commands on blockchain

    Headless operation via Raspberry Pi

    Scalable and modular design


