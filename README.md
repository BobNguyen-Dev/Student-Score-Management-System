
# 📚 Student Score Management System

A complete web application to manage student scores, built with Flask, HTML/CSS, and SQLite.

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-green?logo=flask)
![SQLite](https://img.shields.io/badge/SQLite-Database-lightgrey?logo=sqlite)
![Status](https://img.shields.io/badge/Project%20Status-In%20Development-yellow)

---

## 🚀 Features

- ✅ User registration and login  
- ✅ Role-based access (Teacher & Student)  
- ✅ Enter, edit, and view student scores  
- ✅ Average score calculation  
- ✅ Visualize scores with charts  
- ✅ Password reset via email (Flask-Mail)  
- ✅ Simple and responsive UI  

---

## 🧑‍🏫 Demo Roles

- **Teacher** can:
  - Manage all students’ scores
  - View and edit any score
  - Access dashboard and export functions
- **Student** can:
  - View their own scores
  - See performance charts

---

## 🛠 Technologies Used

- **Backend:** Python, Flask  
- **Frontend:** HTML, CSS (Bootstrap or custom)  
- **Database:** SQLite  
- **Email Service:** Flask-Mail  
- **Charting:** Matplotlib (optional)  
- **Environment:** dotenv  

---

## 📁 Project Structure

```
Work/
├── app.py                 # Main Flask app
├── pass.env              # Environment config
├── templates/            # HTML templates
│   ├── login.html
│   ├── register.html
│   ├── index.html
│   ├── teacher_dashboard.html
│   ├── student_score.html
│   ├── student_chart.html
│   ├── edit_score.html
│   ├── view_scores.html
│   ├── forgot_password.html
│   ├── reset_password.html
│   └── verify.html
```

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/student-score-system.git
cd student-score-system
```

### 2. Create a virtual environment

```bash
python -m venv venv
source venv/bin/activate   # or venv\Scripts\activate on Windows
```

### 3. Install dependencies

```bash
pip install flask flask-mail python-dotenv
```

### 4. Configure environment variables

Create a `.env` file based on `pass.env`:

```
MAIL_USERNAME=your_email@gmail.com
MAIL_PASSWORD=your_email_password
SECRET_KEY=random_secret_key
```

---

## ▶️ Run the App

```bash
python app.py
```

Visit `http://127.0.0.1:5000` in your browser.

---

## 📈 Future Improvements

- [ ] Export scores to Excel/PDF  
- [ ] Use Chart.js for better graph interactivity  
- [ ] Admin dashboard  
- [ ] Add AI model to predict future student performance  

---

## 👤 Author

- **👨‍🎓 Bob Nguyen**  
- 💼 High school student (Grade 10)  
- 🎯 Interested in AI & Cybersecurity (studying path to Germany 🇩🇪)  
- 📧 Contact: [bobnguyenn.dev@gmail.com]()

---

## ⭐ Star this project

If you like this project, please consider giving it a ⭐ on GitHub. It helps me a lot!
