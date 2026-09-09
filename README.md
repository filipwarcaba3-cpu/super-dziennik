# Super dziennik 4.7

Wersja 4.7 rozwija Super dziennik 4.6.1 PostgreSQL/Neon.

Najważniejsze zmiany:
- administrator może edytować klasę: nazwę, rocznik i wychowawcę,
- administrator może edytować/usuwać każde wydarzenie kalendarza,
- nauczyciel może edytować/usuwać wydarzenia dodane przez siebie,
- w kartach przedmiotów w dziale Oceny wyświetlana jest średnia ważona,
- poprawiono układ mobilny, szerokości kart i tabel,
- można odwołać konkretną lekcję dla konkretnej daty,
- odwołana lekcja jest szara, a nazwa przedmiotu przekreślona,
- nauczyciel/admin może przywrócić odwołaną lekcję.

Aplikacja zachowuje obsługę `DATABASE_URL` dla PostgreSQL/Neon oraz SQLite jako tryb lokalny.
