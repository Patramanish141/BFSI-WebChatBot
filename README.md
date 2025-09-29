# BFSI Loan-sales Agent

Simple starter repo for the BFSI Web Chatbot project (Day0).

## Team
- Member A — Manish (Backend & Orchestration)
- Member B — Hrishikesh (Data & KYC)
- Member C — Pratyasha (Underwriting & Business Logic)
- Member D — Rishabh (Frontend, Demo & Slides)

## What is included
- `backend/main.py` — minimal FastAPI health endpoint
- `frontend/app.py` — minimal Streamlit app
- `data/applicants.csv` — sample applicants data (6 rows)
- `.gitignore` — recommended ignores
- `requirements.txt` — suggested packages

## How to run (simple)
1. Install packages globally (skip venv):
```
pip install -r requirements.txt
```
2. Start backend (in one terminal):
```
python -m uvicorn backend.main:app --reload
```
3. Start frontend (in another terminal):
```
streamlit run frontend/app.py
```
Open Streamlit UI in browser and test the API at http://127.0.0.1:8000/health
