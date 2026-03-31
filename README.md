# 🚀 Django Job Application Portal

A robust, full-stack web application built with Django that securely processes job application submissions. The system captures user data through a responsive frontend, validates and persists the information in a relational database, and automatically dispatches SMTP-based email confirmations to applicants.

### Fill Data
<img width="1837" height="860" alt="django-application-form" src="https://github.com/user-attachments/assets/d5e7941d-1c68-443e-9017-7b95460db886" />

### Email sent
<img width="1813" height="865" alt="Submission-mail" src="https://github.com/user-attachments/assets/6cdffad2-3828-4541-8041-5ab60f5603a1" />

### Administration login
<img width="553" height="447" alt="django-login" src="https://github.com/user-attachments/assets/87bb966e-2ff4-4cf3-8fe5-6afd2609f123" />

### Aministration files
<img width="1870" height="751" alt="administartion-home" src="https://github.com/user-attachments/assets/fdb1bd45-d14b-4d48-9141-7dbd593cef27" />

### User Data
<img width="1882" height="858" alt="django-admistration-page" src="https://github.com/user-attachments/assets/0fc27627-cca0-4370-9056-7bf206c598e8" />


## 🧠 System Architecture

* **Frontend:** HTML5, CSS3, and Bootstrap 5 (via CDN) for a responsive, mobile-first user interface. Jinja-style Django templating is used for dynamic data rendering and flash messaging.
* **Backend Framework:** Django (Python).
* **Database:** SQLite3 (development) integrated via Django's built-in ORM.
* **Notification Engine:** Django Core Mail utility configured for secure SMTP transmission.

## ⚙️ Prerequisites

Ensure you have the following installed on your local machine:
* [Python 3.10+](https://www.python.org/downloads/)
* `pip` (Python package installer)
* Git

## 🛠️ Installation & Setup Guide

Follow these steps to replicate the development environment and run the application locally.

### 1. Clone the Repository
```bash
git clone https://github.com/Nayanxyz/Django-Application-from-App17.git
cd Django-Application-from-App17
```
### 2. Install Dependencies
```bash
pip install django
```
### 3. Initialize the Database
```bash
python manage.py makemigrations
python manage.py migrate
```
### 4. Create a superuser 
```bash
python manage.py createsuperuser
```
### 5. Launch the Application
```bash
python manage.py runserver
```
