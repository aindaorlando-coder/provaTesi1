# Roadmap del progetto

## Fase 1: Ingestione dati
- Caricamento datasetDelhi.csv
- Verifica struttura dati (colonne, tipi)
- Controllo valori mancanti

---

## Fase 2: Analisi esplorativa (EDA)
- Statistiche descrittive (media, deviazione standard)
- Analisi valori mancanti
- Analisi correlazioni tra variabili
- Visualizzazioni (istogrammi, heatmap)

---

## Fase 3: Preprocessing
- Selezione feature (PM2.5, PM10, NO2, SO2, CO, Ozone)
- Definizione target (AQI)
- Train/test split (80/20)
- Scaling delle variabili numeriche (StandardScaler)
- Attenzione a evitare data leakage

---

## Fase 4: Modellazione predittiva
- Regressione Lineare
- Random Forest Regressor
- Training dei modelli su training set

---

## Fase 5: Valutazione modelli
- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- R² score
- Confronto grafico tra modelli

---

## Fase 6: Interpretazione e report
- Analisi dei risultati dei modelli
- Confronto prestazioni
- Interpretazione delle feature più influenti
- Generazione report finale con Ollama

## Fase 6: Output finale
- Grafici finali
- Report interpretabile
- Prototipo pronto per demo
