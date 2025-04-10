# FastAPI Docker CI/CD

Ce projet est une démo d'une API FastAPI conteneurisée avec Docker et intégrée à un pipeline CI/CD via GitHub Actions.

## ⚙️ Stack utilisée
- FastAPI (Python)
- Docker
- GitHub Actions (CI/CD)

## 🚀 Lancer en local

```bash
docker build -t fastapi-app .
docker run -d -p 8000:8000 fastapi-app
