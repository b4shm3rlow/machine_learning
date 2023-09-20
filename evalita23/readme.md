# Progetto GeoLingIT 2023
### Models
different models were developed based on two precise text pre-processing processes: the first eliminating all possible accents and apostrophes in words, the second keeping them all

### Results of best models

| Model | Pre-processing with accents/apostrophes | Precision | Recall | F1-Score |
|-------|-----------------|-----------|--------|----------|
| Logistic Regression | No | 0.62 | 0.42 | 0.46 |
| Bi-LSTM | No | 0.62 | 0.52 | 0.54 |
| CNN | Yes | 0.62 | 0.52 | 0.54 |
| Deep CNN | Yes | 0.69 | 0.62 | 0.62 |
