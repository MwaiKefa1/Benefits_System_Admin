# Benefits_System_Admin

# Benefits Administration System

##  Overview

The Benefits Administration System is a complete HR tool built to make employee benefits easier to manage — from health insurance to retirement plans and wellness programs. HR teams get a streamlined dashboard, and employees get clarity and control over their benefits.

This project was built by humans, for humans — no AI shortcuts.



##  Features

- Enroll employees in benefits online
- View and manage all benefit plans
- Admin dashboard for HR professionals
- Secure database with audit trail
- Bootstrap-powered user interface



##  Tech Stack

- **Frontend**: HTML5, Bootstrap 5 (via Flask templates)
- **Backend**: Python 3, Flask, SQLAlchemy
- **Database**: SQLite (for simplicity)
- **Hosting Recommendation**: Render, Heroku, or Railway


## User Roles

- **Employees**: View and enroll in benefit plans
- **HR/Admins**: Add plans, manage enrollments, oversee employee records



## Installation Guide

1. **Clone the repository**:
    ```bash
    git clone https://your-repo-url
    cd benefits_admin_system
    ```

2. **Create a virtual environment (recommended)**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. **Install the dependencies**:
    ```bash
    pip install flask flask_sqlalchemy
    ```

4. **Seed the database with test data**:
    ```bash
    python seed.py
    ```

5. **Run the application**:
    ```bash
    python app.py
    ```

6. **Open in browser**: [http://127.0.0.1:5000](http://127.0.0.1:5000)


## Deployment Instructions

### Option 1: Render

1. Push to GitHub
2. Create new web service on [https://render.com](https://render.com)
3. Add `app.py` as the entry point
4. Set `PYTHON_VERSION` and `requirements.txt` properly

### Option 2: Heroku (legacy)

1. Install Heroku CLI
2. Add a `Procfile` with content:
    ```
    web: python app.py
    ```
3. Deploy via Git


## Project Structure

```
benefits_admin_system/
├── app.py
├── seed.py
├── README.md
├── Benefits_Administration_System_Presentation.pptx
├── templates/
│   ├── index.html
│   ├── employees.html
│   ├── add_employee.html
│   ├── benefits.html
│   ├── add_benefit.html
│   └── enroll.html
└── benefits.db (generated after running)
```

---

##  Sample Users

- Alice Juma (HR)
- Bob S Kimani (Finance)
- Carol James Kamau (IT)

---

## Author

Crafted by the HR Tech Team — with clarity, care, and code.
