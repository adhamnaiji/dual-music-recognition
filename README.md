
# Dual Music Recognition

A cross-platform music recognition project combining
a custom Python audio fingerprinting engine with
Apple ShazamKit.

## Architecture

- Backend: Python, SciPy, SQLite, FastAPI
- Mobile: Flutter (Android and iOS)
- Recognition: Custom fingerprinting + ShazamKit

## Phase 1: Custom Recognition Engine

Goal: Recognize short audio recordings by matching
their fingerprints against an indexed music catalog.

## Development Setup

```powershell
cd backend
py -3.12 -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -e ".[dev]"
python -m pytest -q
```

## Project Status

Phase 1 — Initial development.

## License

Not yet selected.
