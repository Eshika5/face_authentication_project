# face_authentication_project
Face Recognition-Based Attendance System (Flask Web App)


This project is a Flask-powered web application designed to manage attendance using facial recognition. It allows users to mark attendance by scanning their face through a webcam, view daily attendance records, and register new users.


---

## Key Features
**Face Recognition for Attendance:**
Users can mark their attendance by simply scanning their face using the webcam.

**Automated Attendance Logs:**
Daily attendance is recorded and saved automatically in CSV format.

**User Registration with Face Capture:**
Add new users by capturing their facial data via webcam.

**KNN Model Training:**
The app trains a K-Nearest Neighbors (KNN) model automatically using captured face images.

**Intuitive Web Interface:**
A user-friendly interface to manage attendance, view records, and register users.

## 📁 Project Directory Overview

- **app.py**: Main Flask application.
- `**templates/**: Contains HTML files for rendering web pages.
  - `home.html`
  - `attendance.html`
- **static/faces/**: Stores user face images for training and recognition.
- **static/face_recognition_model.pkl**: Pre-trained KNN model for face recognition.
- **Attendance/**: Stores daily attendance logs in CSV format.
  
## ⚙️ Setup Instructions
**1. Clone the  Repository**
   
```bash
git clone https://github.com/your-username/attendance-using-face-recognition.git
cd attendance-using-face-recognition
```

**2. Install Required Packages**

Make sure you have **Python 3.x** installed, then install the dependencies:

```bash

```
pip install -r requirements.txt
**3.Launch the Application**
```bash

python app.py
```
**4. Access the Web Interface**
Open your browser and navigate to:

cpp

http://127.0.0.1:5000
``
## 🎮 How to Use
```
```
1. **Take Attendance**
Click on the "Take Attendance" option.

Allow webcam access and scan your face.

If recognized, your attendance is recorded.

2. **View Attendance Logs**
Go to the "Show Attendance" section.

View records saved for the current day.

3. **Register a New User**
Enter your Name and ID under "Add New User."

Capture face images using your webcam.

The system will retrain the recognition model automatically.

 ## Requirements
Make sure the following are installed:

Python 3.x

Flask

OpenCV

scikit-learn

joblib

pandas

A working webcam


