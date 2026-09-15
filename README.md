# Super dziennik 4.16

Nowa karta lekcji wzorowana na przesłanych przykładach:
- po wejściu w lekcję nauczyciel/administrator ma zakładki **Temat i obecność** oraz **Oceny**,
- temat i frekwencja są uzupełniane dla konkretnego wystąpienia lekcji,
- zakładka **Oceny** pokazuje tabelę całej klasy dla danego przedmiotu,
- przyciskiem **+** można utworzyć wspólną kolumnę ocen (np. „Kartkówka 1”) dla wszystkich uczniów,
- kolumna ma wspólną nazwę, wagę i kolor,
- oceny można wpisać uczniom bezpośrednio w komórkach tabeli i zapisać całą klasę naraz,
- zachowano dotychczasowe funkcje Super dziennika 4.15.

Baza Neon jest migrowana automatycznie: dodawana jest tabela `grade_columns` i pole `column_id` w `grades`. Istniejące dane nie są kasowane.
