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

## Dodawanie zdjęć projektów

1. Utwórz folder `projects` obok `index.html`.
2. Skopiuj swoje zdjęcia projektów (PNG, JPG) do tego folderu:
   - `projects/projekt1.png`
   - `projects/projekt2.png`
3. Po wgraniu na GitHub zdjęcia będą widoczne w sekcji **Projekty**. Klikanie na nie otworzy lightbox z powiększonym podglądem.

Struktura:
```
seba/
  ├─ index.html
  ├─ style.css
  ├─ README.md
  └─ projects/
      ├─ projekt1.png
      └─ projekt2.png
```

Wypchnij na GitHub:
```bash
cd c:\Users\Adrian\Desktop\seba
git add .
git commit -m "Dodanie galerii zdjęć projektów"
git push
```
