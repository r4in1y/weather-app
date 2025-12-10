# 🌤 Weather App

A **chill and responsive weather app** built with **FastAPI** and **Tailwind CSS**.
Check the weather of any city with instant, beautifully styled results and subtle animations.

---

## **Features**

* Fetches real-time weather data from **OpenWeatherMap API** (or any API you choose).
* Responsive, mobile-friendly design using **Tailwind CSS**.
* Animated weather icons for a lively, interactive feel.
* Smooth fade-in animation for weather results.
* Simple and intuitive UI for a chill user experience.

---

## **Screenshots**

![Weather App Screenshot](/Weather%20App.png)
*Example: Weather in California*

---

## **Installation**

1. **Clone the repository:**

```bash
git clone https://github.com/r4in1y/weather-app.git
cd weather-app
```

2. **Create a virtual environment and activate it:**

```bash
python -m venv venv
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate
```

3. **Install dependencies:**

```bash
pip install -r requirements.txt
```

---

## **Usage**

1. Start the FastAPI server:

```bash
uvicorn main:app --reload
```

2. Open your browser and go to:

```
http://127.0.0.1:8000
```

3. Enter any city name and click **Check Weather**.

---

## **Project Structure**

```
weather-app/
├── main.py           # FastAPI app
├── templates/
│   └── index.html    # HTML template with Tailwind CSS
├── static/           
├── requirements.txt  # Python dependencies
└── README.md
```

---

## **Technologies Used**

* **FastAPI** – Modern Python web framework for APIs.
* **Tailwind CSS** – Utility-first CSS framework for styling.
* **Jinja2** – Template engine for rendering HTML.
* **Requests** – Python library for HTTP requests (fetching weather data).

---

## **License**

MIT License – feel free to use and modify!
