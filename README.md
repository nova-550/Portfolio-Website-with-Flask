# 💼 Shiv's Portfolio Website — Built with Flask

> 🚀 Internship Task 6 — BH Python Developer Internship  
> 🧰 Tech Stack: Python | Flask | HTML | CSS

---

## 📌 Project Description

This is a **personal portfolio website** developed using **Flask (Python Web Framework)** as part of the **BH Internship Task 6**. It showcases my technical skills, personal introduction, and projects, with a fully functional **contact form** (POST method only).

The project demonstrates:
- Flask Routing & Templating (Jinja2)
- Static file management (CSS)
- Contact Form Handling
- Clean HTML & CSS layout
- Local testing using `Flask`'s development server

---

## 📁 Project Structure

```
flask_portfolio/
│
├── app.py # Main Flask application
│
├── static/ # Static files (CSS, images, JS)
│ └── styles.css
│
├── templates/ # HTML Templates
│ ├── index.html # Home Page
│ ├── about.html # About Me Page
│ └── contact.html # Contact Form Page
│
└── README.md # Project Documentation
```
---

## 🌐 Routes and Pages

| Route        | Description                    |
|--------------|--------------------------------|
| `/`          | Home Page (Name, tagline, projects) |
| `/about`     | About Me (Short bio)           |
| `/contact`   | Contact form (POST enabled)    |

---

## 🛠️ How to Run This Project Locally

### 1. Clone the repository or download ZIP
```
- git clone https://github.com/your-username/Portfolio-Website-with-Flask
.git
-cd Portfolio-Website-with-Flask
```
### 2. Create and activate virtual environment

```
- python -m venv venv  
-venv\Scripts\activate   # Windows   
- source venv/bin/activate  # Mac/Linux
```
### 3. Install Flask

```
pip install flask
```
### 4. Run the app

```
python app.py
```

### 5. Visit in browser
    http://127.0.0.1:5000/
    
## 💡 Features Implemented
✅ Flask server with multiple routes

✅ Jinja2-based HTML templating

✅ Proper static file linking using url_for

✅ Clean and responsive layout with custom CSS

✅ Contact form submission with POST method

✅ Prints form input to console (simulate message capture)

## 🧠 Key Concepts Learned
Flask Routing

Flask Templates & Jinja2

Form Handling in Flask (request.method == 'POST')

Serving static files (CSS)

Project structuring best practices