# EduAid – AI-Powered Learning Roadmap Generator

<div align="center">
  <img src="https://i.imgur.com/your-demo-image.png" alt="EduAid Screenshot" width="80%"/>
  <p>
    <em>Transform your learning journey with AI-curated roadmaps.</em>
  </p>
  <p>
    <a href="#-live-demo">View Demo</a> •
    <a href="#-features">Features</a> •
    <a href="#-tech-stack">Tech Stack</a> •
    <a href="#%EF%B8%8F-getting-started">Get Started</a> •
    <a href="#-license">License</a>
  </p>
</div>

---

## 🌟 Introduction
*EduAid* solves the modern learner's dilemma: "I want to learn X, but where do I start?" By leveraging Gemini AI, it generates *personalized learning roadmaps* with milestones, exercises, and free resources tailored to your skill level.

*Built for*:
- Self-taught developers 👩💻
- Career switchers 🔄
- Students & lifelong learners 🎓

---

## 🎯 Problem Statement
### The Chaos of Self-Directed Learning
| Problem | EduAid's Solution |
|---------|------------------|
| ❌ *Too many resources* overwhelm beginners | ✅ *AI-curated* high-quality content |
| ❌ No clear *learning path* | ✅ *Milestone-based roadmap* |
| ❌ Hard to *track progress* | ✅ Interactive *checklist system* |
| ❌ Generic *one-size-fits-all* courses | ✅ *Personalized* by skill level (Beginner/Intermediate/Advanced) |

---

## 🚀 Features
### Core Features
| Feature | Description | Preview |
|---------|-------------|---------|
| *AI Roadmap Generator* | Gemini-powered step-by-step plans | ![Roadmap GIF]() |
| *Resource Integration* | Auto-suggests free YouTube videos, GitHub repos, and docs | ![Resources GIF]() |
| *Progress Tracker* | Checklist with completion stats | ![Progress GIF]() |

### Premium Features (Optional)
- 🔍 Job listings integration
- 📚 Udemy course recommendations
- 🗂 Project portfolio builder

---

## 🧰 Tech Stack
### Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![DaisyUI](https://img.shields.io/badge/DaisyUI-5A0EF8?style=for-the-badge&logo=daisyui&logoColor=white)

### Backend
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Gemini API](https://img.shields.io/badge/Gemini_AI-4285F4?style=for-the-badge&logo=google&logoColor=white)

### Deployment
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

---

## ⚡ Getting Started
### Prerequisites
- Node.js ≥18.x
- Gemini API key

### Installation
```bash
# Clone repository
git clone https://github.com/your-username/eduaid.git

# Install dependencies
cd frontend && npm install
cd ../backend && npm install

# Configure environment variables
echo "GEMINI_API_KEY=your_key_here" > backend/.env
