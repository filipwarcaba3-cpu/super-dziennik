# Super dziennik 4.14

Zmiany względem 4.13.1:

- Administrator IT może usuwać uczniów z aktualnie edytowanej szkoły.
- Administrator IT może blokować i odblokowywać konta uczniów i nauczycieli.
- Zablokowany uczeń lub nauczyciel po zalogowaniu widzi czerwony komunikat: „Twoje konto zostało zablokowane przez administratora IT. Aby je odblokować skontaktuj się z twoim dyrektorem.” oraz przycisk wylogowania.
- Pracownik IT nie może blokować, odblokowywać ani usuwać uczniów.
- Przy wystawianiu oceny przez nauczyciela lub administratora można wybrać kolor: czerwony, zielony, niebieski, czarny albo fioletowy.
- Uczeń widzi ocenę w wybranym kolorze w dziale Oceny oraz w szczegółach lekcji.
- Kolor można także zmienić przy edycji istniejącej oceny.
- Migracja bazy dodaje jedynie kolumnę `grades.color`; dotychczasowe oceny otrzymują kolor czarny.

Aplikacja nadal korzysta z tej samej bazy Neon przez `DATABASE_URL`.
