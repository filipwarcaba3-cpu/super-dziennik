# Super dziennik 4.17.2

Poprawka błędu HTTP 502 na Render/Neon przy otwieraniu planu lekcji i po planowaniu sprawdzianu.

Przyczyna: migracja PostgreSQL wykonywała ALTER TABLE dla istniejącej kolumny, a późniejszy rollback cofał nowe migracje, m.in. `tests.target_lesson_id`. Wersja 4.17.2 używa bezpiecznego `ADD COLUMN IF NOT EXISTS` i nie cofa prawidłowych migracji.

Dane w Neon nie są usuwane.
