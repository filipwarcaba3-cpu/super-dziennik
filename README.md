# Super dziennik 4.12.1

Poprawiona wersja panelu Działu IT.

## Poprawki
- naprawione działanie stron **Informacje szkoły**, **Pracownicy IT** i **Informacje o dzienniku**; przyczyną były akcje zapisu IT umieszczone błędnie w obsłudze GET zamiast POST,
- Administrator IT i pracownik IT mogą w **Użytkownicy szkoły** zmieniać login i hasło nauczycieli oraz uczniów przypisanych do edytowanej szkoły,
- usunięto przycisk **Karta ucznia** z panelu **Użytkownicy szkoły**,
- osobny panel **Karty uczniów** nadal służy do dozwolonego wglądu w dane pedagogiczne,
- dodano walidację zajętego loginu i szkoły,
- zachowano PostgreSQL/Neon i dotychczasowe dane.

## Wdrożenie
Na GitHub należy podmienić `app.py` oraz opcjonalnie `README.md`. `requirements.txt` pozostaje bez zmian. Nie zmieniaj `DATABASE_URL` w Renderze.
