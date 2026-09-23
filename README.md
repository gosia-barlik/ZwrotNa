# Fundacja ZwrotNa - doradztwo zawodowe

Statyczna, responsywna strona przygotowana w HTML, CSS i JavaScript. Nie wymaga instalowania bibliotek ani budowania projektu.

## Najprostsze uruchomienie

Otwórz plik `index.html` w przeglądarce.

## Uruchomienie przez lokalny serwer

W terminalu przejdź do folderu projektu i uruchom jedną z poniższych komend:

```bash
python -m http.server 8000
```

lub, jeżeli masz Node.js:

```bash
npx serve .
```

## Struktura
- `index.html` — homepage
- `styles.css` — wspólne style i responsywność
- `script.js` — menu mobilne, animacje wejścia, automatyczny rok w stopce
- `assets/` — logo, zdjęcia, ikony SVG, pdfy


## Ważne przed publikacją
- Podmień dane adresowe i telefon w stopce (`index.html`).
- Podmień wycięte z mockupu obrazy na finalne materiały źródłowe w wysokiej rozdzielczości.
- Uzupełnij docelowe treści podstron.
- Uzupełnij politykę prywatności i konfigurację Analytics / consent banner zgodnie z finalną decyzją projektową.
- Jeśli projekt zacznie rosnąć, warto przenieść wspólne elementy (header/footer/cards) do komponentów np. w Astro.

## Kolory
- Akcent: `#C71978`
- Piaskowy: `#E1D9CD`
- Tło: `#FBF7F3`
