# Super dziennik 4.9

Wersja 4.9 rozwija działającą wersję 4.8 z Neon PostgreSQL.

## Nowości 4.9

- Administrator może dodać, edytować i usunąć informację widoczną na stronie logowania w niebieskim prostokącie.
- Administrator może edytować i usuwać każdy zaplanowany sprawdzian, a nauczyciel może edytować i usuwać sprawdziany zaplanowane przez siebie.
- Uczeń widzi w kalendarzu sprawdziany i kartkówki zaplanowane dla jego klasy.
- W Profilu każdy użytkownik może wybrać kolor dziennika: niebieski (domyślny), zielony lub czerwony. Ustawienie jest zapisywane w bazie.
- Zachowane są funkcje wersji 4.8, w tym roczny plan lekcji, powtarzalność, daty tygodnia, anulowanie lekcji i Neon PostgreSQL.

## Render

- `DATABASE_URL` powinien pozostać ustawiony na connection string z Neon.
- Build Command: `pip install -r requirements.txt`
- Start Command: `python app.py`

Aktualizacja nie usuwa istniejących uczniów ani ocen. Przy starcie dodawane są tylko brakujące kolumny `schools.login_notice` i `users.theme`.
