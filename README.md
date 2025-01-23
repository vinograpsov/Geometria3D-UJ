# Przygotowanie do egzaminu z Geometrii 3D

Repozytorium zostało stworzone do wspólnego przygotowania się do egzaminu z Geometrii 3D. Pomysł polega na tym, aby wspólnie pracować nad konspektami, rozwiązywać zadania i sporządzać notatki na tematy związane z egzaminem, które finalnie zostaną wygenerowane do pliku PDF. Jeśli chcesz po prostu podzielić się swoimi notatkami lub czymś podobnym, dodaj je do repozytorium w odpowiednich folderach. Jeśli takiego folderu nie ma, po prostu go utwórz :)

## Nie umiesz LaTeXa?
To nie jest problem! Wystarczy, że dodasz swoje notatki, a pozostale osoby zajma się ich konwersją do LaTeXa. Lub ruwnirz ChatGPT może pomóc w konwersji tekstu do LaTeXa, z mojego doświadczenia działa to całkiem nieźle.

## Metoda kompilacji

Osobiście używam **MiKTeX**, ale jeśli nie chcesz instalować tego narzędzia, możesz skorzystać z kompilatorów online, takich jak **Overleaf**. Nie wiem jednak, jak działają one z GitHubem. Jeśli działa to źle, wystarczy pobrać repozytorium i skopiować je do kompilatora online.

## Struktura repozytorium

- `main.tex` — główny plik, który łączy wszystkie pozostałe pliki w jeden dokument.
- Inne pliki `.tex` — pliki zawierające rozwiązania zadań lub notatki na różne tematy.

## Jak pracować z repozytorium

### Podstawowy proces

- **Główna gałąź repozytorium:** `main`. Zawiera zatwierdzone materiały.
- **Gałęzie robocze:**
  Każdy uczestnik tworzy swoją gałąź, aby pracować nad zadaniami. Format nazwy gałęzi: `imie_nazwisko`.

Po zakończeniu pracy tworzony jest pull request, który będzie omawiany i sprawdzany przez innych uczestników. Jeśli chcesz być współpracownikiem i mieć możliwość edycji bezpośrednio w moim repozytorium, proszę napisz do mnie na Discordzie: `@vinograpsov`.


## Wymagania dotyczące formatowania

- Wszystkie formuły i zadania muszą być zapisane w LaTeX.
- Komentarze w kodzie pisz po angielsku.
- Wskazuj źródła materiałów, jeśli korzystasz z dodatkowych zasobów.

## Instrukcje dla uczestników

1. Jeśli zostałeś dodany jako collaborator, możesz pracować bezpośrednio w repozytorium.
2. Jeśli nie, wykonaj fork tego repozytorium na swoje konto.
3. Sklonuj je na swoje urządzenie:
   ```bash
   git clone https://github.com/username/3d_geometry_exam_prep.git
   ```
4. Utwórz gałąź dla swojej pracy:
   ```bash
   git checkout -b branch_name
   ```
5. Po zakończeniu pracy wykonaj commit:
   ```bash
   git add .
   git commit -m "Dodano zadania dotyczące wektorów"
   git push origin branch_name
   ```
6. Utwórz pull request do gałęzi `main`.

## Współtwórcy
- Kiryl Vinahradau
