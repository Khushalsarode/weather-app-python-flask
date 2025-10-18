# 🤝 Contribution Guide for Weather App

Welcome to the **Weather App** project! 🌤️  
We’re thrilled that you’re interested in contributing.  
This document provides all the details you need to **set up the project locally**, **understand its structure**, and **make effective contributions**.

---

## 🧭 Table of Contents

1. [Project Overview](#project-overview)
2. [System Requirements](#system-requirements)
3. [Setup Instructions](#setup-instructions)
4. [Project Configuration](#project-configuration)
5. [Running the Application](#running-the-application)
6. [Testing the Application](#testing-the-application)
7. [Contributing Guidelines](#contributing-guidelines)
8. [Coding Standards](#coding-standards)
9. [Commit Message Format](#commit-message-format)
10. [Raising Issues & Feature Requests](#raising-issues--feature-requests)

---

## 🌍 Project Overview

The **Weather App** is a Flask-based web application that displays **real-time weather**, **air quality**, and a **5-day forecast** for any city using the **OpenWeatherMap API**.

It combines a Python backend with a modern, responsive frontend to create an intuitive and informative dashboard experience.

---

## 🖥️ System Requirements

Before you start, ensure that you have the following installed:

| Component | Version | Description |
|------------|----------|-------------|
| **Python** | 3.8 or higher | Required for Flask backend |
| **pip** | Latest | For package management |
| **Git** | Latest | For cloning and version control |
| **Virtualenv** | Optional | For isolated environments |

---

## ⚙️ Setup Instructions

Follow these steps to set up the project on your local machine.

### 1. Clone the Repository

```bash
git clone https://github.com/vishakhasarode/weather-flask-app.git
cd weather-flask-app
````

### 2. Create a Virtual Environment

It’s recommended to use a virtual environment to manage dependencies.

```bash
python -m venv venv
```

Activate it:

* **Windows**

  ```bash
  venv\Scripts\activate
  ```
* **macOS/Linux**

  ```bash
  source venv/bin/activate
  ```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

This installs Flask, requests, and other required libraries.

---

## 🔑 Project Configuration

### 1. Get an OpenWeatherMap API Key

1. Visit [OpenWeatherMap.org](https://openweathermap.org/api)
2. Sign up or log in.
3. Go to your **API Keys** section and copy your unique key.

### 2. Add API Key to the Project

Open `app.py` and locate this line:

```python
API_KEY = "YOUR_API_KEY"
```

Replace it with your actual API key:

```python
API_KEY = "your_openweathermap_api_key_here"
```

---

## ▶️ Running the Application

Once the setup and API configuration are complete:

```bash
python app.py
```

Flask will start the development server.
Open your browser and navigate to:

```
http://127.0.0.1:5000/
```

You should now see the **Weather Dashboard** running locally. 🎉

---

## 🧪 Testing the Application

You can perform quick manual tests such as:

* Searching for different city names (e.g., Pune, London, Tokyo)
* Clicking “Use My Location” to fetch geolocation-based weather
* Switching between Celsius (°C) and Fahrenheit (°F)
* Verifying that the AQI, charts, and map load correctly

---

## 💻 Project Structure Overview

```
weather-flask-app/
│
├── app.py                 # Flask backend
├── templates/
│   └── dashboard.html     # Main HTML page
├── static/
│   ├── css/
│   │   └── style.css      # Styling
│   ├── js/
│   │   └── script.js      # Frontend logic and API calls
│   └── images/
│       └── favicon.png
├── requirements.txt       # Dependencies list
├── README.md              # Main documentation
└── CONTRIBUTION.md        # This file
```

---

## 🌱 Contributing Guidelines

We welcome all contributions — from bug fixes to new features!

### 🧩 Steps to Contribute

1. **Fork** the repository.
2. **Clone** your fork locally.
3. **Create a new branch** for your feature or fix:

   ```bash
   git checkout -b feature/add-new-component
   ```
4. **Make your changes** in code or documentation.
5. **Test your changes** locally to ensure everything works.
6. **Commit and push** your branch:

   ```bash
   git add .
   git commit -m "Added new weather chart feature"
   git push origin feature/add-new-component
   ```
7. **Submit a Pull Request** (PR) to the `main` branch.

---

## 🧹 Coding Standards

To maintain code quality and readability:

* Follow **PEP 8** for Python code.
* Use **meaningful variable names**.
* Add comments for clarity.
* Keep HTML and CSS well-indented.
* Use consistent indentation (4 spaces for Python).
* Avoid committing large or unnecessary files (e.g., `__pycache__`, `.env`, or API keys).

---

## 📝 Commit Message Format

To keep a consistent commit history, follow this structure:

```
<type>(<scope>): <short description>
```

### Examples:

```
feat(api): added new air quality endpoint integration
fix(ui): corrected temperature toggle bug
docs(readme): updated introduction section
style(css): improved card layout responsiveness
```

**Commit Types:**

* `feat` → New feature
* `fix` → Bug fix
* `docs` → Documentation only
* `style` → Code formatting or UI styling
* `refactor` → Code restructuring without changing behavior
* `test` → Adding or fixing tests
* `chore` → Build, dependencies, or maintenance updates

---

## 🐛 Raising Issues & Feature Requests

If you encounter a bug or have an idea for improvement:

1. Go to the **Issues** tab on GitHub.
2. Click **“New Issue”**.
3. Choose a template (Bug Report / Feature Request).
4. Provide detailed steps and screenshots if possible.

---

## 💬 Community & Support

If you need help, feel free to:

* Open a discussion on the GitHub **Discussions** tab.
* Tag `@vishakhasarode` in your issue or pull request for review.

---

## 💖 Thank You!

Your contributions make this project better for everyone!
Whether you’re fixing a typo or building a new feature — **you’re awesome**. 🌈

> “The best way to predict the weather is to help build the forecast.” ⛅

```

---
