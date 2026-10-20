# Bra-Val — Minimal

Publiczna koncepcja sklepu: https://maciejsobolewski3-web.github.io/bra-val-minimal/

Samodzielny, statyczny frontend HTML/CSS/JavaScript. Katalog 15 ofert Bra-Val, kategorie, filtr odpinanej rączki, sortowanie, wyszukiwarka, strony produktów, warianty średnicy, powiększanie zdjęć, ulubione, koszyk i podsumowanie pokazowe. Koszyk nie składa zamówień ani nie pobiera płatności. Linki prowadzą do prawdziwych ofert sprzedawcy na Allegro.

## Dane i grafiki

Źródło katalogu: https://allegro.pl/uzytkownik/Bra-Val, odczyt 20.10.2026. `products.json` zapisuje ceny, parametry, konkretne URL ofert i źródła zdjęć. Zdjęcia produktowe pobrano z publicznych ofert sprzedawcy. Nie stanowi to deklaracji licencji ani własności tych zdjęć. Projekt prezentacyjny przygotowany na prośbę użytkownika.

Zdjęcie kampanijne `assets/campaign.webp` wygenerowano wbudowanym ImageGen z referencji fotograficznych produktów. Prompt: `assets/campaign-prompt.txt`. Zdjęcie jest koncepcyjną aranżacją; karty produktów wykorzystują zdjęcia z ofert. Nie dodano niepotwierdzonych danych kontaktowych, pochodzenia produkcji, opinii ani gwarancji.

Ceny są zapisem z daty odczytu, nie integracją na żywo. Dostępność, dostawa, zgodność z kuchenką i aktualne warunki zakupu są weryfikowane na Allegro. Strona ma `noindex,nofollow` i jasne oznaczenie projektu pokazowego.

## Uruchomienie

`npm run dev`, następnie http://localhost:4180/.
`npm run check` sprawdza składnię JavaScript.

Warianty przechowują koszyk i ulubione w osobnych przestrzeniach localStorage. Animacje respektują prefers-reduced-motion. Nawigacja po hashach działa na GitHub Pages bez serwera aplikacji.

## Wersje

- Oryginalna: https://maciejsobolewski3-web.github.io/bra-val/
- Atelier: https://maciejsobolewski3-web.github.io/bra-val-atelier/
- Editorial: https://maciejsobolewski3-web.github.io/bra-val-editorial/
- Minimal: https://maciejsobolewski3-web.github.io/bra-val-minimal/

## Weryfikacja

Sprawdzono katalog 15 produktów, filtr 4 modeli z odpinaną rączką, sortowanie cen, wybór średnicy, sumy koszyka i odświeżenie, usuwanie, linki ofert, wyszukiwanie, ulubione oraz powiększanie zdjęć. Sprawdzono układy stron głównych 320/390/768/1024/1280 px i podstrony przy 320 px, bez poziomego przepełnienia. Mobilne menu przetestowano w przeglądarce.
