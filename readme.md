# Django Authentication & Authorization App

A basic Django project with:
- Sign up
- Login / Logout
- Dashboard (login required)
- Staff-only page

## Setup

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
py -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
