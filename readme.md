<div align="center">

# 💼 TalentCraft
<em>Discover TalentCraft, the ultimate AI-driven career companion that helps job seekers optimize their resumes, uncover skill gaps, and prepare smarter for interviews.
AI-powered resume analysis, smart job matching, and interview practice — all in one.</em>

<p>
  <img src="/screenshot/home.png" alt="TalentCraft Banner" width="900" />
</p>

<p>
  <a href="https://react.dev/">
    <img alt="React" src="https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white" />
  </a>
  <a href="https://www.djangoproject.com/">
    <img alt="Django" src="https://img.shields.io/badge/Django-5.2-092E20?logo=django&logoColor=white" />
  </a>
  <a href="https://www.django-rest-framework.org/">
    <img alt="DRF" src="https://img.shields.io/badge/DRF-3.x-ff1709?logo=django&logoColor=white" />
  </a>
  <a href="https://tailwindcss.com/">
    <img alt="Tailwind" src="https://img.shields.io/badge/Tailwind-3.x-38BDF8?logo=tailwindcss&logoColor=white" />
  </a>
  <a href="https://www.postgresql.org/">
    <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-DB-4169E1?logo=postgresql&logoColor=white" />
  </a>
  <a href="https://jwt.io/">
    <img alt="JWT" src="https://img.shields.io/badge/JWT-Auth-000000?logo=jsonwebtokens&logoColor=white" />
  </a>
  <a href="https://github.com/romilmonpara/TalentCraft-careertech-resumebuilder-jobmatcher/stargazers">
    <img alt="GitHub Stars" src="https://img.shields.io/github/stars/romilmonpara/TalentCraft-careertech-resumebuilder-jobmatcher?style=social" />
  </a>
  <a href="https://github.com/romilmonpara/TalentCraft-careertech-resumebuilder-jobmatcher/forks">
    <img alt="GitHub Forks" src="https://img.shields.io/github/forks/romilmonpara/TalentCraft-careertech-resumebuilder-jobmatcher?style=social" />
  </a>
  <a href="https://github.com/romilmonpara/TalentCraft-careertech-resumebuilder-jobmatcher/issues">
    <img alt="GitHub Issues" src="https://img.shields.io/github/issues/romilmonpara/TalentCraft-careertech-resumebuilder-jobmatcher" />
  </a>
  <a href="https://github.com/romilmonpara/TalentCraft-careertech-resumebuilder-jobmatcher/pulls">
    <img alt="GitHub PRs" src="https://img.shields.io/github/issues-pr/romilmonpara/TalentCraft-careertech-resumebuilder-jobmatcher" />
  </a>
  <a href="./LICENSE">
    <img alt="License" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
</p>

<p>
  <a href="#live-demo">Demo</a> •
  <a href="#overview">Docs</a> •
  <a href="https://github.com/romilmonpara/TalentCraft-careertech-resumebuilder-jobmatcher/issues">Issues</a>
</p>

</div>

## 📌 Overview

TalentCraft is a full‑stack platform that analyzes resumes, extracts skills and experience, and compares them against job descriptions to produce a match score with actionable feedback. It also includes an HR interview practice assistant and a simple resume builder to generate polished PDFs.

<div align="center">
  <img src="/screenshot/login.png" alt="TalentCraft Login" width="700" />
</div>

## 🎮 Live Demo

- Demo: coming soon
- Video: coming soon

## 📚 Table of Contents

- **Features**
- **Tech Stack**
- **Architecture**
- **API Endpoints**
- **Frontend Structure**
- **Backend Structure**
- **Algorithm & Logic**
- **Data Models**
- **Installation**
- **Usage Examples**
- **Roadmap**
- **Contributing**
- **Acknowledgements**
- **License**

## ✨ Features

### 🔍 Resume Analysis & Management
- Smart PDF parsing and structured extraction
- Multiple profile support and social profile detection
- Clean dashboard to review and fix parsed data

<div align="center">
  <img src="/screenshot/home.png" alt="Resume Dashboard" width="850" />
</div>

### 🎯 Job Matching
- Skill gap analysis and transparent match scoring
- Personalized, actionable improvement suggestions
- Clear visual indicators for quick assessment

### 🤖 HR Interview Practice
- 100+ curated HR interview questions with categories and search
- Interactive chatbot practice with instant feedback
- Pagination and progress tracking

<div align="center">
  <img src="/screenshot/chatbot.png" alt="HR Chatbot" width="850" />
  <p><em>Practice interviews with a conversational assistant</em></p>
</div>

<div align="center">
  <img src="/screenshot/interviewque.png" alt="Interview Questions" width="850" />
</div>

### 📄 Resume Builder
- ATS‑friendly templates and custom PDF generation
- Manage sections: experience, education, projects, skills
- Support for multiple entries and compact mini‑projects

### 👤 User Management
- Secure JWT auth and responsive account UI
- Profile selection to switch between resume profiles

### 🌐 Job Market Integration
- Real‑time job search via external APIs
- Match‑based job sorting and quick apply links

## 🧰 Tech Stack

- **Frontend**: React 19, React Router, Axios, Tailwind CSS
- **Backend**: Django 5.2, Django REST Framework, SimpleJWT
- **PDF & Parsing**: PyMuPDF (fitz), ReportLab
- **Database**: PostgreSQL
- **Other Tools**: Redis (optional), Regex‑based text analysis

<div align="center">
  <img alt="React" src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=white" />
  <img alt="React Router" src="https://img.shields.io/badge/React%20Router-CA4245?logo=reactrouter&logoColor=white" />
  <img alt="Axios" src="https://img.shields.io/badge/Axios-5A29E4?logo=axios&logoColor=white" />
  <img alt="Tailwind" src="https://img.shields.io/badge/Tailwind-38BDF8?logo=tailwindcss&logoColor=white" />
  <img alt="Django" src="https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white" />
  <img alt="DRF" src="https://img.shields.io/badge/DRF-ff1709?logo=django&logoColor=white" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white" />
  <img alt="Redis" src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white" />
</div>

## 🏗️ Architecture

Client‑server architecture:
- React SPA frontend
- Django REST API backend
- PostgreSQL database
- External job APIs for search and enrichment

<div align="center">
  <img src="/screenshot/roadmap.png" alt="System Overview" width="850" />
</div>

## 📊 API Endpoints

<details>
<summary><strong>Expand to view endpoints</strong></summary>

### Authentication
- `POST /api/signup/`
- `POST /api/login/`
- `POST /api/token/refresh/`
- `POST /api/password-reset/`

### Resume Management
- `POST /api/resumeupload/`
- `GET /api/profiles/`
- `GET /api/current-profile/`
- `POST /api/set-current-profile/`

### Job Matching
- `POST /api/match/match-job-description/`
- `GET /api/jobs/matching-jobs/`

### HR Interview Practice
- `GET /chatbot/hr-questions/`
- `GET /chatbot/start/`
- `POST /chatbot/next-question/`
- `GET /chatbot/random/`

### Resume Builder
- `POST /api/resume/generate/`

</details>

## 🖥️ Frontend Structure

```
ai_resume_matcher/frontend/
├── public/
│   ├── index.html
│   ├── logo.png
│   └── p.avif
├── src/
│   ├── api/
│   │   ├── axiosConfig.js
│   │   └── axiosInstance.js
│   ├── components/
│   │   ├── HRChatBot.jsx
│   │   ├── HRQuestionsPage.jsx
│   │   ├── PrivateRoute.js
│   │   └── PublicRoute.js
│   ├── pages/
│   │   ├── Assignments.jsx
│   │   ├── HRInterviewPractice.jsx
│   │   ├── Roadmap.jsx
│   │   ├── TrainingDashboard.jsx
│   │   ├── home.jsx
│   │   ├── jobmatch.jsx
│   │   ├── jobs.jsx
│   │   ├── landing.jsx
│   │   ├── me.jsx
│   │   ├── profile.jsx
│   │   ├── resumebuilder.jsx
│   │   ├── upload.jsx
│   │   ├── Progress.jsx
│   │   ├── Login.jsx
│   │   └── Signup.jsx
│   ├── App.jsx
│   ├── index.js
│   └── main.jsx
├── package.json
├── package-lock.json
├── vite.config.js
└── README.md
```

## 🔧 Backend Structure

```
ai_resume_matcher/backend/
├── manage.py
├── core/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
├── apps/
│   ├── users/
│   ├── match/
│   │   └── matching.py
│   ├── jobs/
│   ├── chatbot/
│   ├── resumes/
│   └── training/
├── media/
├── requirements.txt
└── db.sqlite3 (dev)
```

## 🧠 Algorithm & Logic

### Match Scoring Algorithm
1) Skill extraction for single‑ and multi‑word skills
2) Summary relevance and experience weighting
3) Score breakdown with targeted improvement hints

### Interview Chatbot Logic
1) Adaptive question flow and progress tracking
2) Keyword‑based answer evaluation with feedback
3) Suggestions to improve responses

<div align="center">
  <img src="/screenshot/chatbot.png" alt="Chatbot Flow" width="850" />
</div>

### Resume Builder Engine
1) Dynamic layout and pagination
2) Section prioritization for impact
3) Consistent visual hierarchy

## 💾 Data Models

### Profile Model
- User reference (ForeignKey)
- Personal info (name, email, phone)
- Resume sections (summary, skills, education, experience)
- Social links (LinkedIn, GitHub, website)
- Resume file & hash (duplicate detection)
- Current profile flag (Boolean)

### User Model (Extended)
- Standard Django user fields
- Email verification status
- Account creation date
- Last login tracking

### HR Questions Model
- Question ID, text, model answer
- Category classification, difficulty level

## 🧪 Installation & Setup

### Prerequisites
- Node.js 18+
- Python 3.10+
- PostgreSQL 12+

### Frontend
```bash
git clone https://github.com/romilmonpara/TalentCraft-careertech-resumebuilder-jobmatcher.git
cd TalentCraft-careertech-resumebuilder-jobmatcher/ai_resume_matcher/frontend
npm install
npm start
```

### Backend
```bash
cd ../backend
python -m venv venv
venv\Scripts\activate  # Windows
pip install -r requirements.txt

# .env configuration (create .env in backend root)
# Example keys:
# SECRET_KEY=your-secret
# DEBUG=true
# DB_NAME=resumatch
# DB_USER=postgres
# DB_PASSWORD=postgres
# DB_HOST=localhost
# DB_PORT=5432

python manage.py migrate
python manage.py runserver
```

## 🚀 Usage Examples

### Sign up / Login
<div align="center">
  <img src="/screenshot/signup.png" alt="Signup" width="420" />
  <img src="/screenshot/login.png" alt="Login" width="420" />
  
</div>

### Interview Practice
<div align="center">
  <img src="/screenshot/chatbot.png" alt="Chatbot" width="850" />
</div>

### Special Training
<div align="center">
  <img src="/screenshot/specialtraning.png" alt="Training" width="850" />
</div>

## 🗺️ Roadmap

- More job provider APIs (LinkedIn, Indeed, Greenhouse)
- ML‑assisted skill extraction and semantic scoring
- Multi‑theme UI (light/dark and high‑contrast)
- Resume templates marketplace and custom designer
- Internationalization and localization
- Docker dev environment and one‑click deploys

## 🤝 Contributing

We welcome contributions!
1) Fork the repo
2) Create a branch: `git checkout -b feat/amazing-feature`
3) Commit: `git commit -m "feat: add amazing feature"`
4) Push: `git push origin feat/amazing-feature`
5) Open a Pull Request

Don’t forget to ⭐ the repo if you find it useful!

## 🙏 Acknowledgements

- [PyMuPDF](https://github.com/pymupdf/PyMuPDF)
- [ReportLab](https://www.reportlab.com/)
- [Django REST Framework](https://www.django-rest-framework.org/)
- [SimpleJWT](https://github.com/jazzband/djangorestframework-simplejwt)
- [Tailwind CSS](https://tailwindcss.com/)
- [React](https://react.dev/)

## 📄 License

Licensed under the MIT License. See the [`LICENSE`](./LICENSE) file for details.

<div align="center">
  <br/>
  <strong>Made with ❤️ for job seekers everywhere</strong>
  <br/>
  ✨ Keep learning, keep shipping, keep growing ✨
</div>
