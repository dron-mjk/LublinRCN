# LublinRCN

Projekt polegający na analizie danych i budowie modeli regresyjnych dla danych przestrzennych z Rejestru Cen Mieszkań z 2025/2026 roku.

## Zarys projektu
- `download_data.ipynb` - pobranie danych.
- `clean_data.ipynb` - czyszczenie i weryfikacja.
- `preprocess_data.ipynb` - wstepne przetwarzanie.
- `eda.ipynb` - eksploracja i selekcja cech.
- `train_models.ipynb` - trenowanie i ocena modeli.
- `model_explainability.ipynb` - SHAP/LIME dla interpretowalnosci.

## Wymagania
- Python `>=3.12`
- `uv` (zarzadzanie srodowiskiem i zaleznosciami): [https://docs.astral.sh/uv/](https://docs.astral.sh/uv/)


## Instalacja zależności
```bash
uv sync
```

## Budowanie plików html z dokumentacją
```bash
uv sync --dev
uv run jupyter-book build book/
```

Material teoretyczny i szerszy opis znajduja sie w notatnikach