# NLP & Topic Modeling: Email Classification and Text Analysis

## Descrizione del Progetto
Questo progetto sviluppa una pipeline avanzata di **Natural Language Processing (NLP)** per la gestione automatizzata dei flussi di comunicazione via email. L'obiettivo è duplice: implementare un sistema di classificazione accurato per filtrare contenuti non desiderati (Spam) ed estrarre informazioni strutturate dai testi per identificare trend e tematiche ricorrenti.

## Metodologia e Workflow Tecnico
L'analisi integra diverse tecniche di Machine Learning e linguistica computazionale:

1. **Text Classification:** implementazione di un modello di classificazione binaria per distinguere tra comunicazioni legittime e spam, ottimizzando la precisione per ridurre i falsi positivi.
2. **Topic Modeling (LDA):** utilizzo dell'algoritmo *Latent Dirichlet Allocation* per estrarre automaticamente i temi dominanti dai messaggi. Questa tecnica permette di categorizzare grandi volumi di testo senza supervisione manuale.
3. **Analisi Semantica:** calcolo della coerenza tra i topic estratti per valutare l'omogeneità dei flussi informativi e la qualità della clusterizzazione.
4. **Information Extraction (NER):** applicazione di tecniche di *Named Entity Recognition* per identificare ed estrarre nomi di organizzazioni e brand menzionati nei testi, utile per analisi di mercato o monitoraggio del brand.

## Tech Stack
* **Linguaggio:** Python
* **NLP & ML:** `Scikit-learn`, `Gensim` (per Topic Modeling), `spacy`.
* **Data Science:** `Pandas`, `NumPy`, `Matplotlib` per la visualizzazione dei cluster.

## Impatto e Applicazioni Business
- **Customer Support:** categorizzazione automatica delle richieste in base al topic rilevato.
- **Brand Monitoring:** estrazione automatica di competitor o partner menzionati in grandi dataset testuali.
- **Data-Driven Insights:** trasformazione di dati non strutturati (testo libero) in dati strutturati pronti per la reportistica aziendale.

## Struttura del Repository
- `Progetto_Filtro anti spam.ipynb`: notebook completo con preprocessing dei dati, addestramento dei modelli e visualizzazione dei risultati.
