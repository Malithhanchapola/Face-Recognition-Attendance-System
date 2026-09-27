# AttendRx – Smart Face Recognition Attendance System

## Overview

AttendRx is a smart attendance management system that uses **ESP32-CAM, Wi-Fi communication, and face recognition** to automate the process of recording student attendance. The system captures student images through an ESP32-CAM and processes them using a Python-based face recognition system to identify students and record attendance with timestamps.

The project provides a practical combination of **IoT, computer vision, and Python** to reduce the effort required for traditional attendance management.

## Features

* **Automated Attendance Tracking:** Records attendance using face recognition.
* **Face Recognition:** Identifies registered students from captured images.
* **ESP32-CAM Integration:** Uses an ESP32-CAM for image capture.
* **Wireless Communication:** Transfers captured images through Wi-Fi.
* **Real-Time Processing:** Processes images and identifies students during attendance.
* **Attendance Records:** Records recognized students along with timestamps.
* **IoT Integration:** Combines embedded hardware with a Python-based recognition system.
* **Simple Workflow:** Designed to reduce manual attendance work.

## Technologies Used

* **Hardware:** ESP32-CAM
* **Programming:** Python, Arduino/C++
* **Computer Vision:** Face Recognition
* **Communication:** Wi-Fi
* **Data Processing:** Python
* **Development Tools:** Arduino IDE
* **Version Control:** Git & GitHub

## System Requirements

* ESP32-CAM module
* Computer/Laptop
* Wi-Fi network
* Python 3.x
* Arduino IDE
* ESP32 board support for Arduino IDE
* Webcam/camera access through ESP32-CAM

## Installation & Setup

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd <your-repository-folder>
```

### 2. ESP32-CAM Setup

1. Open the `ESP32Cam_Code_AttendRx` folder.
2. Open `AttendRx.ino` using Arduino IDE.
3. Configure the ESP32-CAM board.
4. Add your Wi-Fi network credentials.
5. Connect the ESP32-CAM to your computer.
6. Upload the program to the ESP32-CAM.

### 3. Python Environment

Navigate to the face recognition project:

```bash
cd FaceRecognition_Code_AttendRx
```

Install the required Python packages according to the dependencies used by the project.

### 4. Run the Face Recognition System

Run the Python script:

```bash
python ESP32Cam.py
```

The system will connect to the ESP32-CAM through Wi-Fi, retrieve captured images, process them, and perform face recognition.

## Usage

1. Start the ESP32-CAM.
2. Connect the ESP32-CAM to the configured Wi-Fi network.
3. Run the Python face recognition script.
4. Capture student images using the ESP32-CAM.
5. The Python application processes the received images.
6. Recognized students are identified using face recognition.
7. Attendance is recorded with the corresponding timestamp.

## Project Structure

```text
AttendRx/
│
├── ESP32Cam_Code_AttendRx/
│   └── AttendRx.ino
│
├── FaceRecognition_Code_AttendRx/
│   └── ESP32Cam.py
│
└── README.md
```

## Contributing

Contributions are welcome. To contribute:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Commit your changes.
5. Push the branch to GitHub.
6. Create a Pull Request.

## License

This project should retain the license and attribution of the original repository/code from which it was adapted. Check the original repository's license before redistributing or modifying the project.

## Attribution

This version is adapted and customized for personal learning and portfolio development from the original **AttendRx: Smart Face Recognition-Based Attendance System** project.

Original repository:
https://github.com/onkar69483/AttendRx-Face-Recognition-Attendance-System

Original contributors include **Onkar Mendhapurkar, Praneet Mahendrakar, and Prabhat Shankar**.

## Contact

**Malith Hanchapola**

* GitHub: https://github.com/
* Email: Your Email Address
