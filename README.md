# 🚦 RoadSafe AI – Accident Severity Prediction & Risk Analysis

## 📌 Project Overview
RoadSafe AI is a data-driven web application designed to predict **road accident severity and risk levels** using historical accident data, weather conditions, road characteristics, and temporal factors.  
The system enables **proactive accident prevention** by identifying high-risk zones and conditions before accidents occur.

---

## ❗ Problem Statement
Road accidents continue to increase due to:
- Lack of predictive safety systems
- Reactive accident handling instead of preventive planning
- No unified platform combining weather and historical accident data

RoadSafe AI addresses these challenges by offering **AI-powered accident severity prediction and risk analysis**.

---

## 👥 Target Users (Personas)

### 🧑‍✈️ Traffic Police Officers
- Identify accident-prone zones
- Deploy checkpoints and preventive measures

### 🏛️ Government & Road Authorities
- Analyze accident trends
- Improve road infrastructure planning

### 🚗 Daily Commuters
- Avoid high-risk routes and timings
- Make safer travel decisions

---

## 🌟 Vision Statement
> *To reduce road accidents by enabling proactive, data-driven safety decisions through intelligent risk prediction.*

---

## 🎯 Key Features / Goals
- Accident severity prediction (Low / Medium / High)
- Weather-based risk analysis
- Accident hotspot visualization
- Historical trend analytics
- Authority dashboard for decision-making

---

## 📊 Success Metrics
- Prediction accuracy above 80%
- Reduced accident rates in identified hotspots
- Fast prediction response time (< 2 seconds)
- Adoption by traffic and civic authorities

---

## ⚠️ Assumptions & Constraints

### Assumptions
- Historical accident datasets are accurate and available
- Weather data can be fetched via APIs

### Constraints
- Accuracy depends on data quality
- Internet required for real-time data
- Limited scope due to academic timeline

---

## 🧩 User Stories (Summary)
- Predict accident severity using historical data
- Analyze accident risk based on weather
- View accident hotspots on a map
- Filter accidents by location and time
- Admin dashboard for authorities
- Secure backend APIs
- Containerized deployment using Docker

(Complete list available in GitHub Issues – 25 user stories implemented)

---

## 🧠 MoSCoW Prioritization

### Must Have
- Accident severity prediction
- Weather data integration
- Analytics dashboard
- Historical data processing

### Should Have
- Map-based visualization
- Trend analysis

### Could Have
- Route safety recommendations
- Alert notifications

### Won’t Have
- Mobile application
- Real-time IoT sensor integration

---

## 🏗️ System Architecture (High-Level)

Frontend (React)  
⬇  
Backend (Flask REST API)  
⬇  
ML Model (Severity Prediction)  
⬇  
Database (Accident & Weather Data)  
⬇  
Docker Container  
⬇  
Local / Cloud Deployment  

---

## 🌿 Branching Strategy
This project follows **GitHub Flow**:

- `main` → Stable production-ready code
- `feature-ml-model` → Machine learning features
- `feature-ui-dashboard` → Frontend dashboard features

All feature branches are merged into `main` via pull requests.

---

## 🐳 Docker Setup

### Prerequisites
- Docker Desktop installed
- Git installed

---

## 🚀 Quick Start – Local Development

```bash
# Build the Docker image
docker build -t roadsafe-ai .

# Run the container
docker run -p 5000:5000 roadsafe-ai
```

## 📁 Project Folder Structure

```text
roadsafe-ai/
│
├── backend/
│   ├── routes/
│   ├── models/
│   ├── services/
│   ├── utils/
│
├── frontend/
│   ├── public/
│   └── src/
│       ├── pages/
│       ├── components/
│       ├── services/
│       └── styles/
│
├── docker/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── docs/
│   └── screenshots/
│
└── .github/
    └── workflows/
```


