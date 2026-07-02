# Shipyard Backend Test

A minimal Flask API demonstrating JWT authentication and database connection patterns.

## Endpoints
- `GET /health` – Health check
- `POST /login` – Authenticate and receive JWT
- `GET /protected` – Access protected resource (requires Bearer token)

## Setup
```bash
pip install -r requirements.txt
python app.py
