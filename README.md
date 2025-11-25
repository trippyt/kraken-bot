# Kraken Bot — Settings & Mode Persistence

## Quick start (local)
```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
uvicorn app.main:app --reload
BOT_API_URL=http://localhost:8000 streamlit run ui/dashboard.py
