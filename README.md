# ConnectCare

A lightweight social-media-style web app to help NGOs connect, share updates, and collaborate.

## Features

* Sign‑up, login, logout using Flask‑Login
* Create short text posts (updates)
* Follow other NGOs to see their updates in your personalised feed
* Search NGOs by name
* Responsive UI powered by Bootstrap 4

## Quick‑start

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python app.py  # database will be created automatically
```

Navigate to http://127.0.0.1:5000 in your browser.

## Project structure

```
app.py              – main Flask application
requirements.txt
templates/          – Jinja templates (HTML)
static/             – CSS & JS
```

Feel free to extend the models and templates (e.g., image uploads, events, messaging).
