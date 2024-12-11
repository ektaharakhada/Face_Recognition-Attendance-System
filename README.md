# Face_Recognition-Attendance-System
## Overview
The **Face Recognition Attendance System** is a Python-based application that automates the process of taking attendance using facial recognition technology. This system uses machine learning models for detecting and recognizing faces, providing an efficient and reliable way to track attendance in educational institutions or workplaces.

## Features
- **Face Detection and Recognition**: Uses Haar Cascade classifiers for face detection and LBPH (Local Binary Patterns Histograms) for recognition.
- **Attendance Management**: Automatically logs attendance into a database or CSV file.
- **User-friendly Interface**: Simple and intuitive interface for users to interact with the system.
- **Student Management**: Add, update, and manage student data.
- **Training Module**: Train the system with new faces for better accuracy.

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - Dlib for facial feature extraction and recognition.
  - OpenCV for image processing and face detection.
  - NumPy for numerical computations.
- **Database**: SQLite or MySQL
- **Tools**: Visual Studio Code

## How It Works
### Face Detection:
- The system detects faces using advanced algorithms.

### Face Recognition:
- Extracts unique facial embeddings for each detected face.
- Matches embeddings with stored data to identify individuals.

### Attendance Logging:
- Logs recognized faces with names and timestamps into the database.
- Generates attendance reports for review.

## Requirements
To run this project, you need the following:
- **Python 3.8 or higher**
- Required Python Libraries:
  - `opencv-python`
  - `numpy`
  - `pandas`
  - `sqlite3`
