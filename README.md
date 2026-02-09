
# teamsystem-backend-demo
# TeamSystem Backend Sample (FastAPI)

A minimal FastAPI backend service with health check endpoint and test coverage.

## Tech Stack
- Python 3.11
- FastAPI
- Uvicorn
- Pytest

## API Endpoints

- GET /health  
  Health check endpoint

- GET /items  
  Returns item list

- POST /items  
  Creates a new item


## Run locally
```bash
source .venv/bin/activate
uvicorn app.main:app --reload --port 8000

>>>>>>> 189afb2 (Add FastAPI health endpoint with pytest coverage)
