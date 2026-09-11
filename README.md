# Super dziennik 4.12

Wersja 4.12 dodaje osobny panel **Dział IT**.

Najważniejsze zmiany:
- jeden Administrator IT (`fwarcabaIT`) tworzony automatycznie przy pierwszym uruchomieniu wersji; początkowe hasło `1234`, możliwe do zmiany w Profilu,
- wyłącznie Administrator IT może dodawać i usuwać szkoły,
- administrator szkoły nie może już tworzyć nowych szkół,
- Administrator IT może przełączać aktualnie edytowaną szkołę,
- Administrator IT może dodawać pracowników IT i przypisywać ich do jednej szkoły,
- pracownik IT widzi i edytuje wyłącznie przypisaną szkołę,
- Dział IT może zmieniać login oraz hasło nauczyciela,
- Administrator IT może zmienić globalną nazwę dziennika,
- Dział IT ma wgląd w oceny, uwagi i pochwały ucznia, ale nie może ich edytować,
- Dział IT może dodawać, edytować i usuwać wpisy frekwencji w swojej szkole,
- administratorzy i nauczyciele mogą pisać do Administratora IT oraz przypisanego pracownika IT,
- przy osobach IT w poczcie widoczna jest etykieta „Pracownik działu IT”.

Baza danych jest rozwijana migracyjnie: istniejące szkoły, uczniowie, oceny i pozostałe dane nie są kasowane.

Po wdrożeniu zaleca się od razu zalogować jako `fwarcabaIT` / `1234` i zmienić hasło w Profilu.
