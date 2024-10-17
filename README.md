# Emotion-Detection-Challenge-on-Twitter
## Description
This project was carried out for the hackathon dedicated to the Milan Digital Week by Open Data Playground. The sentiment analysis task involves a multiclass classification of 4 emotions:
1.   😠 **Anger**     (class 0)
2.   😂 **Joy**       (class 1)
3.   😀 **Optimism** (class 2)
4.   😞 **Sadness**   (class 3)
A dataset containing raw textual files of tweets collected from Twitter was provided.

My approach was to use a voting classifier. The project is based on several stages, including text preprocessing, tokenization, and merging the results of various machine learning models. In the end, the system produces a final prediction saved in a CSV file.

## Key Features
1) **Data analysis:** Histograms to understand the distribution of words based on emotions.
2) **Data preprocessing:** Stopword removal, text normalization, lemmatization.
3) **Data augmentation:** Applied a data augmentation technique by creating new text using synonyms of words (removed due to worse performance).
4) **Embedding:** Tested embedding with TF-IDF, Word2Vec, and pre-trained BART (best performance with TF-IDF).
5) **Integration of multiple models:** Combines predictions from different models.
6) **Voting system:** Determines the final prediction based on the mode of labels predicted by individual classifiers.


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Descrizione
Progetto svolto per l'hackaton dedicato alla Milano Digital Week da parte di Open Data Playground. [Secondo posto su 10 team]
Il task di sentiment analysis consiste in una classificazione multiclasse di 4 sentimenti:

1.   😠 **Anger**     (class 0)
2.   😂 **Joy**       (class 1)
3.   😀 **Optimism** (class 2)
4.   😞 **Sadness**   (class 3)

A disposizione è stato fornito un dataset contenente i file testuali grezzi dei tweet raccolti da Tweeter.

Il mio approccio è stato quello di utilizzare il voting classify. 
Il progetto si basa su diverse fasi, tra cui pre-elaborazione del testo, tokenizzazione, e fusione dei risultati dei modelli di machine learning. Alla fine, il sistema produce una previsione finale salvata in un file CSV.

## Funzionalità principali
1) Analisi dei dati: Istogrammi per capire la distribuzione delle parole in base alle emozioni
2) Data pre-processing: Rimozione Stopword, normalizzazione del testo, lemmatizzazione
3) Data agumentation: Usata una tecnica di data agumentation creando nuovo testo sfruttando sinonimi delle parole (rimosso per performance peggiori)
1) Embedding: Testato l'embedding con TFIDF, Word2Vec e Bart pre addestrato. (Performance migliori con TFIDF)
2) Integrazione di più modelli: combina le previsioni di diversi modelli
3) Sistema di votazione: determina la previsione finale basata sulla modalità delle etichette predette dai singoli classificatori
