# Sport Data Analysis Project

## 馃搫 Opis projektu

Ten projekt analizuje dane sportowe, korzystaj膮c z pliku CSV zawieraj膮cego szczeg贸艂owe informacje o parametrach fizjologicznych sportowc贸w. Analiza obejmuje przetwarzanie danych, eksploracj臋 oraz wizualizacj臋 wynik贸w.

---

## 馃搧 Zawarto艣膰 repozytorium

- **`sport.csv`**: Plik zawieraj膮cy dane wej艣ciowe.
- **`Sport.ipynb`**: Notatnik Jupyter Notebook z analiz膮 danych.
- **`README.md`**: Dokumentacja projektu.

---

## 馃搳 Struktura danych

Plik **`sport.csv`** zawiera 161 wierszy i 29 kolumn. Poni偶ej opis najwa偶niejszych kolumn:

- **`sex`**: P艂e膰 sportowca (1 - m臋偶czyzna, 0 - kobieta).
- **`date`**: Data zbierania danych.
- **`age`**: Wiek sportowca (w latach).
- **`height`**: Wzrost sportowca (w cm).
- **`weight`**: Waga sportowca (w kg).
- **`discipline`**: Dyscyplina sportowa (np. "running", "triathlon").
- **`AeT`**: T臋tno na progu tlenowym.
- **`AnT`**: T臋tno na progu beztlenowym.
- **`vo2max`**: Maksymalne zu偶ycie tlenu (ml/kg/min).
- **`vo2_at`**: Zu偶ycie tlenu na progu tlenowym.
- **`hrmax`**: Maksymalne t臋tno.
- **`la_10`, `la_12`, `la_14`**: Poziomy mleczanu (mmol/l) przy r贸偶nych poziomach t臋tna.

*(Pe艂na lista kolumn jest dost臋pna w pliku CSV.)*

---

## 馃敡 Wymagania

Projekt wymaga zainstalowania nast臋puj膮cych zale偶no艣ci:

- **Python**: Wersja 3.7 lub nowsza.
- **Biblioteki Python**:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`

Zaleca si臋 korzystanie ze 艣rodowiska wirtualnego (virtualenv lub conda).

---

## 馃殌 Instalacja

1. **Sklonuj repozytorium:**

   ```bash
   git clone https://github.com/TwojaNazwaUzytkownika/sport-data-analysis.git
   cd sport-data-analysis
