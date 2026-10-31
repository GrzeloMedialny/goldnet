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




Wzór Batemana
Dla n-tego izotopu w szeregu promieniotwórczym, jego ilość $N_n(t)$ w czasie t wyraża się wzorem:
$$N_n(t) = N_1(0) \left( \prod_{i=1}^{n-1} \lambda_i \right) \sum_{i=1}^n \frac{e^{-\lambda_i t}}{\prod_{j=1, j\neq i}^n (\lambda_j - \lambda_i)}$$ 
## Gdzie poszczególne symbole oznaczają:

* $N_n(t)$ – liczba atomów n-tego izotopu w łańcuchu po czasie t.
* N₁(0) – początkowa liczba atomów pierwszego (macierzystego) izotopu w czasie t=0.
* $\lambda_i$ – stała rozpadu promieniotwórczego dla i-tego izotopu (powiązana z czasem połowicznego rozpadu wzorem $\lambda = \frac{\ln(2)}{T_{1/2}}$).
* $\prod$ – symbol iloczynu (mnożenie kolejnych wartości).
* $\sum$ – symbol sumy (dodawanie kolejnych składników).

Klasyczny, prosty wzór na rozpad jądrowy ($N(t) = N_0 e^{-\lambda t}$) zakłada, że badamy tylko jeden izotop, który zamienia się w coś stabilnego.
W rzeczywistości (np. w szeregu uranowym) Uran-238 rozpada się w Tor-234, ten w Protaktyn-234, potem w Uran-234 i tak przez kilkanaście kroków. Każdy z tych elementów rozpada się w swoim własnym tempie, jednocześnie będąc stale "produkowanym" przez swojego poprzednika. Równanie Batemana rozwiązuje ten cały ciąg skomplikowanych równań różniczkowych jednocześnie.
Jeśli chcesz, mogę rozpisać ten wzór dla konkretnego przykładu (np. dla trzech pierwszych pierwiastków w łańcuchu) lub wytłumaczyć, jak oblicza się stałą rozpadu λ. Co wybierasz?
