# Contributing to TrendVibe AI

Thank you for your interest in contributing! TrendVibe AI welcomes developers,
designers, and researchers who want to help build the future of AI-driven
content creation.

---

## 📌 Codebase Structure
TrendVibe AI uses a hybrid architecture:

- **Next.js (frontend)**
- **Node.js API Gateway**
- **Python FastAPI (AI workers)**
- **PostgreSQL + pgvector**
- **Redis cache**
- **Scrapers + AI models (proprietary)**

Refer to the repository structure in `/docs/REPO_STRUCTURE.md`.

---

## ⚠️ Proprietary Code
The following folders are **not open for contributions** without approval:
- `/core-ai/`
- `/scrapers/`
- `/prediction-engine/`
- `/internal/`

These contain proprietary models and logic.

---

## 🧩 Allowed Areas for Contribution
You are welcome to contribute to:

### ✔ Frontend (Next.js, UI, components)
- dashboards  
- trend cards  
- script generator UI  
- onboarding  
- landing page  

### ✔ Backend (Node.js API)
- routing  
- input validation  
- rate limiting  
- error handling  

### ✔ FastAPI Worker
- non-proprietary utilities  
- job queuing  
- log handling  

### ✔ Documentation
- README improvements  
- API docs  
- examples  

---

## 🧪 Pull Request Guidelines
1. Fork the repo and create a feature branch.
2. Ensure TypeScript types are clean (no `any` unless justified).
3. Run formatting:
   - `npm run lint` (frontend)
   - `npm run format`
4. Write clear commit messages:
   - `feat: add trend card component`
   - `fix: improve error response structure`
5. Open a PR with:
   - description  
   - screenshots (if UI)  
   - checklist  

---

## 📬 Communication
Major discussions happen via:
- GitHub Issues  
- Discord server (coming soon)  

Thanks again for helping build TrendVibe AI!
