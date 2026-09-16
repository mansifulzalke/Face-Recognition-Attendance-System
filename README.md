# Face Recognition Attendance Software

A smart, real-time attendance system that utilizes AI-powered facial recognition to automate and secure attendance logging, built under the guidance of Dr. Jayashree Rajesh Prasad at the Department of Computer Science & Engineering, MITSoC, Loni Kalbhor[cite: 1].

---

## Features
* **Real-Time Recognition:** Captures and matches facial data instantly via webcam integration.
* **User-Friendly GUI:** Dark-themed desktop interface built using Tkinter.
* **Voice Feedback:** Text-to-Speech integration (`pyttsx3`) for improved accessibility.
* **Automated CSV Logs:** Stores and manages attendance data cleanly using Pandas, categorized by subject and timestamp.
* **High Accuracy:** Employs Haar Cascade Classifiers for face detection and Local Binary Pattern Histograms (LBPH) for face recognition.

---

## Tech Stack & Tools
* **Programming Language:** Python
* **Computer Vision / ML:** OpenCV, NumPy
* **GUI & Images:** Tkinter, PIL (Pillow)
* **Data Management:** Pandas (CSV storage)
* **Accessibility:** pyttsx3 (Text-to-Speech)
* **IDE:** VS Code

---

## System Architecture / Workflow
1. **Register Face:** Input student details (Enrollment No. & Name) and capture training images via webcam.
2. **Train Model:** Train the LBPH face recognition model using the captured face data.
3. **Take Attendance:** Enter the subject name, start the live camera session, detect faces, recognize registered students, and mark attendance automatically.
4. **View Attendance:** Check and review generated subject-wise CSV logs.

---

## Installation & Setup

1. **Clone or Download** this repository to your local machine.
2. **Install the required dependencies** by running the following command in your terminal/command prompt:
   ```bash
   pip install -r requirements.txt
