# 🌦️ Weather REST API - FastAPI

---

## 📌 Description

This is a **Weather REST API** built with **FastAPI** in Python as part of the backend internship assessment for **AM SaleTech**.  
The API provides basic weather data for a given location, using a single GET endpoint. It follows RESTful design principles and is designed for simplicity, clarity, and performance.

---

## 🚀 Features

✔ Provides current weather information like temperature, humidity, and description  
✔ Uses asynchronous FastAPI server  
✔ Handles HTTP GET requests efficiently  
✔ Returns data in JSON format  
✔ Auto-generated interactive API documentation (Swagger UI)  
✔ Well-structured code suitable for beginners and interview demos  
✔ Easily extendable for real-time or dynamic data

---

## 🛠 Technologies Used

🔹 **Programming Language**: Python 3.10+  
🔹 **Web Framework**: FastAPI  
🔹 **Server**: Uvicorn (ASGI)  
🔹 **Data Format**: JSON  
🔹 **Tools**: Swagger UI, ReDoc, Postman (for testing)

---

## 📜 Usage Instructions

🔹 `GET /weather` → Get current weather info (e.g., temperature, humidity, description)

### 🔁 Sample Output

```json
{
  "location": "Cairo",
  "temperature": "35°C",
  "description": "Sunny",
  "humidity": "30%"
}
▶️ How to Run the Project
Install the required packages:

bash
Copy
Edit
pip install fastapi uvicorn
Run the API server:

bash
Copy
Edit
uvicorn server:app --reload
Access the API via browser:

🔹 Swagger UI → http://127.0.0.1:8000/docs

🔹 Main Endpoint → http://127.0.0.1:8000/weather

🎯 Suggested Improvements
Add support for querying real-time weather data from a third-party API

Allow users to input dynamic locations

Add error handling for invalid endpoints or missing data

Implement caching for performance optimization

Add unit testing and validation for production-readiness

Deploy to cloud (Render, Railway, Vercel, etc.)
