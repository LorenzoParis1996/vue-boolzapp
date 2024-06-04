Boolzapp - a (not very) innovative messaging platform


Nome Repo: vue-boolzapp
Milestone 1
Replica della grafica con la possibilità di avere messaggi scritti dall’utente (verdi) e dall’interlocutore (bianco) assegnando due classi CSS diverse
Visualizzazione dinamica della lista contatti: tramite la direttiva v-for, visualizzare nome e immagine di ogni contatto

- ricreo layout, e tramite un ciclo v-for, stampo e visualizzo nome e immagine dei contatti

Milestone 2
Visualizzazione dinamica dei messaggi: tramite la direttiva v-for, visualizzare tutti i messaggi relativi al contatto attivo all’interno del pannello della conversazione
Click sul contatto mostra la conversazione del contatto cliccato

- mi creo delle funzioni in cui gli indici si interfacciano e posso navigare col click nella lista contatti, e col ciclo v-for, quando clicco su un contatto, mi stampa i messaggi della chat del contatto cliccato

Milestone 3
Aggiunta di un messaggio: l’utente scrive un testo nella parte bassa e digitando “enter” il testo viene aggiunto al thread sopra, come messaggio verde
Risposta dall’interlocutore: ad ogni inserimento di un messaggio, l’utente riceverà un “ok” come risposta, che apparirà dopo 1 secondo.

- creo una funzione in cui posso creare un messaggio premendo enter, e dentro la funzione di creazione messaggio, aggiungo una funzione timer in cui dopo 1 secondo ricevo una risposta impostata da me

Milestone 4
Ricerca utenti: scrivendo qualcosa nell’input a sinistra, vengono visualizzati solo i contatti il cui nome contiene le lettere inserite (es, Marco, Matteo Martina -> Scrivo “mar” rimangono solo Marco e Martina)

- creo una funzione in cui tramite input filtra le lettere dei contatti (in minuscolo), e nel v-for della li non richiamo piu' contacts ma la funzione di ricerca (cambiando anche il value)

Milestone 5 - opzionale
Cancella messaggio: cliccando sul messaggio appare un menu a tendina che permette di cancellare il messaggio selezionato

Visualizzazione ora e ultimo messaggio inviato/ricevuto nella lista dei contatti 

Consigli utili:
Si possono trascurare le scrollbar verticali, sia nel pannello dei messaggi, che nella lista dei contatti
I pulsanti e le icone possono non funzionare (a parte l’invio del messaggio)
Per gestire le date, può essere utile la libreria Luxon
La struttura dell’array dei contatti potrebbe avere questa forma
