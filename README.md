# AeroPulse AI

**AI-powered aircraft engine predictive maintenance dashboard** — synthetic telemetry demonstration only.

⚠️ **DISCLAIMER:** This system uses completely synthetic data and simplified ML models. It is **NOT suitable for real aircraft operational decisions**. This is a technical proof-of-concept only.

## Features

- **Real-time telemetry dashboard** — Live engine metrics (temp, pressure, vibration, RPM)
- **Anomaly detection** — Flags unusual engine behavior
- **Health score** — 0–100 engine health visualization
- **Remaining useful life (RUL)** — Estimated operating hours remaining
- **AI explanations** — Plain-English maintenance recommendations
- **Interactive charts** — Vite + React with WebSocket live updates

## Quick Start

### Prerequisites
- Docker & Docker Compose
- Node.js 18+ (if running locally without Docker)
- Python 3.9+ (if running locally without Docker)

### Run with Docker
```bash
docker-compose up
