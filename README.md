# Federated Learning Based Face and Eye Blink Recognition

This project implements a biometric authentication system using **Face Recognition** and **Eye Blink Pattern**.  
It uses a federated learning approach where models are trained locally and then updated to a central server without sharing raw user data.

## 🔍 Features

- Face registration using webcam
- Eye blink pattern training as a password
- Federated model update to server
- Face authentication
- Eye blink authentication
- GUI built using Tkinter
- Uses OpenCV, Dlib, and Face Recognition libraries

## 🛠️ Technologies Used

- Python
- OpenCV
- Dlib
- face_recognition
- Tkinter
- NumPy, SciPy, Imutils
- Socket programming (for server-client communication)

## 📂 Project Structure

- `Main.py` – Client application (GUI + face/eye logic)
- `Server.py` – Federated server
- `model/` – Contains required model files
- `run.bat` – Starts client application
- `runServer.bat` – Starts server
- `requirements.txt` – Required Python libraries
- `SCREENS.docx` – Project screenshots and explanation

## ⚙️ Setup Instructions

1. Install Python (recommended: Python 3.10 or compatible)
2. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
