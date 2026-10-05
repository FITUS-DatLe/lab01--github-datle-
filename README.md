# Study Assistant — starter

A starter repository for the CSC10014 Smart Virtual Assistant project.

## Setup

1. Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate
   # Windows (PowerShell): .venv\Scripts\Activate.ps1

   pip install -r requirements.txt
    pip install -e .

## Run

python -m assistant "where is the IT helpdesk?"

## Test

pytest -q

## Project structure
src/assistant: Source code for the assistant application.

tests/: Unit tests for the application.

scripts/: Helper scripts, including environment checks.
