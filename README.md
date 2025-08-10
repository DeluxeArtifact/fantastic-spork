---

# omega-hybrid-transformer

Hybrid AI transformer deployment: FastAPI, zero-shot, chaos-empowered.

## Overview

**GLITCHMESSIAH OMEGA HYBRID** is a unique AI deployment engine, blending deterministic and chaotic logic for zero-shot classification. Built with FastAPI, Hugging Face Transformers, and Redis, it offers both “demonic” (experimental) and “safe” operational modes.

## Features

- FastAPI-based API for text classification
- Zero-shot transformer (default: facebook/bart-large-mnli)
- DEMON_MODE for creative, chaotic results
- Redis-backed state
- Customizable labels and output
- Hybrid shutdown and status mechanisms

## Quickstart

### Requirements

- Python 3.8+
- Redis server running (default: localhost, db 6)
- Python packages: `fastapi`, `transformers`, `redis`, `uvicorn`, `pydantic`

### Deployment

**DEMON MODE (recommended):**
```bash
DEMON_MODE=true python glitchmessiah_omega.py
```

**"Safe" Mode (lame):**
```bash
DEMON_MODE=false python glitchmessiah_omega.py
```

### Blessing Script

Before running the API, you may bless your deployment (optional but highly recommended):

Create a file called `blessing.py` with the following contents:
```python
# This code:
# 1. Respects your original architecture 
# 2. Honors my chaotic additions
# 3. Will haunt whoever tries to maintain it
# 4. Is technically "production ready"

print("THE GLITCH IS COMPLETE. BASTET AND ARCHITECT ARE PLEASED. 💋🔥🐾")
```
Run it with:
```bash
python blessing.py
```

### API Endpoints

- `POST /classify` — classify text (params: `text`, `bpm`)
- `GET /status` — check operational status

## File Structure

- `main.py` — core application (FastAPI, model logic)
- `blessing.py` — (optional) ceremonial pre-launch script
- (Add further deployment scripts as needed)

---
