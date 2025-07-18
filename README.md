# Airplane Data Dashboard

A simple, high-performance airplane tracking dashboard.

- **C++**: Ingests and processes live airplane data
- **Python (FastAPI)**: Serves the processed data over HTTP API endpoints
- **Frontend  will decide later

---

## Tech Stack

- **Backend Ingest:** C++
- **Backend API:** Python 3.x with FastAPI
- **Frontend:** will decide later
- **Bridge:** pybind11 or sockets (for C++ ↔ Python communication)

---

## API Endpoints

| Method | Endpoint            | Description                            |
|--------|---------------------|----------------------------------------|
| GET    | `/api/airplanes`    | Get current airplane positions/data    |
| GET    | `/api/airplanes/{id}` | Get details about a specific airplane  |
| GET    | `/api/metrics`      |  Return stats/metrics        |
| WS     | `/ws/airplanes`     |  Real-time airplane updates  |

---

## Example API Usage

---

## Requirements

- C++17+ toolchain
- Python 3.8+
- FastAPI, Uvicorn
- pybind11 (if using direct C++/Python bindings)
---


