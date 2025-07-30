# CVInsight: AI-Powered Resume Analyzer & Job Matcher

CVInsight is an open-source, web-based application built to help job seekers and career switchers get actionable insights from their CVs and understand their job fit for various roles. Leveraging modern Python-backed AI/NLP technology, it extracts, analyzes, and recommends roles and provides transparent matching with job descriptions—all for free.

## 🚀 Features

- **Upload Your CV** (PDF/Word)  
  Receive instant AI analysis and recommendations for suitable job roles and fields based on your skills and experiences.

- **CV-Job Description Matching**  
  Upload your CV and a job description to:
    - Get a **match percentage**
    - Receive **detailed, actionable feedback** on alignment and gaps between your CV and the job requirements

- **AI-Powered Analysis**  
  Uses free open-source models (spaCy, Hugging Face Transformers, sentence-transformers) for:
    - Named entity recognition (skills, experience, education)
    - Semantic similarity and skill/keyword overlap
    - Transparent, natural-language recommendations

- **End-to-End Workflow**  
  Simple, responsive React frontend + fast Python/FastAPI backend  
  Free-tier hosting and databases for a zero-cost MVP

## 🧑💻 Intended Users

- **Job seekers:** Understand and improve job fit for targeted roles.
- **Recent graduates/career switchers:** Discover alternate fields and get unbiased resume feedback.
- **Anyone wanting to tailor their resume** with AI support.

## 🛠️ Technologies & Stack

| Area        | Technology/Tool                        |
|-------------|----------------------------------------|
| Frontend    | React.js, Tailwind CSS, React Router   |
| Backend     | Python, FastAPI                        |
| AI/NLP      | spaCy, Hugging Face Transformers, sentence-transformers |
| Parsing     | pdfplumber (PDF), python-docx (Word)   |
| Database    | Supabase (PostgreSQL) or MongoDB Atlas |
| Deployment  | Netlify/Vercel (frontend), Render/Fly.io (backend) |
| Testing     | Pytest, Jest, Cypress                  |

## 🗺️ Development Roadmap

**Weeks 1–3:**  
- Requirement analysis, architecture design, project setup  
- UI/UX wireframes and frontend bootstrapping

**Weeks 4–6:**  
- Build frontend authentication and upload/dashboard pages  
- Develop FastAPI backend, document parsing and NER pipeline

**Weeks 7–9:**  
- Finalize NER, build job recommendation, DB design/migration  
- Integrate and test semantic similarity models

**Weeks 10–12:**  
- Refine outputs, full-stack and API testing  
- Setup CI/CD, deployment, monitoring, and documentation


