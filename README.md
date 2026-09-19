# BI_NGO_Wikipedia
BI_NGO Project for Wikipedia

Logotypy:
https://drive.google.com/drive/u/0/folders/1ar2ViYoEzNVmQTpTDY2YzpjW6KHY0O62

Kolory:
https://meta.wikimedia.org/wiki/Brand/colours

Typografia:
https://meta.wikimedia.org/wiki/Brand/Typography


To do:
- Strona główna - Karty z sumą elementów
    - wyświetlenia - suma z ostatnich 10 lat
    - Suma Nowych artykułów z ostatnich 25
    - Suma Nowych użytkowników z ostatnich 25
    - Średnia aktywnych użytkowników  z ostatnich?
- Top 10 (?) wyświeltanych artykułów
- Top 10 (?) edytowanych artykułów
- Top kategorii
    - przygotowanie danych
    
    

Zrobione:
- Przygotowanie danych
    - najnowszy tytuł pod pageId, w otrzymanych danych każde page_id ma już aktualny tytuł
    - uzupełnienie brakujących page_id - puste page_id pochodzą ze stron już nieistniejących (np. przeniesionych gdzieś indziej, jedyną istotną stroną jest "xss")
    - przypisanie 20 kategorii - lub kategorii z wikipedii, zebranie kategorii przez API