# Analisi Statistica Multivariata: Heart Failure Clinical Records

Questo progetto presenta un'analisi statistica rigorosa condotta su un dataset clinico relativo a pazienti affetti da insufficienza cardiaca. L'obiettivo è esplorare le relazioni tra variabili cliniche e identificare pattern predittivi per la mortalità attraverso tecniche di statistica descrittiva e inferenziale.

## Metodologia e Tecniche Applicate
L'analisi segue un workflow strutturato per estrarre il massimo valore dai dati clinici:

1. **Analisi Descrittiva (EDA):** Pulizia del dato, gestione dei missing values e studio delle distribuzioni delle variabili biometriche (Frazione di eiezione, Creatinina, Età, ecc.).
2. **Riduzione della Dimensionalità (PCA):** Applicazione dell'Analisi delle Componenti Principali per visualizzare la varianza dei dati e identificare le variabili con maggior potere informativo.
3. **Clustering:** Implementazione di algoritmi di clustering per segmentare i pazienti in gruppi omogenei in base al profilo clinico, facilitando l'individuazione di pattern di rischio.
4. **Modellazione Statistica:** Utilizzo della **Regressione Lineare** per studiare l'impatto delle variabili indipendenti sulla sopravvivenza e validare le ipotesi statistiche (analisi dei residui e p-value).

## Stack Tecnologico
* **Linguaggio:** R
* **Framework:** RMarkdown
* **Librerie Utilizzate:**
  * `FactoMineR` & `factoextra`: Per l'analisi multivariata e la visualizzazione avanzata della **PCA**.
  * `NbClust`: Per la determinazione del numero ottimale di cluster tramite indici statistici.
  * `psych` & `corrplot`: Per l'analisi descrittiva e la visualizzazione delle matrici di correlazione.
  * `scatterplot3d`: Per la rappresentazione spaziale dei dati in tre dimensioni.
  * `knitr`: Per la generazione del report dinamico.

## Documentazione
* `Report.Rmd`: Codice sorgente documentato.
* `Report.pdf`: Relazione completa con interpretazione dei risultati e visualizzazioni grafiche avanzate.
* `heart_failure_clinical_records_dataset.csv`: Dataset reperito su kaggle

---
*Progetto realizzato per l'esame di **DATA ANALYSIS AND STATISTICAL MODELING**.*
