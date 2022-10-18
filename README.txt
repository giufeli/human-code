Scegliere cosa guardare su Netflix

/* APPLICAZIONE FUNZIONALE ALL'INTERNO DI NETFLIX */


SE (so cosa guardare)
- Riproducilo
 FINE SE

ALTRIMENTI
- Avvia processo di ricerca

Comunico all'algoritmo il TEMPO che ho a disposizione e le CATEGORIE che potrebbero interessarmi

Sfoglia nel catalogo dei titoli disponibili

SE (il titolo rispecchia i parametri TEMPO, CATEGORIE e NON è stato gia visualizzato in procedenza)
- Proponilo all'utente

ALTRIMENTI
- Eliminalo dal catalogo di ricerca
- Riparti dal primo punto (*Avvia processo di ricerca*)

SE (il titolo non ci piace)
- eliminalo dal catalogo di ricerca
- Riparti dal primo punto (*Avvia processo di ricerca*)
    FINE SE

SE (il titolo ci piace)
- Termina il processo di ricerca
- Riproducilo
 FINE SE   

FINE


