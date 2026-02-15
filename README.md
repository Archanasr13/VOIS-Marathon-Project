# Unified Cybersecurity Simulation & Threat Intelligence Platform

A state-of-the-art, full-stack cybersecurity empowerment platform designed to transform organizational security culture. This platform combines high-fidelity phishing simulations, AI-driven awareness training, gamified health tracking, and professional-grade threat intelligence tools.

---

## 🌟 Premium Features

### 🛡️ Core Simulation & Training
- **High-Fidelity Phishing Simulations**: Realistic email scenarios covering various difficulty levels (Easy to Hard)
- **Role-Based Simulations**: Tailored phishing attempts specific to departments (HR, Finance, IT, Marketing)
- **AI-Generated Awareness Videos**: Dynamic video content providing positive reinforcement and educational breakdown of threats
- **Adaptive Quizzes**: Interactive knowledge checks with instant feedback and detailed explanations
- **Digital Certificates**: Secure PDF certificates generated upon successful completion of training modules

### 🧪 Advanced Threat Intelligence (SWHI)
- **Deep Domain Analysis**: Real-time investigation of suspicious URLs
- **Infrastructure Fingerprinting**: DNS record auditing, SSL certificate inspection, and CDN detection
- **Geographic Attribution**: Interactive map showing hosting locations and ASN information
- **AI Threat Prediction**: Machine learning model (Random Forest) assessing domain risk with confidence scores
- **Network Path Visualization**: Visual representation of the domain's network infrastructure

### 📊 Intelligence & Analytics
- **Cyber Health Dashboard**: Premium visualization of personal and organizational security posture
- **Real-Time Threat Feed**: Live stream of global cybersecurity threats with severity filtering
- **Gamified Leaderboard**: Competitive ranking system with achievements, streaks, and department-wise standings
- **Admin Command Center**: Comprehensive overview of interaction rates, quiz performance, and risk distribution across the organization

---

## 🛠️ Technology Stack

### Backend (Python/Flask)
- **Engine**: Flask with blueprint-based modular architecture
- **Database**: SQLAlchemy ORM with SQLite for reliable local data storage
- **Security**: Password hashing (Werkzeug), CORS protection, and input sanitization
- **Analysis**: Specialized modules for DNS (dnspython), SSL, and WHOIS analysis
- **Machine Learning**: Scikit-Learn based threat classifier with Joblib for model persistence

### Frontend (React/Modern CSS)
- **Framework**: React 18+ with functional components and hooks
- **Styling**: TailwindCSS for a premium "Glassmorphism" aesthetic
- **Animations**: Framer Motion for smooth transitions and micro-interactions
- **Data Visualization**: Chart.js for interactive analytics and Leaflet for geographic mapping
- **Icons**: Lucide-React for professional, consistent iconography

---

## 📁 System Architecture

```
VOIS Final/
├── Project/
│   ├── backend/
│   │   ├── routes/             # Feature-specific API blueprints
│   │   ├── swhi/               # Core domain analysis engine
│   │   │   ├── ml/             # ML models and predictors
│   │   │   └── analyzer.py     # Heuristic analysis logic
│   │   ├── models.py           # Database schema definitions
│   │   └── app.py              # Application entry point & seed logic
│   ├── frontend/
│   │   ├── src/
│   │   │   ├── components/     # High-reusability UI elements
│   │   │   ├── pages/          # Feature-rich page components
│   │   │   │   ├── SWHI/       # Domain analysis module
│   │   │   │   └── ...         # Dashboards, Feeds, Simulations
│   │   │   ├── services/       # API integration layer
│   │   │   └── App.js          # Routing and Global State
│   └── instance/               # Local database storage
```

---

## 🚀 Getting Started

### 1. Backend Setup

```bash
cd backend
python -m venv venv

# On Windows:
venv\Scripts\activate

# On Unix:
source venv/bin/activate

pip install -r requirements.txt
python app.py
```

The backend server initializes at `http://localhost:5000` and automatically seeds the database with demo users and simulations.

### 2. Frontend Setup

```bash
cd frontend
npm install
npm start
```

The dashboard becomes available at `http://localhost:3000`.

---

## 📈 Platform Ecosystem

### User Workflow
1. **Interactive Learning**: Watch AI-generated videos and take adaptive quizzes to build foundational knowledge
2. **Simulation Training**: Interact with realistic simulations and receive immediate "Cyber Coach" feedback
3. **Daily Health Check**: Monitor your progress via the Cyber Health Dashboard and aim for the top of the Leaderboard
4. **Active Defense**: Use the SWHI tool to verify any suspicious emails or links encountered in the real world

### Administrative Oversight
- **Performance Audit**: Track which departments are most vulnerable to specific attack vectors
- **Resource Allocation**: Identify users needing additional training based on their risk profile
- **Threat Awareness**: Monitor the real-time feed to stay ahead of emerging campaigns targeting your industry

---

## 🛡️✨

**Unified Cybersecurity Simulation & Threat Intelligence Platform**

*Empowering individuals, securing organizations.*
=======
# VOIS-Marathon-Project
VOIS Hackathon Project Submission – Includes application code, problem statement, and project presentation.
>>>>>>> a86d987d8f6bc6adf7739c43a4a69382c6164e6e
