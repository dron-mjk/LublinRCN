# LublinRCN

Projekt do analizy danych i budowy modeli regresyjnych (scikit-learn/XGBoost) dla danych przestrzennych z Rejestru Cen Mieszkań.

## Zarys projektu
- `download_data.ipynb` - pobranie danych.
- `clean_data.ipynb` - czyszczenie i weryfikacja.
- `preprocess_data.ipynb` - wstepne przetwarzanie.
- `eda.ipynb` - eksploracja i selekcja cech.
- `train_models.ipynb` - trenowanie i ocena modeli.
- `model_explainability.ipynb` - SHAP/LIME dla interpretowalnosci.

## Szybki start
```bash
uv sync
uv run jupyter lab
```

## Build dokumentacji
```bash
uv run jupyter-book build book/
```

Material teoretyczny i szerszy opis znajduja sie w ksiazce projektu (`book/`).