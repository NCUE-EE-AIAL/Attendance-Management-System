# Project Overview
This project is a Face Recognition Attendance Management System. It allows users to capture images for training a face recognition model, train the model, and recognize faces to log attendance. The attendance data is stored in both a CSV file and a database for future reference.

```mermaid
graph LR
    B[Launch GUI]
    B --> C[Take Images]
    C --> D[Train Images]
    D --> E[Recognize Faces and Take Attendance]
    E --> F[Store Attendance in CSV/Database]
```
# How to Use
### 1. Capture Images: 
Click the "Take Images" button to capture face images from the webcam.
### 2. Train the Model: 
Once the images are captured, click "Train Images" to train the face recognition model.
### 3. Recognize Faces: 
To recognize faces and log attendance, click "Take biometrics" and follow the instructions.
### 4. Manually Fill Attendance: 
If needed, manually enter attendance by clicking "Manually Fill the biometrics."
The system also provides a feature to export the attendance data to a CSV file or store it in a MySQL database.

# Key Features & Modules:
### GUI Interface: 
Provides an intuitive graphical interface using Tkinter, allowing users to interact with the system to capture images, train the face recognition model, recognize faces for attendance, and manually input attendance if needed.
### Image Capture & Face Recognition: 
Uses OpenCV for detecting faces from a webcam feed. Capture images using the webcam, train a model, and recognize faces in real-time to log attendance.
### CSV and Database Storage and Integration: 
Attendance records are stored in CSV format. Also, the user can store the data in a MySQL database for efficient data storage and retrieval. For convenient, the user can export attendance data in CSV format for easy access and review.
### Manual Attendance Entry: 
If automatic recognition is not possible, the system offers a manual attendance entry option through the GUI.

