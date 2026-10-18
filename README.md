manzilcart/               <-- Current working directory (repo root)
├── manage.py             <-- Sits right at the root
├── config/               <-- Settings, asgi.py, wsgi.py, urls.py
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py       (later split into settings/base.py, local.py)
│   ├── urls.py
│   └── wsgi.py
├── apps/                 <-- All domain apps live here
│   ├── __init__.py
│   ├── accounts/
│   └── core/
├── templates/            <-- Global HTML templates
├── static/               <-- CSS, JS, images
├── media/                <-- User uploaded images
└── venv/                 <-- Virtual environment (gitignored)
