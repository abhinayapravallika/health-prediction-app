# Health Prediction Application

A full-stack Health Prediction Application built using Flask, SQLite, Bootstrap, and Google Gemini AI. The application allows users to manage patient records and generate AI-powered health insights based on blood test results.

## Features

* Patient Record Management (CRUD Operations)
* Add, View, Update, and Delete Patient Records
* AI-Powered Health Prediction using Google Gemini API
* Blood Test Analysis
* Data Validation
* Responsive User Interface
* SQLite Database Storage
* Flask Backend
* Bootstrap Styling
* Session-Based Web Application

---

## Tech Stack

### Frontend

* HTML5
* CSS3
* Bootstrap 5

### Backend

* Flask
* SQLAlchemy
* Python

### Database

* SQLite

### AI Integration

* Google Gemini API

---

## Project Structure

```text
health-prediction-app/
|
├── app.py
|
├── requirements.txt
|
├── .gitignore
|
├── static/
|    └── style.css
|
├── templates/
|    ├── index.html
|    ├── add.html
|    └── edit.html
|
└── Screenshots/
```

## Application Workflow

1. User enters patient details:

   * Full Name
   * Date of Birth
   * Email Address
   * Glucose
   * Haemoglobin
   * Cholesterol

2. The application validates input data.

3. Patient data is sent to the Gemini AI model.

4. Gemini analyzes blood test values and generates a health prediction.

5. Prediction results are stored in the Remarks field.

6. Users can:

   * Create patient records
   * View patient records
   * Update patient records
   * Delete patient records

---

## Installation

### Clone Repository

git clone https://github.com/abhinayapravallika/health-prediction-app.git

cd health-prediction-app

### Create Virtual Environment

python -m venv venv

### Activate Virtual Environment

Windows:

venv\Scripts\activate

### Install Dependencies

pip install -r requirements.txt

### Configure Environment Variables

Create a .env file:

GEMINI_API_KEY=YOUR_GEMINI_API_KEY

### Run Application

python app.py

Open Browser:

http://127.0.0.1:5000

---

## Screenshots

### Home Page

Displays all patient records along with AI-generated health remarks.

### Add Patient

Allows users to enter patient details and generate health predictions.

### Edit Patient

Allows updating existing patient records and regenerating predictions.

---

## Future Enhancements

* Search Patient Records
* Export Reports to Excel
* PDF Report Generation
* User Authentication
* Advanced Machine Learning Models
* Health Risk Visualization Dashboard
* Cloud Deployment

---

## Author

Ramena Abhinaya Pravallika

B.Tech – Artificial Intelligence & Machine Learning

Full Stack Developer

Oracle Generative AI Certified Professional

GitHub: https://github.com/abhinayapravallika

LinkedIn: [www.linkedin.com/in/ramena-abhinaya-pravallika](http://www.linkedin.com/in/ramena-abhinaya-pravallika)
