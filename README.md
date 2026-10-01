# AI-Powered Smart Agriculture Monitoring and Crop Disease Prediction Platform

## 📌 Project Overview

An AI-based smart agriculture platform that helps farmers monitor crop health, detect diseases from leaf images, analyze current environmental conditions, and receive explainable recommendations for better crop management.

## 🎯 Objectives

- Detect crop diseases using AI-based leaf image analysis.
- Automatically retrieve current weather conditions using location.
- Analyze temperature, humidity, rainfall, cloud cover, wind, and related environmental factors.
- Provide explainable recommendations for irrigation, fertilizer, and disease management.
- Store prediction and recommendation history.
- Provide a dashboard for crop health, alerts, weather, and trends.

## 🏗️ System Workflow

```text
Farmer
  ↓
Location + Leaf Image
  ↓
Automatic Weather Retrieval
  ↓
AI Crop Disease Prediction
  ↓
Environmental Context Analysis
  ↓
Explainable Recommendations
  ↓
Database Storage
  ↓
Dashboard & History
```

## 🧩 Main Modules

1. **User Module** – Login and farmer interaction.
2. **Leaf Image Module** – Upload/capture crop leaf images.
3. **Weather Module** – Automatically retrieves current weather using location.
4. **AI Disease Prediction** – Identifies crop disease from leaf images.
5. **Recommendation Module** – Generates explainable farming recommendations.
6. **Dashboard Module** – Displays crop health, predictions, alerts, weather and trends.
7. **Database Module** – Stores users, predictions and recommendation history.

## 🛠️ Technology Stack

| Component | Technology |
|---|---|
| Frontend | React, Vite, Tailwind CSS |
| Backend | FastAPI, Python |
| AI/ML | TensorFlow, MobileNetV2 |
| Weather | Open-Meteo API |
| Database | PostgreSQL |
| Containerization | Docker |
| Version Control | Git & GitHub |

## 🤖 AI Methodology

The system uses transfer learning with **MobileNetV2** for crop disease classification.

Input:
- Crop leaf image
- Environmental/weather information

Output:
- Predicted crop disease
- Confidence score
- Environmental interpretation
- Explainable recommendations

## 🌦️ Environmental Monitoring

Weather information is automatically obtained based on the user's location. The system considers parameters such as:

- Temperature
- Humidity
- Rain/precipitation
- Cloud cover
- Wind
- Radiation/light-related conditions

Soil moisture can be integrated later using IoT sensors.

## 🗄️ Database

PostgreSQL stores:

- User information
- Disease predictions
- Confidence values
- Environmental conditions
- Recommendations
- Prediction history

## 🚀 Project Execution

```bash
docker compose up --build -d
```

The project consists of separate frontend, backend, AI-service, and database components.

## 📂 Project Structure

```text
AI-Smart-Agriculture/
├── src/
│   ├── frontend/
│   ├── backend/
│   ├── ai-service/
│   └── database/
├── data/
├── docs/
├── results/
├── reports/
├── docker-compose.yml
├── README.md
└── .github/
```

## 🔮 Future Enhancements

- IoT-based soil moisture monitoring
- More crops and disease classes
- Mobile application
- AWS/cloud deployment
- Advanced explainable AI
- Real-time alerts and notifications

## 👥 Team

- **B. Vaishnavi** – 2420090026
- **S. Lahari Krishna** – 2420090055

**Academic Year:** 2026–2027  
