# Super dziennik 4.8 — roczny plan lekcji + Neon PostgreSQL

Wersja 4.8 zachowuje dane w tej samej bazie Neon i rozszerza plan lekcji o harmonogram na cały rok szkolny.

## Nowości 4.8

- plan jest wyświetlany dla konkretnego tygodnia,
- przyciski **Poprzedni tydzień** i **Następny tydzień**,
- przy nazwach dni tygodnia wyświetlane są konkretne daty `dzień.miesiąc`,
- w planowaniu zajęć: **Powtarzalność** — co tydzień, co dwa tygodnie lub co miesiąc,
- pola **Od kiedy** i **Do kiedy** określają okres obowiązywania lekcji,
- tryb `Co miesiąc` powtarza zajęcia w tym samym porządku dnia tygodnia w miesiącu (np. pierwszy wtorek),
- dotychczasowe lekcje bez zakresu dat pozostają traktowane jako cotygodniowe,
- odwołanie lekcji nadal dotyczy jednej konkretnej daty,
- plan na telefonie można przewijać poziomo, aby zachować czytelne szerokości kolumn.

## Render

Environment: `DATABASE_URL` = connection string z Neon.

Build Command:

```bash
pip install -r requirements.txt
```

Start Command:

```bash
python app.py
```

Przy pierwszym uruchomieniu 4.8 aplikacja bezpiecznie dodaje do tabeli `lessons` kolumny `recurrence`, `date_from` i `date_to`. Nie usuwa istniejących uczniów ani ocen.
