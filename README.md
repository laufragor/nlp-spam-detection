# nlp-spam-detection
Identificare le email di tipo SPAM sulle quali poi effettuare analisi contenutistiche.

# Descrizione
Viene fornito un dataset di email etichettate come SPAM o non-SPAM. Si procede ad:
* Addestrare un classificatore per identificare le email SPAM
  * Preprocessing testo e codifica testo con tf-idf, valutazione risultati
* Individuare i topic principali tra le email SPAM con la libreria `gensim`
* Calcolare la distanza semantica tra i topic ottenuti
* Estrarre dalle email non-SPAM le organizzazioni presenti con `spacy`
