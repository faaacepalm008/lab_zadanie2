# Opis zadania 2
### Struktura projektu:
```
zadanie2/
├── public/
├── src/
│   ├── components/
│   │   ├── Header.js
│   │   ├── Footer.js
│   │   └── Content.js
│   ├── App.js
│   ├── App.css
│   └── index.js
├── Dockerfile
├── package.json
└── .github/
    └── workflows/
        └── ci.yml
```

# Zadanie - Budowanie i Wdrażanie Obrazu Docker

To repozytorium zawiera kod źródłowy aplikacji React oraz konfigurację CI/CD do budowania i wdrażania obrazu Docker na platformie GitHub.

## Opis Zadania

Celem tego zadania jest:

1. Utworzenie aplikacji React.
2. Skonfigurowanie CI/CD z wykorzystaniem GitHub Actions.
3. Budowanie obrazu Docker dla aplikacji React.
4. Testowanie obrazu pod kątem podatności na zagrożenia.
5. Wdrażanie obrazu na GitHub Container Registry (GHCR).

## Krok po Kroku

1. **Utworzenie Aplikacji React:**
   - Stworzona  nowa przykładowa aplikacja na React z tego powodu, że z zadanie 1 była nisko oceniona

2. **Konfiguracja CI/CD:**
   - Skonfigorowałem plik `ci.yml` z wykorzystaniem GitHub Actions, który będzie budował, testował i wdrażał obraz Docker.

3. **Budowanie Obrazu Docker:**
   - Stworzony odpowiedni plik `Dockerfile`, aby zbudować obraz Docker dla aplikacji React.![Zrzut ekranu 2024-06-3 o 17 39 25](https://github.com/faaacepalm008/lab_zadanie2/assets/83872764/a8d9174a-7502-4595-bc26-82599a8ff086)


4. **Testowanie Podatności:**
   - Wykonane skanowanie obrazu Docker pod kątem podatności na zagrożenia.

5. **Wdrażanie Obrazu:**
   - "PULL" zbudowanego obrazu Docker do GitHub Container Registry.

![Zrzut ekranu 2024-06-3 o 17 34 32](https://github.com/faaacepalm008/lab_zadanie2/assets/83872764/1fb1442d-83d6-46c6-94b2-a94c482c73e3)

![Zrzut ekranu 2024-06-3 o 17 37 59](https://github.com/faaacepalm008/lab_zadanie2/assets/83872764/c975c712-013e-4a8f-970b-328f57e3a92c)
![Zrzut ekranu 2024-06-3 o 17 38 26](https://github.com/faaacepalm008/lab_zadanie2/assets/83872764/801aa998-804d-44af-a765-b5a0361effba)
