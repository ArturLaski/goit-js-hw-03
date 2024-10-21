# goit-js-hw-03

## Struktura projektu
Projekt składa się z następujących plików i folderów:
- `/js`
  - `task-1.js` - Rozwiązanie zadania 1: Slug Generator
  - `task-2.js` - Rozwiązanie zadania 2: Array Composition
  - `task-3.js` - Rozwiązanie zadania 3: Filtering an Array of Numbers
- `.gitignore` - Plik ignorujący niepotrzebne pliki w repozytorium
- `.prettierrc` - Plik konfiguracyjny dla Prettier
- `index.html` - Strona główna projektu, wyświetlająca wyniki zadań w przeglądarce
- `README.md` - Dokumentacja projektu

## Opis zadań

### Task 1: Slug Generator
Celem tego zadania jest stworzenie funkcji `slugify(title)`, która przekształca tytuł artykułu w tzw. "slug" - czyli czytelny dla użytkownika identyfikator URL w formie małych liter, z wyrazami rozdzielonymi myślnikami. Wyniki są wyświetlane w sekcji "Task 1 Results" w pliku `index.html`.

### Task 2: Array Composition
Zadanie polega na stworzeniu funkcji `makeArray(firstArray, secondArray, maxLength)`, która łączy dwie tablice w jedną i, jeśli przekroczona zostanie maksymalna długość, zwraca skróconą wersję nowej tablicy. Wyniki są wyświetlane w sekcji "Task 2 Results" w pliku `index.html`.

### Task 3: Filtering an Array of Numbers
Zadanie polega na stworzeniu funkcji `filterArray(numbers, value)`, która przeszukuje tablicę liczb i zwraca nową tablicę zawierającą liczby większe niż zadany parametr `value`. Wyniki są wyświetlane w sekcji "Task 3 Results" w pliku `index.html`.

## Wymagania
- Kod musi być sformatowany za pomocą Prettier.
- Nie mogą występować żadne błędy ani ostrzeżenia w konsoli po uruchomieniu zadań.
- Taski 1, 2 i 3 muszą zostać wykonane i poprawnie wyświetlać wyniki w odpowiednich sekcjach strony `index.html`.

## Wyświetlanie wyników
Wyniki zadań są automatycznie wyświetlane w przeglądarce w odpowiednich sekcjach pliku `index.html`:
- Wyniki zadania 1 są wyświetlane w sekcji `#task-1-results`.
- Wyniki zadania 2 są wyświetlane w sekcji `#task-2-results`.
- Wyniki zadania 3 są wyświetlane w sekcji `#task-3-results`.

## Sformatowanie kodu za pomocą Prettier:

* Aby użyć Prettier, musisz zainstalować go w swoim projekcie. Można to zrobić, jeśli masz zainstalowany Node.js, za pomocą polecenia:
  
```bash
npm install --save-dev prettier
```

* Następnie możesz uruchomić Prettier na swoim kodzie za pomocą:

```bash
npx prettier --write .
```

To polecenie sformatuje wszystkie pliki w projekcie.

