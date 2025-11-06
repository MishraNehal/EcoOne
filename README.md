# EcoOne / Saarthi.AI-main

This repository contains a FastAPI backend for municipal services (authentication, user management, grievance system, voice/twilio integrations, and more).

Quick start

1. Create & activate a Python virtual environment:

```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
```

2. Install dependencies:

```powershell
pip install -r requirements.txt
```

3. Add a `.env` file in the repository root with required environment variables (see `app/config.py` and `docs/frontend_api.md`).

4. Run the app:

```powershell
uvicorn main:app --host 0.0.0.0 --port 3000 --reload
```

Docs
- See `docs/frontend_api.md` for API endpoint documentation and frontend integration notes.

License
- Add a LICENSE file if you intend to make this project public.
# EcoOne-
