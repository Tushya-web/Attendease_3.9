# AttendEase – AI Powered Face Recognition Attendance System
## (Django + DeepFace/FaceNet + Jazzmin + HTML/CSS/JS)

### AttendEase is a full-stack, intelligent attendance automation system powered by Django, DeepFace/FaceNet, OpenCV, and a clean Jazzmin-powered admin dashboard.
It features secure face verification, user registration, attendance tracking, leave management, and admin control.

https://github.com/user-attachments/assets/03b4130c-6bcc-4957-811b-0bff7711e6cb

## Project Information

Django-based Web Application

Face Recognition using DeepFace (FaceNet backend)

Real-Time Attendance Marking with Liveness Detection

Admin Dashboard Powered by Jazzmin

Student/Employee Management

Daily Attendance, Time-based Attendance (IN/OUT)

Export Attendance as CSV/Excel

Responsive UI (HTML, CSS, JS)

## AI + Face Verification

DeepFace with FaceNet model

Real-time webcam recognition

Liveness detection (anti-spoofing)

Face must match the master/default face uploaded by admin

## User Portal

Register & Login

Add face (must match master data)

Mark attendance

View attendance

View uploaded faces

Apply for leave

Update personal information

Download attendance (PDF/CSV)

## Admin Panel (Jazzmin Dashboard)

Upload master data (student/faculty records)

Approve or reject user registration

Manage users, faculty, students

Approve/reject leave requests

Manage face entries

View attendance analytics

Export attendance reports


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
> AttendEase/
>
> │
>
> ├── attendease/               # Core Django project
>
> ├── attendance_app/           # Main features
>
> │   ├── models.py             # Database models
>
> │   ├── views.py              # Logic & AI processing
>
> │   ├── detectors/            # FaceNet + Liveness
>
> │   ├── static/               # CSS, JS
>
> │   ├── templates/            # HTML pages
>
> │   ├── utils/                # Helper scripts
>
> │   └── urls.py
>
> │
>
> ├── media/                    # User uploaded images
>
> │   ├── master_faces/
>
> │   └── user_faces/
>
> │
>
> ├── requirements.txt
> 
> └── README.md

### Author

Tushya R. Parmar

AI and Computer Vision Enthusiast












