# Super dziennik 4.15

Zmiany względem 4.14:

- W planowaniu lekcji lista „Przedmiot” zawiera nową pozycję „Inne”.
- Po wybraniu „Inne” pojawia się pole „Nazwa”, w którym można wpisać własną nazwę wydarzenia / zajęć.
- Przy zapisie własna nazwa jest automatycznie dodawana jako przedmiot w danej szkole (jeśli jeszcze nie istnieje) i używana w planie lekcji.
- Dział IT otrzymał nowy panel „Klasy”.
- Administrator IT może dodawać, edytować i usuwać klasy w aktualnie edytowanej szkole.
- Pracownik IT może dodawać, edytować i usuwać klasy wyłącznie w przypisanej do niego szkole.
- Przy klasie można zmienić nazwę, rocznik i wychowawcę.
- Usunięcie klasy pozostawia uczniów w systemie jako „bez klasy”. Ze względów bezpieczeństwa nie można usunąć klasy, która ma jeszcze zaplanowane lekcje lub sprawdziany.
- Zmiany klas wykonywane przez pracownika IT trafiają do Historii zmian; dodanie i edycję można cofnąć, a usunięcie pustej klasy można odtworzyć wraz z poprzednimi przypisaniami uczniów.

Aplikacja nadal korzysta z tej samej bazy Neon przez `DATABASE_URL` i nie wymaga tworzenia nowej bazy.
