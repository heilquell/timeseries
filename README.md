# timeseries

Zwei Lern-Notebooks rund um sequentielle Daten mit TensorFlow/Keras. Stand
2019, nicht aktiv gepflegt.

## Inhalt

| Notebook | Was es macht | Stack |
|---|---|---|
| `Copy_of_text_generation.ipynb` | Character-Level RNN (GRU) für Text-Generation auf Shakespeare-Korpus (Karpathy-Dataset). Adaption des offiziellen TensorFlow-Tutorials. | TensorFlow / Keras (GRU) |
| `time_series_A&B_google.ipynb` | LSTM-Forecast auf Aktien-Kursdaten (Google A&B). Multi-Feature-Sequenz-Modell mit Train/Val/Test-Split, Plotly-Visualisierung. | TensorFlow / Keras (LSTM), pandas, plotly |

Beide basieren auf TensorFlow-Tutorials (Apache 2.0, Copyright-Header
ist in den Notebooks erhalten) und sind an eigene Daten/Fragestellungen
angepasst.

## Benutzung

Beide für Google Colab geschrieben. Lokal:

```
pip install tensorflow keras pandas numpy matplotlib plotly
```

Das Time-Series-Notebook nutzt `%tensorflow_version 2.x` (Colab-Magic) —
lokal einfach ignorieren, normales TF 2.x reicht.

## Stand

TF 2.0er-Frühphase. Bei aktuellem TensorFlow ggf. kleinere
Deprecation-Warnings, sollte aber durchlaufen.
