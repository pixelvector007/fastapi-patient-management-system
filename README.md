<<<<<<< HEAD
# FastAPI Learning 🚀

A collection of projects and experiments built while learning **FastAPI**, Python backend development, and RESTful APIs.

This repository documents my journey of understanding backend development through hands-on projects, from basic API creation to building complete web applications.

## 📚 What I'm Learning

- FastAPI fundamentals
- RESTful API development
- Pydantic and data validation
- CRUD operations
- Dependency injection
- API documentation with Swagger UI
- Backend and frontend integration
- Docker and deployment

## 🛠️ Tech Stack

- Python
- FastAPI
- Pydantic
- Uvicorn
- HTML, CSS, JavaScript
- Git & GitHub

## 📂 Projects

| Project | Description | Status |
|---|---|---|
| Patient Management System | A patient management application with a FastAPI backend and a web-based frontend. | 🚧 In Progress |

More projects will be added as I continue learning and exploring FastAPI.

## ⚙️ Getting Started

### Clone the Repository

```bash
git clone https://github.com/pixelvector007/fastapi-learning.git
cd fastapi-learning
```

### Create a Virtual Environment

```bash
python -m venv myenv
```

### Activate the Virtual Environment
=======
# 🏥 PatientCare — Patient Management System

A full-stack patient management application built using **FastAPI, Pydantic, HTML, CSS, and JavaScript**.

PatientCare provides a REST API and a web-based dashboard to manage patient records, calculate BMI, and explore backend development concepts through a practical application.

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-009688?logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-v2-E92063)
![HTML5](https://img.shields.io/badge/HTML5-Frontend-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-Frontend-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?logo=javascript&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-Supported-2496ED?logo=docker&logoColor=white)

---

## 📌 About the Project

**PatientCare** is a patient management system developed to explore backend development using FastAPI and the integration of REST APIs with a web-based frontend.

The application allows users to manage patient records, view patient information, and calculate BMI-based health categories.

It also includes a responsive dashboard with features such as search, filtering, sorting, statistics, and CSV export.

The project combines a Python backend with a browser-based frontend to demonstrate how APIs can power a practical web application.

---

## ✨ Features

### 🩺 Patient Management

- Create new patient records
- View individual patient details
- Update existing patient information
- Delete patient records
- Store patient data using JSON-based persistence

### 📊 BMI Calculation

- Automatically calculate BMI using height and weight
- Generate BMI-based health verdicts
- Include calculated values in patient responses

### 🌐 Web Dashboard

- Responsive patient management dashboard
- Search and filter patient records
- Sort patient data
- View dashboard statistics
- Export patient data to CSV
- Light and dark themes
- Demo mode for exploring the interface

### ⚙️ API Features

- RESTful API endpoints
- Request validation using Pydantic
- Interactive API documentation
- Modular application structure
- Docker support

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Backend development |
| FastAPI | REST API framework |
| Pydantic v2 | Data validation and models |
| HTML5 | Frontend structure |
| CSS3 | Styling and responsive layout |
| JavaScript | Frontend interactions and API integration |
| JSON | Data persistence |
| Docker | Application containerization |
| AI Tools | Assistance with frontend development |

---

## 📂 Project Structure

```text
PatientCare/
│
├── main.py
├── patients.json
├── requirements.txt
├── Dockerfile
│
├── models/
│   └── patient.py
│
├── routers/
│   └── patient.py
│
├── dependencies/
│   └── patient.py
│
├── utils/
│   └── database.py
│
└── website/
    ├── index.html
    ├── dashboard.html
    ├── style.css
    ├── common.js
    ├── landing.js
    └── dashboard.js

---

## 🚀 Getting Started

Follow these steps to run PatientCare locally.

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd PatientCare
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the virtual environment.
>>>>>>> b92b766 (Change the Structure)

**macOS / Linux**

```bash
<<<<<<< HEAD
source myenv/bin/activate
=======
source venv/bin/activate
>>>>>>> b92b766 (Change the Structure)
```

**Windows**

```bash
<<<<<<< HEAD
myenv\Scripts\activate
```

### Install Dependencies
=======
venv\Scripts\activate
```

### 3. Install Dependencies
>>>>>>> b92b766 (Change the Structure)

```bash
pip install -r requirements.txt
```

<<<<<<< HEAD
### Run a Project

Navigate to the respective project directory and start the FastAPI application:

```bash
python -m uvicorn main:app --reload
```

Once the server starts, visit:

| Resource | URL |
|---|---|
| API | http://127.0.0.1:8000 |
| Swagger UI | http://127.0.0.1:8000/docs |
| ReDoc | http://127.0.0.1:8000/redoc |

> **Note:** The commands and dependencies may vary depending on the individual project.

## 🎯 Goal

To strengthen my backend development fundamentals by building practical applications and gradually exploring more advanced concepts such as authentication, databases, Docker, and cloud deployment.

---

Thanks for visiting!

If you find this repository useful, consider giving it a ⭐
=======
### 4. Start the FastAPI Server

```bash
uvicorn main:app --reload
```

The API will be available at:

```text
http://127.0.0.1:8000
```

### 5. Explore the API Documentation

FastAPI automatically generates interactive API documentation.

- **Swagger UI:** `http://127.0.0.1:8000/docs`
- **ReDoc:** `http://127.0.0.1:8000/redoc`

---

## 🔗 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/health` | Check API health |
| GET | `/view` | View patient records |
| GET | `/sort` | Sort patient records |
| GET | `/patient/{patient_id}` | Retrieve a specific patient |
| POST | `/create` | Create a patient record |
| PUT | `/edit/{patient_id}` | Update a patient record |
| DELETE | `/delete/{patient_id}` | Delete a patient record |

> For available parameters, request schemas, and response details, explore the interactive API documentation at `/docs`.

---

## 🐳 Run with Docker

Build the Docker image:

```bash
docker build -t patientcare .
```

Run the container:

```bash
docker run -p 8000:8000 patientcare
```

The API will be available at:

```text
http://127.0.0.1:8000
```

---

## 🤖 AI-Assisted Development

AI tools were used to assist with the development of the PatientCare frontend, including parts of the UI design, layout, styling, and JavaScript implementation.

This project provided an opportunity to explore AI-assisted development while learning how a frontend interacts with a FastAPI backend.

It also helped me understand API integration, application structure, data validation, and the process of connecting backend functionality with a user-facing interface.

---

## 📚 Key Learnings

Through this project, I explored:

- Building REST APIs using FastAPI
- Defining and validating data with Pydantic
- Organizing a backend using routers, models, and dependencies
- Implementing CRUD operations
- Working with JSON-based data persistence
- Connecting a frontend to backend API endpoints
- Understanding request and response handling
- Using Docker to containerize an application
- Exploring AI-assisted frontend development

---

## 🔮 Future Improvements

- Replace JSON storage with a relational database
- Add authentication and authorization
- Improve error handling and API responses
- Add automated tests
- Deploy the application online
- Improve frontend functionality and API integration

---

## ⭐ Thanks for Visiting!

If you found this project interesting, consider giving the repository a star.
>>>>>>> b92b766 (Change the Structure)

**Made with ❤️ by Arpit Kushwaha**
