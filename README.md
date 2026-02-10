# Face Detection System

A web-based **Face Detection System** that detects and recognizes faces using a webcam and marks attendance automatically.  
The system uses **Python, Flask, OpenCV, face_recognition, MySQL**, and a simple **HTML/CSS/JavaScript frontend**.

This project is designed as a **student-level AI + Web application** and is suitable for academic projects, demonstrations, and learning purposes.

---

## 📌 Features

- 👤 Student registration with face image
- 📷 Real-time face detection using webcam
- 🧠 Face recognition using trained face encodings
- 🗄️ MySQL database for storing students and attendance
- 📊 Attendance visualization using charts
- 📁 Attendance report download (CSV)
- 🌐 Web-based interface

---

## 🛠️ Technologies Used

### Backend
- Python
- Flask
- OpenCV
- face_recognition
- NumPy
- MySQL
- Pickle

### Frontend
- HTML
- CSS
- JavaScript
- Chart.js




## 📁 Project Structure
Face_Detection_System/
│
├── backend/
│ ├── app.py # Main Flask application
│ ├── db.py # Database operations
│ ├── face_model.py # Face encoding and recognition logic
│ └── ENCODE.p # Trained face encodings (auto-generated)
│
├── frontend/
│ ├── templates/
│ │ └── index.html # Main UI page
│ │
│ └── static/
│ ├── style.css # Styling
│ ├── main.js # Frontend controller
│ ├── form.js # Registration form logic
│ ├── webcam.js # Webcam handling
│ ├── utils.js # Utility functions
│ └── assets/
│ └── logo.png
│
├── package.json
├── package-lock.json
└── README.md


---

## ⚙️ How the System Works

1. User opens the web application.
2. Student registers by entering details and capturing a face image.
3. Face encodings are generated and stored in `ENCODE.p`.
4. Webcam captures live face for attendance.
5. The system compares the live face with stored encodings.
6. If matched, attendance is marked in the database.
7. Attendance is displayed using charts and can be downloaded as CSV.

---

## 🧪 Installation & Setup

### 1️⃣ Clone the Repository
git clone https://github.com/AAs6395/Face_Detection_System.git
cd Face_Detection_System

2️⃣ Install Python Dependencies
pip install flask opencv-python face-recognition numpy mysql-connector-python

3️⃣ Setup MySQL Database
Create a MySQL database (example: face_attendance)

Update database credentials in backend/db.py

Tables are created automatically when the app runs

4️⃣ Run the Application
python backend/app.py
Open your browser and visit:
http://127.0.0.1:5000/

📊 Output
Real-time face recognition

Automatic attendance marking

Attendance visualization (Pie Chart)

Downloadable attendance report (CSV)

🎓 Use Case
College attendance system

AI & ML academic project

Face recognition learning project

Web + AI integration demo

🚀 Future Enhancements
Face mask detection

Multiple camera support

Cloud database integration

Admin login system

Live deployment

👨‍💻 Author
Aashish Joshi
B.Tech CSE Student
Graphic Era Hill University, Bhimtal




