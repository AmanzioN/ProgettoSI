Progetto per corso sistemi intelligenti.

prof. - Scala

Studenti - Bondioli Davide, Amanzio Nicola

Questo progetto è un'applicazione che utilizza la libreria OSMnx per analizzare e visualizzare mappe stradali di regioni specifiche,
con l'obiettivo di trovare un percorso in grado di mediare tra costo e lunghezza del percorso in base a dei parametri

Il codice fornito implementa diverse funzionalità:
- Caricamento della regione d'interesse e delle città di partenza e arrivo:
      La regione di interesse viene caricata utilizzando la libreria OSMnx (OpenStreetMap NetworkX) specificando il nome della regione.
      Inoltre, vengono definiti i nomi delle città di partenza e arrivo per la ricerca del percorso ottimale (miglior rempo e miglior costo).
- Algoritmo A* per la ricerca del percorso ottimale:
      Viene implementato l'algoritmo A* per trovare il percorso ottimale tra la città di partenza e quella di arrivo.
      L'algoritmo tiene conto delle lunghezze degli archi e dei costi degli archi per calcolare il percorso ottimale.
- Funzioni per visualizzare la mappa e il percorso ottimale:
      Utilizzando Pygame, viene visualizzata la mappa stradale della regione con le strade colorate in base al peso del costo degli archi.
      I nomi delle città vengono mostrati sulla mappa per rendere la rappresentazione più leggibile.
      Inoltre, vengono disegnati cerchi gialli intorno alle città di partenza e arrivo.
      È possibile anche zoomare sulla mappa e trascinarla con il mouse.
- Calcolo del costo e della lunghezza del percorso ottimale:
      Viene calcolato il costo e la lunghezza del percorso ottimale trovato.
- Interazione utente:
      L'utente può interagire con l'applicazione tramite Pygame, utilizzando la rotella del mouse per zoomare,
      trascinando la mappa con il mouse e premendo il tasto spazio per visualizzare il percorso ottimale.
  
