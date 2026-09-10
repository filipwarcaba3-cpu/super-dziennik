# Super dziennik 4.10

Zmiany w wersji 4.10:
- komunikaty szkolne można edytować i usuwać,
- administrator może edytować/usunąć każdy komunikat,
- nauczyciel może edytować/usunąć komunikat dodany przez siebie,
- przy odebranej wiadomości jest przycisk „Odpowiedz”,
- formularz odpowiedzi automatycznie wybiera nadawcę jako odbiorcę,
- temat odpowiedzi jest automatycznie ustawiany jako `RE: <temat>` bez podwajania `RE:`.

Wersja zachowuje obsługę Neon PostgreSQL przez `DATABASE_URL` i nie usuwa istniejących danych. Dodawana jest tylko kolumna `created_by` do komunikatów, aby zapamiętać autora nowych komunikatów.

## Render
Build Command:
`pip install -r requirements.txt`

Start Command:
`python app.py`
