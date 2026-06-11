# Portfolio Inżyniera Instalacji Sanitarnych

Prosta strona internetowa portfolio dla inżyniera instalacji sanitarnych. Pliki w katalogu:

- `index.html` — główna strona
- `style.css` — stylizacja

## Jak opublikować na GitHub Pages

1. Utwórz nowe repozytorium na GitHub, np. `portfolio-sanitarne`.
2. Skopiuj pliki do lokalnego katalogu i wykonaj:
   ```bash
   git init
   git add .
   git commit -m "Pierwsza wersja portfolio"
   git branch -M main
   git remote add origin https://github.com/TWOJ_LOGIN/portfolio-sanitarne.git
   git push -u origin main
   ```
3. Wejdź do ustawień repozytorium na GitHub i włącz GitHub Pages z gałęzi `main`.
4. Po chwili strona będzie dostępna pod adresem `https://TWOJ_LOGIN.github.io/portfolio-sanitarne/`.

## Edycja zawartości

- Zmień swoje imię i dane kontaktowe w `index.html`.
- Dodaj kolejne projekty lub zdjęcia w sekcji `Wybrane projekty`.
- Możesz rozszerzyć stronę o kolejne sekcje, np. doświadczenie, certyfikaty lub referencje.

## Dodawanie plików PDF z projektami

1. Utwórz folder `projects` obok `index.html`, np. `projects/`.
2. Skopiuj swoje pliki PDF do tego folderu, np. `projects/projekt1.pdf`, `projects/projekt2.pdf`.
3. Otwórz `index.html` i w sekcji "Projekty (PDF)" zaktualizuj atrybuty `data-pdf` lub dodaj nowe elementy `.pdf-item` z odpowiednią ścieżką do pliku.
4. Po odświeżeniu strony kliknięcie miniaturki otworzy podgląd PDF w modalu. Jeśli osadzanie PDF nie działa w przeglądarce, użyj linku, który otwiera plik w nowej karcie.

Przykład struktury:
```
seba/
  ├─ index.html
  ├─ style.css
  ├─ README.md
  └─ projects/
      ├─ projekt1.pdf
      └─ projekt2.pdf
```

Po umieszczeniu plików zatwierdź zmiany i wypchnij je na GitHub, a następnie opublikuj repozytorium na GitHub Pages jak opisano wyżej.
