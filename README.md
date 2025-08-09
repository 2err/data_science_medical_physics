
# Data Science for Medical Physics — Portfolio

**Cel repozytorium:** dokumentacja mojej rocznej ścieżki przejścia w kierunku Data Science z wykorzystaniem doświadczenia z fizyki medycznej i inżynierii materiałowej (scyntylatory, pomiary E2E, analiza obrazów).

## Spis treści
- `01_python_pandas/` — podstawy Pythona, Pandas, wizualizacje
- `02_sql_statistics/` — SQL + statystyka stosowana
- `03_machine_learning/` — modele ML (regresja, klasyfikacja, walidacja)
- `04_deep_learning/` — CNN i analiza obrazów
- `05_portfolio_freelance/` — przygotowanie portfolio i profili freelance
- `06_final_project/` — projekt roczny (case study)
- `data/` — surowe i przetworzone dane (niecommittowane, patrz .gitignore)
- `assets/` — zrzuty ekranu do README

## Uruchomienie środowiska
1. Zainstaluj Pythona 3.10+ i `pip`.
2. (Opcjonalnie) utwórz środowisko wirtualne:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # Windows: .venv\Scripts\activate
   ```
3. Zainstaluj zależności:
   ```bash
   pip install -r requirements.txt
   ```

## Dane
- Surowe dane umieszczaj w `data/raw/`, przetworzone w `data/processed/`.
- Pliki danych są ignorowane przez Gita — w README projektów opisuję jak je pozyskać / zanonimizować.

## Zrzuty ekranu
Wrzucaj obrazy do `assets/img/` i linkuj je w README poszczególnych projektów.

## Git — szybki start
```bash
git init
git add .
git commit -m "Initial commit: scaffold portfolio"
git branch -M main
git remote add origin https://github.com/<TwojaNazwa>/data-science-medical-physics.git
git push -u origin main
```

## Kontakt
- LinkedIn: <tu wstaw link>
- Email: <tu wstaw email>

---
> Na końcu roku: podsumowanie wyników, linki do prezentacji i publikacji.
