# 📝 Flask Todo Application

A simple and lightweight web application to manage your daily tasks using **Flask**, **SQLAlchemy**, and **SQLite**.

---

## 🚀 Features

* Add new tasks with a title and description.
* View all your pending tasks in a clean list.
* Update existing tasks when things change.
* Delete tasks once they are completed.
* Persistent storage using a local SQLite database.
* Clean web interface using HTML and Jinja2 templates.

---

## 🛠️ Tech Stack

* Python
* Flask
* Flask-SQLAlchemy
* SQLite
* HTML / CSS / Jinja2

---

## 📂 Project Structure

```text
todo/
│
├── app.py               # Flask web application and routes
├── instance/
│   └── todo.db          # SQLite database (auto-generated)
├── templates/
│   └── index.html       # Main HTML template for the UI
├── static/              # Static files (CSS, JS, Images)
├── venv/                # Python virtual environment
├── .gitignore           # Git ignore file for sensitive/unnecessary files
└── README.md
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/flask-todo-app.git
cd flask-todo-app
```

### Setup Virtual Environment & Install Dependencies

```bash
# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# Install required packages
pip install Flask Flask-SQLAlchemy
```

### Run the Application

```bash
python app.py
```

The app will start running locally. Open your browser and go to `http://127.0.0.1:5000`.

---

## 💻 Usage

1. Open the application in your browser.
2. Enter a task **Title** and **Description** in the form.
3. Click the submit button to add it to your list.
4. Use the **Update** button next to any task to modify its details.
5. Use the **Delete** button to remove a task once it's completed.

---

## 📷 Example

### Input

```text
Title: Complete GitHub README
Description: Write the README.md file with tech stack and installation steps.
```

### Action

* Task appears in your list immediately and is saved to the database!

---

© 2026 Kunal Singh
