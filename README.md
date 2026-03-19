# ✨ FUn WITH TEXT — TextUtils

A simple yet powerful **Django web app** that lets you analyze and manipulate text in various ways. Built as a learning project to explore Django's request-response pipeline and template rendering.

---

## 🚀 Features

| Feature | Description |
|---|---|
| 🔡 **Remove Punctuations** | Strips all punctuation marks from your text |
| 🔠 **Uppercase Converter** | Converts all text to UPPERCASE |
| 🔃 **New Line Remover** | Removes all newline/carriage return characters |
| ␣ **Extra Space Remover** | Removes consecutive extra spaces |

---

## 🛠️ Tech Stack

- **Backend**: Python 3 + Django 6
- **Frontend**: HTML5 + Bootstrap 4
- **Templating**: Django Template Language (DTL)

---

## ⚙️ Getting Started

### Prerequisites
- Python 3.x installed
- pip

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/h-arshit-a/TextUtils.git
cd TextUtils

# 2. Create a virtual environment (recommended)
python -m venv venv
venv\Scripts\activate   # On Windows

# 3. Install Django
pip install django

# 4. Run migrations
python manage.py migrate

# 5. Start the development server
python manage.py runserver
```

Then open your browser and go to **http://127.0.0.1:8000/**

---

## 📁 Project Structure

```
TextUtils/
│
├── myprojectutils/        # Django project settings
│   ├── settings.py
│   ├── urls.py
│   └── views.py
│
├── templates/             # HTML templates
│   ├── index.html         # Home page
│   └── analyze.html       # Results page
│
├── static/                # Static assets (favicon, etc.)
├── manage.py
├── .gitignore
└── README.md
```

---

## 👩‍💻 Author

**Harshita** — [@h-arshit-a](https://github.com/h-arshit-a)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
