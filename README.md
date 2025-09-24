# Darkweb Chat – Prosty Szyfrowany Czat w HTML

## Opis

To minimalistyczna, lekka i czarna jak noc na Torze strona do lokalnej komunikacji.  
Zaprojektowana z myślą o bezpieczeństwie i prywatności — zero zewnętrznych bibliotek, zero śledzenia, zero przepychu.

Wszystkie wiadomości są szyfrowane prostym XOR-em z kluczem ustalonym w kodzie (możesz go zmienić) —  
pamiętaj jednak, że to tylko demo i dla prawdziwej anonimowości i bezpieczeństwa potrzebujesz pełnego backendu i Tor Hidden Service.

---

## Funkcje

- Dark mode i czytelny design dla nocnych marków
- Szyfrowanie wiadomości na froncie (XOR z kluczem)
- Prosta symulacja wymiany wiadomości lokalnie przez `localStorage`
- Zero zewnętrznych zależności — wszystko w jednym pliku `index.html`
- Obsługa wysyłania wiadomości klawiszem Enter i przyciskiem

---

## Jak używać

1. Pobierz plik `index.html`.
2. Otwórz go w przeglądarce (najlepiej Tor Browser, jeśli chcesz poczuć klimat darkwebu).
3. Wpisz wiadomość w dolnym polu i kliknij **Wyślij** lub naciśnij Enter.
4. Twoja wiadomość zostanie zaszyfrowana i wyświetlona na czacie.
5. Symulowany odbiór wiadomości pokaże odszyfrowany tekst (demo lokalne).

---

## Uwaga

- Ten projekt to podstawowy przykład — do realnej komunikacji na darkwebie potrzebujesz backendu, HTTPS, Tor Hidden Service i zaawansowanego szyfrowania.
- Klucz szyfrowania jest statyczny i prosty — dla bezpieczeństwa zmień go na własny, długi i losowy.
- Nie przechowuj wrażliwych danych ani prawdziwych rozmów w tym demo.

---

## Rozwój i dalsze kroki

- Dodanie prawdziwego AES z WebCrypto API
- Połączenie z backendem przez WebSocket i hosting w Tor Hidden Service
- Obsługa wielu użytkowników i anonimowość
- Automatyczne czyszczenie historii, obsługa kluczy asymetrycznych

---

## Kontakt
Chcesz pomocy? Pytaj śmiało — zawsze na czacie, nawet w mroku!

---

*Darkweb Chat © 2025 Grzelo Medialny*  
*Bezpieczne rozmowy, bez świateł i fleszy.*









