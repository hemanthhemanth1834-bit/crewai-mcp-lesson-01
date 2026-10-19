# CrewAI MCP Course — Lesson 01

A beginner example demonstrating a single CrewAI research agent and task.

## Requirements

- Python
- An OpenAI API key
- Dependencies listed in `requirements.txt`

## Setup

Create and activate a virtual environment, then install dependencies:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
```

Copy `.env.example` to `.env` and set your own `OPENAI_API_KEY` in `.env`.
Never commit your real API key.

## Run

```powershell
python agent.py
```

The agent uses the `gpt-4o-mini` model through `langchain-openai`.
API usage may incur charges; check your provider's current pricing and limits.

## What it demonstrates

- Agent roles, goals, and backstories
- Task definitions and expected outputs
- Sequential CrewAI execution

## Attribution

This lesson was separated from the upstream
[500-AI-Agents-Projects](https://github.com/ashishpatel26/500-AI-Agents-Projects)
repository. See `LICENSE` and `UPSTREAM_ATTRIBUTION.md`.
