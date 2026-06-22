# ⚡ Energy Load Forecasting & Smart Grid Optimization

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.104+-green.svg)](https://fastapi.tiangolo.com)
[![React](https://img.shields.io/badge/React-18+-61DAFB.svg)](https://reactjs.org)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

![Energy Dashboard](https://via.placeholder.com/800x400?text=Energy+Forecast+Dashboard)

## 🎯 Project Vision

**Smart Energy Management** through AI-powered forecasting and optimization. This project combines state-of-the-art machine learning with intuitive visualization to help energy providers and consumers make data-driven decisions.

> **"Predict today, power tomorrow"**

## ✨ Key Features

### 🔮 Multi-Model Forecasting
- **ARIMA**: Traditional time-series analysis
- **LSTM**: Deep learning for complex patterns
- **Gradient Boosting**: Ensemble method for accuracy
- **Ensemble Voting**: Combined predictions for better results

### ⚡ Smart Grid Optimization
- Real-time grid monitoring
- Peak load prediction (up to 7 days)
- Demand response strategies
- Load balancing recommendations

### 🌱 Carbon Footprint Analysis
- Carbon intensity tracking
- Emission reduction suggestions
- Renewable energy integration
- Sustainability reporting

### 🤖 AI-Powered Insights
- Natural language insights via Gemini API
- Automated alerts and recommendations
- Interactive Q&A about energy data
- Report generation

### 📊 Interactive Dashboard
- Real-time consumption visualization
- Model performance comparison
- Historical trends analysis
- Exportable reports (PDF/CSV)

## 🏗️ System Architecture

## 🚀 Quick Start

### Prerequisites
- Python 3.9+
- Node.js 16+
- Git
- Docker (optional)

### Installation

#### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/energy-forecast-smart-grid.git
cd energy-forecast-smart-grid

cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt

# Setup environment variables
cp .env.example .env
# Edit .env with your configurations

# Initialize database
cd ../database
python init_db.py
python seed_data.py

cd ../frontend
npm install
cp .env.example .env
