# Career Catalyst 🚀

**AI-Powered Talent Management Ecosystem**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Next.js Version](https://img.shields.io/badge/next.js-14.2-blue)
![Python Version](https://img.shields.io/badge/python-3.11-blue)


## 🌟 Features

### **Recruiter Portal** 👔
- AI-Powered Candidate Matching Engine
- Automated Resume Ranking System
- Real-time Applicant Dashboard
- Collaborative Hiring Workflows
- Interview Scheduling & Feedback Management
- Diversity Analytics & Bias Detection

### **Employee Portal** 👩💻
- Smart Resume Builder with AI Optimization
- Personalized Job Recommendations
- Application Tracking System (ATS)
- Cover Letter Generator with AI Detection
- Skill Gap Analysis & Learning Recommendations
- Salary Benchmarking & Negotiation Coach

## 🛠 Tech Stack

**Frontend:**
- `Next.js 14` (React Framework)
- `Node.js 20` (Runtime)
- `Firebase` (Authentication & Realtime DB)
- `Tailwind CSS` (Styling)


**Backend Services:**
- `Python Flask` (REST API)
- `Google Gemini Pro` (AI Analysis)
- `Firebase Functions` (Serverless Backend)
- `PyPDF` (PDF Processing)
- `Redis` (Caching)
deployment backend: https://resume-checker-3fh2.onrender.com

**AI/ML:**
- Google Gemini NLP Models
- Custom Recommendation Engine
- Semantic Resume-JD Matching
- Bias Detection Algorithms
- Predictive Hiring Analytics

**Infrastructure:**
- Firebase Hosting (Web Deployment)
-
- Render
-

## 🚀 Installation

1. **Clone Repositories**
```bash
# Backend (Flask)
git clone https://github.com/mohdaftab011/resume-checker.git

# Frontend (Next.js)
git clone https://github.com/lytcode404/fontend.git


# Backend .env
GOOGLE_API_KEY=your_gemini_key
FIREBASE_CONFIG={...}

# Frontend .env.local
NEXT_PUBLIC_FIREBASE_CONFIG={...}
API_ENDPOINT=http://localhost:8000



# Backend
cd career-catalyst-backend
pip install -r requirements.txt

# Frontend
cd ../fontend
npm install
Run Development Servers


# Start Flask backend (Port 8000)
flask run --port=8000

# Start Next.js frontend (Port 3000)
npm run dev
