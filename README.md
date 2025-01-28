# Sport Data Analysis Project

## 🏈 Opis projektu

Ten projekt analizuje dane sportowe, korzystając z pliku CSV zawierającego szczegółowe informacje o parametrach fizjologicznych sportowców. Analiza obejmuje przetwarzanie danych, eksplorację oraz wizualizację wyników.

---

## 📇 Zawartość repozytorium

- **`sport.csv`**: Plik zawierający dane wejściowe.
- **`Sport.ipynb`**: Notatnik Jupyter Notebook z analizą danych.
- **`README.md`**: Dokumentacja projektu.

---

## 📊 Struktura danych

Plik **`sport.csv`** zawiera 161 wierszy i 29 kolumn. Poniżej opis najważniejszych kolumn:

- **`sex`**: Płeć sportowca (1 - mężczyzna, 0 - kobieta).
- **`date`**: Data zbierania danych.
- **`age`**: Wiek sportowca (w latach).
- **`height`**: Wzrost sportowca (w cm).
- **`weight`**: Waga sportowca (w kg).
- **`discipline`**: Dyscyplina sportowa (np. "running", "triathlon").
- **`AeT`**: Tętno na progu tlenowym.
- **`AnT`**: Tętno na progu beztlenowym.
- **`vo2max`**: Maksymalne zużycie tlenu (ml/kg/min).
- **`vo2_at`**: Zużycie tlenu na progu tlenowym.
- **`hrmax`**: Maksymalne tętno.
- **`la_10`, `la_12`, `la_14`**: Poziomy mleczanu (mmol/l) przy różnych poziomach tętna.

*(Pełna lista kolumn jest dostępna w pliku CSV.)*

---

## 📁 Wymagania

Projekt wymaga zainstalowania następujących zależności:

- **Python**: Wersja 3.7 lub nowsza.
- **Biblioteki Python**:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`

Zaleca się korzystanie ze środowiska wirtualnego (virtualenv lub conda).

---

## 🚜 Instalacja

1. **Sklonuj repozytorium:**

   ```bash
   git clone https://github.com/MistalH/Sport
   cd Sport
