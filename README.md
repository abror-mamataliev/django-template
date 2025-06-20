# 🐍 Django Project Template

This is a reusable Django project template that provides a solid starting point for building web applications with Django.

## 🚀 Quick Start

Follow these steps to set up and run the project on your local machine.

### 1. 🖁️ Clone the Repository

```bash
git clone https://github.com/abror-mamataliev/django-template.git
cd django-template
```

### 2. 🧪 Create and Activate Virtual Environment

#### Unix/macOS

```bash
python3 -m venv .venv
source .venv/bin/activate
```

#### Windows

```bash
python -m venv .venv
.venv\Scripts\activate
```

### 3. 📆 Install Dependencies

```bash
python -m pip install --upgrade pip setuptools
pip install -r requirements.txt
```

### 4. ⚙️ Configure Environment Variables

Copy the example `.env.example` to `.env` and update the values as needed:

```bash
cp .env.example .env
```

Make sure to configure values like `BASE_URL`, `SECRET_KEY`, `DEBUG`, etc.

### 5. 💠 Run Migrations

```bash
python manage.py migrate
```

### 6. 👤 Create Superuser (Admin Account)

```bash
python manage.py createsuperuser
```

### 7. 📂 Collect Static Files

```bash
python manage.py collectstatic
```

### 8. 🚴‍♀️ Run Development Server

```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000` in your browser to see the running app.

---

## 📁 Project Structure

```
django-template/
├── apps/                # Your custom Django apps
├── config/              # Django project settings
├── media/               # Uploaded media files
├── static/              # Static files (CSS, JS, etc.)
├── templates/           # HTML templates
├── .env                 # Environment variables
├── manage.py            # Django management script
└── requirements.txt     # Python dependencies
```

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
