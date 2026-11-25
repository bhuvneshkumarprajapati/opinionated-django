# Trace Supply

Django shipment-tracking backend with a session-authenticated operations dashboard.

## Run locally

```powershell
uv sync
uv run python src/manage.py migrate
uv run python src/manage.py createsuperuser
uv run python src/manage.py runserver
```

Open `http://127.0.0.1:8000/` and sign in with the superuser credentials. The dashboard uses the shipment API; API documentation remains at `http://127.0.0.1:8000/api/docs`.
