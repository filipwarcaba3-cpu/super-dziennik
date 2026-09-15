# Super dziennik 4.22

Zmiany:
- naprawione otwieranie karty ucznia (usunięty błąd powodujący HTTP 502),
- potwierdzenie „Czy pokazać kartę ucznia?” działa także przy sprawdzaniu obecności,
- przy planowaniu sprawdzianu lista lekcji jest filtrowana jednocześnie po wybranej klasie i przedmiocie,
- karta wpisywania tematu/obecności jest żółta bez tematu i zielona po zapisaniu tematu,
- brak frekwencji choćby jednego ucznia pokazuje czerwony wykrzyknik na planie nauczyciela,
- wewnątrz lekcji widoczny jest czerwony komunikat „Nie sprawdzona obecność”,
- ostrzeżenie znika dopiero po zapisaniu frekwencji wszystkim uczniom.


## Wersja 4.22 – poprawy ocen
- Przy każdej kolumnie ocen jest przycisk **Dodaj poprawę**.
- Poprawa tworzy zsynchronizowaną kolumnę, w której można wpisać ocenę uczniowi.
- Uczeń widzi historię jako: stara ocena przekreślona → nowa ocena.
- Można dodać poprawę poprawy i kolejne poprawy.
- Średnia przedmiotu używa najnowszej oceny z łańcucha popraw zamiast liczyć jednocześnie starą i poprawioną ocenę.
- Kolumny z poprawami można edytować; przy usuwaniu zachowana jest kolejność łańcucha.
