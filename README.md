# Super dziennik 4.6.1 — Neon PostgreSQL

Public-ready demo e-dziennika. Wersja 4.6.1 obsługuje trwałą bazę PostgreSQL (np. Neon) przez zmienną `DATABASE_URL`.

## Render
1. Environment: ustaw `DATABASE_URL` na connection string z Neon.
2. Build Command: `pip install -r requirements.txt`
3. Start Command: `python app.py`

Jeżeli `DATABASE_URL` nie jest ustawione, aplikacja działa lokalnie z SQLite jako trybem awaryjnym.

Po uruchomieniu z `DATABASE_URL` aplikacja sama utworzy wymagane tabele PostgreSQL.
