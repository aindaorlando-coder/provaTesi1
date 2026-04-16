# Progetto: Pipeline automatizzata per dati ambientali

## Obiettivo
Sviluppare una pipeline automatizzata per l’analisi e la predizione della qualità dell’aria utilizzando dati reali, confrontando una implementazione manuale (Colab) con una generata tramite OpenCode.ai a partire da specifiche GSD.

---

## Dataset 
- Dataset reale: datasetDelhi.csv
- Variabili:
  - PM2.5
  - PM10
  - NO2
  - SO2
  - CO
  - Ozone
  - AQI (target numerico)

---

## Task del progetto

1. Acquisizione dati (CSV)
2. EDA (analisi esplorativa)
   - statistiche descrittive
   - valori mancanti
   - correlazioni
3. Preprocessing
   - selezione feature
   - train/test split
   - scaling (StandardScaler)
4. Modellazione predittiva
   - Linear Regression
   - Random Forest Regressor
5. Valutazione modelli
   - MAE
   - MSE
   - R²
   - confronto grafico
6. Generazione report interpretativo (Ollama)

---

## Strumenti
- GSD → definizione specifiche pipeline
- OpenCode.ai → generazione codice automatica
- Colab → esecuzione pipeline manuale
- Ollama → interpretazione risultati

---

## Output attesi
- pipeline ML funzionante
- confronto tra modelli
- analisi prestazioni
- report finale automatico
