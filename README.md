# AttendEase – AI Powered Face Recognition Attendance System
## (Django + DeepFace/FaceNet + Jazzmin + HTML/CSS/JS)

### AttendEase is a full-stack, intelligent attendance automation system powered by Django, DeepFace/FaceNet, OpenCV, and a clean Jazzmin-powered admin dashboard.
It features secure face verification, user registration, attendance tracking, leave management, and admin control.

https://github.com/user-attachments/assets/03b4130c-6bcc-4957-811b-0bff7711e6cb

## Project Information

_Django-based Web Application_

_Face Recognition using DeepFace (FaceNet backend)_

_Real-Time Attendance Marking with Liveness Detection_

_Admin Dashboard Powered by Jazzmin_

_Student/Employee Management_

_Daily Attendance, Time-based Attendance (IN/OUT)_

_Export Attendance as CSV/Excel_

_Responsive UI (HTML, CSS, JS)_

## AI + Face Verification

_DeepFace with FaceNet model_

_Real-time webcam recognition_

_Liveness detection (anti-spoofing)__

_Face must match the master/default face uploaded by admin_

## User Portal

_Register & Login_

_Add face (must match master data)_

_Mark attendance_

_View attendance_

_View uploaded faces_

_Apply for leave_

_Update personal information_

_Download attendance (PDF/CSV)_

## Admin Panel (Jazzmin Dashboard)

_Upload master data (student/faculty records)_

_Approve or reject user registration_

_Manage users, faculty, students_

_Approve/reject leave requests_

_Manage face entries_

_View attendance analytics_

_Export attendance reports_


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

> │

> ├── media/                    # User uploaded images

> │   ├── master_faces/

> │   └── user_faces/

> │
> ├── requirements.txt
> └── README.md

### Author

Tushya R. Parmar

AI and Computer Vision Enthusiast















