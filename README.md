# 🎲 Soc Ops: Social Bingo

### Turn Networking into a Game! 🚀

**Soc Ops** is a modern, interactive Social Bingo game designed for in-person mixers and networking events. Find people who match the fun questions on your board and be the first to get 5 in a row!

[![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)](https://fastapi.tiangolo.com/)
[![Python](https://img.shields.io/badge/Python-3.13+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Jinja2](https://img.shields.io/badge/Jinja2-B41717?style=for-the-badge&logo=jinja&logoColor=white)](https://jinja.palletsprojects.com/)

---

## ✨ Features

- **Dynamic Board Generation**: No two boards are the same! Questions are shuffled for every player.
- **Mobile-First Design**: Optimized for playing on your phone while you mingle.
- **Instant Bingo Check**: Automatically detects when you've won.
- **Interactive UI**: Powered by HTMX for smooth, no-refresh gameplay.

---

## 📸 Preview

![Social Bingo Home Page](/Users/vatsalp/.gemini/antigravity/brain/6aaf84a6-0467-4738-b45a-a0c2abb64210/social_bingo_home_page_1773785821533.png)

---

## 🕹 How to Play

1.  **Start Your Game**: Click "Start Game" to get your unique bingo board.
2.  **Find Matches**: Talk to people! If someone matches a square (e.g., "Has a cat"), tap that square.
3.  **Get 5 in a Row**: Mark five squares in a row (horizontal, vertical, or diagonal).
4.  **Win!**: The game will announce your Bingo!

---

## 📚 Lab Guide & Workshop

This project is part of the [GitHub Copilot Agent Lab](https://madebygps.github.io/vscode-github-copilot-agent-lab/).

| Part | Title |
|------|-------|
| [**00**](https://madebygps.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Overview & Checklist |
| [**01**](https://madebygps.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Setup & Context Engineering |
| [**02**](https://madebygps.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Design-First Frontend |
| [**03**](https://madebygps.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Custom Quiz Master |
| [**04**](https://madebygps.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Multi-Agent Development |

---

## 🛠 Setup & Development

### Prerequisites
- [Python 3.13+](https://www.python.org/downloads/)
- [uv](https://docs.astral.sh/uv/) or `pip`

### Install Dependencies
```bash
uv sync 
# OR
python3 -m venv .venv && source .venv/bin/activate && pip install -e .
```

### Run Locally
```bash
uv run uvicorn app.main:app --reload
```
Visit: [http://localhost:8000](http://localhost:8000)

### QA Tools
```bash
uv run pytest       # Run tests
uv run ruff check . # Linting
```
