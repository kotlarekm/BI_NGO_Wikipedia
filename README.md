# BI_NGO_Wikipedia
BI_NGO Project for Wikipedia

Logotypy:
https://drive.google.com/drive/u/0/folders/1ar2ViYoEzNVmQTpTDY2YzpjW6KHY0O62

Kolory:
https://meta.wikimedia.org/wiki/Brand/colours

Typografia:
https://meta.wikimedia.org/wiki/Brand/Typography

Paleta:
Tekst

tytuły: #000000 (wm-black)
opisy: #404040 (wm-black-75)
przypisy: #7F7F7F (wm-black-50)

Kolor marki
główny akcent: #0E65C0 (wm-blue)

Tło:
Zamiast czystej bieli:

tło: wm-yellow-bright-light #F9F9F0
tytuły: #000000
tekst: #404040
wykresy: Wikimedia Blue #0E65C0 - wybrane słupki
wm-blue-light #C3D8EF - wszystkie słupki

To do:

- Tytuły wykresów
- Weryfikacja metodologii
- Uporządkowanie modelów danych - czy zostawiać PowerBI?
- Uporządkowanie repo
    
Zrobione:
- Przygotowanie danych
    - najnowszy tytuł pod pageId, w otrzymanych danych każde page_id ma już aktualny tytuł
    - uzupełnienie brakujących page_id - puste page_id pochodzą ze stron już nieistniejących (np. przeniesionych gdzieś indziej, jedyną istotną stroną jest "xss")
    - przypisanie 20 kategorii - lub kategorii z wikipedii, zebranie kategorii przez API
- Top 10 (?) wyświeltanych artykułów
    - mam staystyki na podstawie https://pageviews.wmcloud.org/ - "D:\AnalizaDanych\000_projekty\BI_NGO_Wikipedia\BI_NGO_Wikipedia\data\pageviews-2016-08-2026-08.csv"
    - Biblia w latach 2016-2017 ma ogromne skoki ze względu na zwiększony ruch botów i błędy w raportowaniu,
        z tego względu decyduję się na ograniczenie analizy do ostatnich 8 lat?
    
    - korelacja anomalii - z wydarzeniami
    - Zrobienie metryki - procentowego i całkowitego odchylenia od średniej
- Top kategorii
    - przygotowanie danych

- Strona główna - Karty z sumą elementów
    - wyświetlenia - suma z ostatnich 10 lat    

    - Storytelling
        - Slajd z podsumowaniem
        - Weryfikacja tekstów
        - Weryfikacja kolorów
        - Wyrównywanie
        - Numeracja źródeł w meodologii
        - Weryfikacja wyświetleń kategorii dla 200 lub 300 artykułów
        - Usuń plik analiza top.csv

Anulowane:
- Top 10 (?) edytowanych artykułów
    - Suma Nowych artykułów z ostatnich 25
    - Suma Nowych użytkowników z ostatnich 25
    - Średnia aktywnych użytkowników  z ostatnich?