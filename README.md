# Emotion-Detection-Challenge-on-Twitter

## Descrizione
Progetto svolto per l'hackaton dedicato alla Milano Digital Week da parte di Open Data Playground.
Il task di sentiment analysis consiste in una classificazione multiclasse di 4 sentimenti:

1.   😠 **Anger**     (class 0)
2.   😂 **Joy**       (class 1)
3.   😀 **Optimism** (class 2)
4.   😞 **Sadness**   (class 3)

A disposizione è stato fornito un dataset contenente i file testuali grezzi dei tweet raccolti da Tweeter.

Il mio approccio è stato quello di utilizzare il voting classify.
Il progetto si basa su diverse fasi, tra cui pre-elaborazione del testo, tokenizzazione, e fusione dei risultati dei modelli di machine learning. Alla fine, il sistema produce una previsione finale salvata in un file CSV.

## Funzionalità principali
1) Pre-elaborazione del testo: applicata tecnica di tokenizzazione. Testato l'embedding con Word2Vec e Bart pre addestrato
2) Integrazione di più modelli: combina le previsioni di diversi modelli
3) Sistema di votazione: determina la previsione finale basata sulla modalità delle etichette predette dai singoli classificatori
