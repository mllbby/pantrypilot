# PantryPilot

PantryPilot is a web app for tracking pantry items and reducing food waste.

This repository currently contains a minimal Django setup with a home page.

## Requirements

- Python 3
- Django (already installed in `.venv`)

## Run locally

From the project folder:

```powershell
.\.venv\Scripts\Activate.ps1
python manage.py runserver
```

Open http://127.0.0.1:8000/ in your browser. You should see:

`PantryPilot is running!`

If port 8000 is not available, use another port:

```powershell
python manage.py runserver 127.0.0.1:8080
```

Then open http://127.0.0.1:8080/ .
