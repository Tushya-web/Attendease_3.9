
<center><img width="290" height="80" alt="AttendEase" src="https://github.com/user-attachments/assets/18f6c229-4bda-4c21-b791-4ee18e2ccdc3" /></center>

> AttendEase is an AI-powered face recognition attendance system built with Django, DeepFace (FaceNet), OpenCV, and Jazzmin.  
> It ensures secure, real-time attendance logging using deep learning–based face verification and anti-spoofing.
> (Django + DeepFace/FaceNet + Jazzmin + HTML/CSS/JS)

### AttendEase is a full-stack, intelligent attendance automation system powered by Django, DeepFace/FaceNet, OpenCV, and a clean Jazzmin-powered admin dashboard.
It features secure face verification, user registration, attendance tracking, leave management, and admin control.

## 📑 Table of Contents
- [Technology Documentation](#-technology-documentation-which-used)
- [Project Information](#project-information)
- [AI + Face Verification](#ai--face-verification)
- [User Portal](#user-portal)
- [Admin Panel](#admin-panel-jazzmin-dashboard)
- [Demo](#demo)
- [Installation](#installation--setup-step-by-step)
- [Project Structure](#project-structure)
- [Author](#author)



## 📘 Technology Documentation which used
<!-- Tech Stack Badges -->
<p align="left">

<!-- Python -->
<a href="https://www.python.org/" target="_blank">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python Badge"/>
</a>

<!-- Django -->
<a href="https://www.djangoproject.com/" target="_blank">
  <img src="https://img.shields.io/badge/Django-4.x-0C4B33?style=for-the-badge&logo=django&logoColor=white" alt="Django Badge"/>
</a>

<!-- DeepFace -->
<a href="https://serengil.github.io/deepface/" target="_blank">
  <img src="https://img.shields.io/badge/DeepFace-FaceNet-F9A825?style=for-the-badge&logo=google&logoColor=white" alt="DeepFace Badge"/>
</a>

<!-- FaceNet -->
<a href="https://arxiv.org/abs/1503.03832" target="_blank">
  <img src="https://img.shields.io/badge/FaceNet-Embedding%20Model-1976D2?style=for-the-badge&logo=google&logoColor=white" alt="FaceNet Badge"/>
</a>

<!-- OpenCV -->
<a href="https://opencv.org/" target="_blank">
  <img src="https://img.shields.io/badge/OpenCV-Computer%20Vision-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV Badge"/>
</a>

<!-- Jazzmin -->
<a href="https://django-jazzmin.readthedocs.io/" target="_blank">
  <img src="https://img.shields.io/badge/Jazzmin-Admin%20Theme-8A2BE2?style=for-the-badge&logo=django&logoColor=white" alt="Jazzmin Badge"/>
</a>

<!-- HTML -->
<a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank">
  <img src="https://img.shields.io/badge/HTML5-Frontend-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML Badge"/>
</a>

<!-- CSS -->
<a href="https://developer.mozilla.org/en-US/docs/Web/CSS" target="_blank">
  <img src="https://img.shields.io/badge/CSS3-Styles-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS Badge"/>
</a>

<!-- JavaScript -->
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank">
  <img src="https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript Badge"/>
</a>

</p>

## 🎥 Demo
![AttendEase Demo](https://github.com/user-attachments/assets/03b4130c-6bcc-4957-811b-0bff7711e6cb)

## ⭐ Features
- Django-based full-stack architecture  
- DeepFace FaceNet-based face matching  
- Secure master-face verification  
- Real-time webcam-based recognition  
- IN/OUT time-based attendance  
- User + Admin dashboards  
- Leave management system  
- Attendance export (CSV/PDF)  

## Project Information

- Django-based Web Application
- Face Recognition using DeepFace (FaceNet backend)
- Real-Time Attendance Marking with Liveness Detection
- Admin Dashboard Powered by Jazzmin
- Student/Employee Management
- Daily Attendance, Time-based Attendance (IN/OUT)
- Export Attendance as CSV/Excel
- Responsive UI (HTML, CSS, JS)

## AI + Face Verification
- DeepFace with FaceNet model
- Real-time webcam recognition
- Liveness detection (anti-spoofing)
- Face must match the master/default face uploaded by admin

## User Portal
- Register & Login
- Add face (must match master data)
- Mark attendance
- View attendance
- View uploaded faces
- Apply for leave
- Update personal information
- Download attendance (PDF/CSV)

## Admin Panel (Jazzmin Dashboard)
- Upload master data (student/faculty records)
- Approve or reject user registration
- Manage users, faculty, students
- Approve/reject leave requests
- Manage face entries
- View attendance analytics
- Export attendance reports

### Installation & Setup (Step-by-Step)

**1️. Clone the Repository**
```
git clone https://github.com/Tushya-web/Attendease_3.9.git

```

**2️. Create Virtual Environment**
```
python -m venv env

source env/bin/activate   # Linux/Mac

env\Scripts\activate      # Windows
```

**3️. Install Dependencies**
```
pip install -r requirements.txt
```

**4️. Apply Migrations**
```
python manage.py makemigrations

python manage.py migrate
```

**5️. Create Superuser (Admin Login)**
```
python manage.py createsuperuser
```

**6️. Run Development Server**
```
python manage.py runserver
```

## Project Structure
```
AttendEase/
│
├── attendease/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── attendance_app/
│   ├── models.py
│   ├── views.py
│   ├── detectors/
│   │   ├── facenet.py
│   │   └── liveness.py
│   ├── templates/
│   ├── static/
│   ├── utils/
│   └── urls.py
│
├── media/
│   ├── master_faces/
│   └── user_faces/
│
├── requirements.txt
└── README.md
```

### Author

Tushya R. Parmar

AI and Computer Vision Enthusiast

![GitHub Repo stars](https://img.shields.io/github/stars/Tushya-web/Attendease_3.9?style=flat)
![GitHub forks](https://img.shields.io/github/forks/Tushya-web/Attendease_3.9?style=flat)
![GitHub issues](https://img.shields.io/github/issues/Tushya-web/Attendease_3.9?style=flat)












