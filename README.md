# Face-Recognition-System
# Real-Time Face Recognition System

## Project Overview
This project is a real-time face recognition system built using Python, OpenCV, Face Recognition Library, and Google Colab.

The system allows users to:

- Register known people using their photos
- Store face encodings in a local database
- Capture live webcam images through Google Colab
- Identify registered people in real-time
- Detect unknown persons and generate alerts

---

## Features

 Multiple face registration

Face encoding database storage

Live webcam face recognition

Known vs Unknown person detection

Confidence score display


Automatic summary report

---

## Technologies Used

- Python
- OpenCV
- Face Recognition
- NumPy
- Pillow
- Google Colab
- Pickle

---

## Project Workflow

### Step 1: Register Faces

Upload photos of known people.

The system:
- Detects faces
- Extracts face encodings
- Stores encodings for future recognition

### Step 2: Save Database

All registered face encodings are saved in:

```bash
known_faces.pkl
```

### Step 3: Capture Webcam Frames

Google Colab accesses webcam using JavaScript and captures multiple frames.

### Step 4: Face Recognition

The system:

- Detects faces
- Compares them with stored encodings
- Calculates similarity score
- Identifies the person

### Step 5: Output

Known Person:

```text
YES! Welcome, Person 1
```

Unknown Person:

```text
Random person wants to enter!
```

---

## Installation

Install required libraries:

```bash
pip install ultralytics
pip install face_recognition
pip install opencv-python
pip install Pillow
pip install cmake
pip install dlib
```

---

## Run the Project

Open Google Colab and run:

1. Install dependencies
2. Register known faces
3. Save face database
4. Start webcam recognition

---

## Project Structure

```text
Face-Recognition-System/
│
├── Face_Recognition.ipynb
├── known_faces.pkl
├── README.md
└── screenshots/
```

---

## Future Improvements

- Attendance Management
- Face Mask Detection
- Database Integration (MySQL)
- Employee Login System
- Multi-person Tracking
- Flask Web Application

---

## Author

Priya Rathod

Data Analyst | Python | SQL | Power BI
