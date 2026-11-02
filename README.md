# WbL1 – Lexis from the whiteboard

Aplikacja webowa do utrwalenia słownictwa z tablicy (WbL1, wrzesień i październik):
62 wyrażenia – przymiotniki i przysłówki, rzeczowniki, czasowniki oraz zwroty.

**Autor:** Marcin Wyrzykowski · © 2026 Marcin Wyrzykowski – patrz [LICENSE](LICENSE).

## Co potrafi

- **Fiszki** – wyrażenie po angielsku; po odwróceniu polskie znaczenie, definicja i przykład.
- **Quiz** – polskie znaczenie i wybór jednej z 4 odpowiedzi.
- **Luki** – wpisanie brakującego słowa w zdaniu, z podpowiedzią.
- Filtry według części mowy i zakładka **Do powtórki** z błędnymi odpowiedziami.
- Postęp zapisuje się lokalnie w przeglądarce, bez logowania.

Cała aplikacja to jeden plik `index.html` – bez budowania i zależności.

## Publikacja na GitHub Pages

1. W repozytorium: **Settings → Pages → Build and deployment → Source: GitHub Actions**.
2. Workflow `.github/workflows/deploy.yml` przy każdym pushu do `main` opublikuje stronę
   pod adresem `https://<użytkownik>.github.io/<repozytorium>/`.
