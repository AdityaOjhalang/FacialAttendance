# Facial Attendance System

The Facial Attendance System is a Python-based application that uses face recognition to mark attendance. It leverages the `face_recognition` library to detect and recognize faces, and then logs the attendance of recognized individuals.

## 🌟 Features

- **Face Encoding**: The system encodes facial features from a set of training images and uses them to recognize individuals in real-time.
- **Real-time Attendance Marking**: When a recognized face is detected, the system logs the attendance with the current timestamp.
- **Support for Multiple Faces**: The system can detect and recognize multiple faces in real-time.
- **CSV Logging**: Attendance is logged in a CSV file, making it easy to integrate with other systems or for further analysis.

## 📂 Key Files

- [**AttendanceProject.py**](https://github.com/AdityaOjhalang/FacialAttendance/blob/master/AttendanceProject.py): This is the main file responsible for capturing video feed, recognizing faces, and marking attendance.
- [**main.py**](https://github.com/AdityaOjhalang/FacialAttendance/blob/master/main.py): A test script that demonstrates face recognition using a pair of images.

## 🚀 How to Use

1. Add training images to the `ImagesAttendance` directory. The system will use these images to recognize individuals.
2. Run `AttendanceProject.py` to start the attendance system.
3. The system will capture video from the default camera and recognize faces in real-time.
4. Recognized faces will have their attendance marked in the `Attendance.csv` file.

## 📦 Dependencies

- `face_recognition`
- `cv2` (OpenCV)
- `numpy`
