# Super dziennik 4.2

Demo technologiczne elektronicznego dziennika szkolnego.

## Nowości 4.2
- Uczeń ma osobne rubryki **Oceny** oraz **Uwagi i pochwały** w pasku bocznym.
- Uwagi i pochwały są wyświetlane pionowo, jedna pod drugą.
- **Uwaga** jest prezentowana na czerwono, a **Pochwała** na zielono.
- Autor wpisu może edytować i usuwać własną uwagę/pochwałę; administrator może edytować i usuwać każdy wpis.
- Oceny ucznia są pogrupowane poziomo według przedmiotów w prostokątnych kartach.
- Im więcej ocen z danego przedmiotu, tym większa szerokość jego prostokąta.
- Frekwencja zachowuje statusy: obecny, nieobecny, spóźnienie, spóźnienie usprawiedliwione oraz nieobecność usprawiedliwiona.

## Uruchomienie
```bash
python app.py
```
Następnie otwórz `http://127.0.0.1:8000`.

Demo: `admin/admin123`, `nauczyciel/demo123`, `uczen/demo123`.

## Testy
```bash
python test_app.py
python test_v4.py
python test_v41.py
python test_v42.py
```

To jest prototyp/demo technologiczne, nie system produkcyjny.
