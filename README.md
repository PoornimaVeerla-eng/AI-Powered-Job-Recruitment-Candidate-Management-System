# AI-Powered-Job-Recruitment-Candidate-Management-System
# 🎯 AI Recruitment System

> **Student Project by Poornima Veerla**
> A complete AI-powered recruitment platform — Resume Parsing, Candidate Matching, and Smart Hiring Workflow

![Project Status](https://img.shields.io/badge/status-complete-success)
![Python](https://img.shields.io/badge/python-3.10+-blue)
![License](https://img.shields.io/badge/license-MIT-green)

---

## 📖 About the Project

This project automates the recruitment lifecycle using AI and NLP. It parses resumes, extracts key candidate info, ranks candidates against job descriptions using semantic similarity, and provides a clean dashboard for recruiters.

Built end-to-end across **5 phases** — Requirements, Backend, UI/UX, Data & Testing, and Deployment.

---

## 🗺️ Project Roadmap (5 Phases)

| Phase | Title | Status | Documentation |
|-------|-------|--------|---------------|
| 1 | Requirement Analysis & Planning | ✅ Done | [phase1-requirements.md](docs/phase1-requirements.md) |
| 2 | Backend Development & Configuration | ✅ Done | [phase2-backend.md](docs/phase2-backend.md) |
| 3 | UI/UX Development & Customization | ✅ Done | [phase3-uiux.md](docs/phase3-uiux.md) |
| 4 | Data Migration, Testing & Security | ✅ Done | [phase4-data-testing.md](docs/phase4-data-testing.md) |
| 5 | Deployment, Documentation & Maintenance | ✅ Done | [phase5-deployment.md](docs/phase5-deployment.md) |

👉 **Full index of all code links:** [CODE_LINKS.md](CODE_LINKS.md)
👉 **Visual roadmap:** [ROADMAP.md](ROADMAP.md)

---

## ⚡ Quick Start

```bash
git clone https://github.com/PoornimaVeerla-eng/ai-recruitment-system.git
cd ai-recruitment-system
pip install -r src/requirements.txt
python -m spacy download en_core_web_sm
python src/main.py
```

Open browser → `http://localhost:8000`

---

## ✨ Features

- 📄 Resume parsing (PDF & DOCX)
- 🧠 AI-powered candidate ↔ job matching (semantic similarity)
- 📊 Recruiter dashboard with ranked candidates
- 🔍 Skill gap analysis
- 💾 Database storage (SQLite/MongoDB)
- 📥 CSV export of shortlist
- 🎨 Clean responsive UI

---

## 🛠️ Tech Stack

**Backend** → Python · FastAPI · spaCy · sentence-transformers
**Frontend** → HTML · CSS · JavaScript
**Database** → SQLite (dev) / MongoDB (prod)
**AI** → all-MiniLM-L6-v2 embedding model
**Deployment** → Docker · Docker Compose

---

## 📁 Folder Structure

```
ai-recruitment-system/
├── README.md
├── ROADMAP.md
├── CODE_LINKS.md
├── LICENSE
├── .gitignore
├── src/                   # Backend code
├── frontend/              # UI files
├── docs/                  # Phase documentation
├── data/                  # Sample data
├── tests/                 # Unit tests
├── deployment/            # Docker configs
└── assets/                # Logo & images
```

---

## 👩‍🎓 Author

**Poornima Veerla**
GitHub: [@PoornimaVeerla-eng](https://github.com/PoornimaVeerla-eng)

---

## 📜 License

MIT — see [LICENSE](LICENSE)
"
