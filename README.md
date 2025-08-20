# Miroko
A collaborative drawing board

To run each commands:
# Backend:
cd backend
python -m venv .venv
.\.venv\Scripts\Activate
uvicorn main:app --reload --port 8000

# Frontend
cd frontend
cd app
npm run dev