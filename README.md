# Flask API

## Run

```bash
uv pip install -r requirements.txt
uv run python app.py
```

## Endpoints

- `GET /health` → `{"status": "ok"}`
- `POST /predict` → `{"label": "positive", "score": 0.95}`
