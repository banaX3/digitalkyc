# digitalkyc
# Digital KYC — Reduce Drop-Off Prototype

Small prototype demonstrating a digital KYC onboarding flow with:
- Document upload & validation
- Duplicate detection (checksum)
- Quality checks (blurriness, resolution)
- Simulated KYC server latency & rejections
- Funnel metrics & failure breakdown

## Tech stack
- Backend: Python Flask + Pillow
- Frontend: static HTML/JS (fetch API)

## Run locally
1. Create virtualenv:
   ```bash
   python -m venv venv
   source venv/bin/activate   # or venv\Scripts\activate on Windows
   cd backend
   pip install -r requirements.txt
   python app.py
