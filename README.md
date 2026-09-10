# Super dziennik 4.11

Nowości:
- w powtarzalności lekcji dostępna jest opcja **Nie powtarzaj**,
- lekcja może być **grupowa** (dla całej klasy) albo **indywidualna**,
- dla lekcji indywidualnej można zaznaczyć jednego lub kilku uczniów z listy wszystkich uczniów szkoły,
- uczeń widzi w swoim planie tylko lekcje grupowe swojej klasy oraz lekcje indywidualne przypisane bezpośrednio do niego,
- frekwencja, oceny i uwagi na lekcji indywidualnej obejmują wyłącznie wybranych uczniów,
- zachowana zgodność z Neon PostgreSQL i poprzednimi funkcjami 4.10.

Wdrożenie na Render:
- Build Command: `pip install -r requirements.txt`
- Start Command: `python app.py`
- pozostaw istniejące `DATABASE_URL` bez zmian.
