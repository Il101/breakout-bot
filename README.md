# Breakout Bot

![Python](https://img.shields.io/badge/python-3.11+-blue.svg)
![React](https://img.shields.io/badge/React-Frontend-61DAFB?logo=react)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-009688?logo=fastapi)
![License](https://img.shields.io/badge/license-MIT-green.svg)

Full-stack crypto trading system for breakout strategies with API, web UI, and automation scripts.

## Features

- 4 strategy presets for different market conditions
- Multi-stage market scanning and scoring
- Signal generation (momentum + retest)
- Risk management and position lifecycle controls
- REST API + WebSocket support
- React dashboard for monitoring and control

## Quick Start

```bash
git clone https://github.com/Il101/breakout-bot.git
cd breakout-bot
pip install -r requirements.txt
cd frontend && npm install && cd ..
chmod +x start.sh stop.sh status.sh
./start.sh
```

## Local Access

- Frontend: `http://localhost:5173`
- API: `http://localhost:8000`
- API docs: `http://localhost:8000/docs`

## Main Commands

```bash
./status.sh
./stop.sh
python3 -m breakout_bot.cli.main presets
```

## Tech Stack

- Backend: Python, FastAPI
- Frontend: React, Vite
- Data: WebSocket real-time streams
- Ops: Bash scripts for process management

## Disclaimer

For educational and research purposes. Always test safely.

## License

MIT
