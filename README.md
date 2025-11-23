
# Smart Attendance System — Project Scaffold

This repository contains a ready-to-launch **scaffold** for a Smart Attendance System using:

- Frontend: **Expo (React Native)**
- Backend: **FastAPI** + **OpenCV** + **face_recognition**
- Database: **MongoDB**
- Features: QR scanning, GPS geofencing, face recognition, real-time attendance

> NOTE: This scaffold contains well-organized placeholders and templates (README, env examples, Docker, API stubs, and frontend structure).
> You asked *not* to include full implementation code — so files are templates and TODOs to fill with your actual logic.

## Contents
- `backend/` — FastAPI backend templates and Dockerfile
- `frontend/` — Expo app skeleton (React Native) and sample screens
- `infra/` — nginx config and mongo-init script
- `scripts/` — utility scripts (QR generation, encoding pipeline)
- `docs/` — architecture and API spec templates
- `docker-compose.yml`, `.env.example`, `.gitignore`

## Quick start (development)
1. Copy `.env.example` to `.env` and edit values.
2. Start MongoDB (docker-compose does this for you): `docker compose up -d mongo`
3. Start backend:
   - Enter `backend/`, create a virtualenv, install `requirements.txt`, then run `uvicorn app.main:app --reload --host 0.0.0.0 --port 8000`
4. Start frontend:
   - Enter `frontend/`, run `npm install`, then `expo start`
5. See `docs/architecture.md` and `docs/api_spec.md` for endpoint and flow descriptions.

## Deliverables in this scaffold
- Project structure with clear TODOs.
- Dockerfiles + docker-compose service templates.
- API endpoint stubs and models (placeholders with descriptions).
- Frontend screen skeletons and service layer placeholders.
- Face-encoding pipeline script outline and storage guidance.

