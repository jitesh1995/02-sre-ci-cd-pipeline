# 02-sre-ci-cd-pipeline

FastAPI microservice with tests, Dockerfile, and GitHub Actions CI pipeline for SRE/DevOps demonstration.

---

## 📌 Features
- FastAPI app with `/health` endpoint
- Unit tests with pytest
- Dockerfile for containerization
- GitHub Actions CI workflow (runs tests on push/PR)

---

## 🚀 Run locally (optional)
```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate
pip install -r requirements.txt
uvicorn app:app --reload

![CI](https://github.com/jitesh1995/02-sre-ci-cd-pipeline/actions/workflows/ci.yml/badge.svg)
