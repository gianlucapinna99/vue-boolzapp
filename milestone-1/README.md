# Bollzapp

- Applicazione web di messaggistica realizzata con js, html e CSS utilizzando VueJS.

- Realizzata in milestones, strutturate in questo modo:

# MILESTONE 1

- Replica della grafica con la possibilità di avere messaggi scritti dall’utente (verdi) e dall’interlocutore (bianco) assegnando due classi CSS diverse

- Visualizzazione dinamica della lista contatti: tramite la direttiva v-for, visualizzare nome e immagine di ogni contatto

---

Realizzo il layout in html e css, lasciando tutto statico.
Creo 2 classi per i diversi messaggi degli utenti, uno per l'utente che sta usando l'app e l'altro per chi sta inviando il messaggio, con unica differenza colore.

Creo un array che contenga le informazioni dei contatti (Nome, Immagine,) e con un ciclo for lo collego al mio html utilizzando vuejs, in modo che le informazioni dei contatti vengano visualizzate sulla nav laterale dinamicamente.


# MILESTONE 2

- Visualizzazione dinamica dei messaggi: tramite la direttiva v-for, visualizzare tutti i messaggi relativi al contatto attivo all’interno del pannello della conversazione

- Click sul contatto mostra la conversazione del contatto cliccato

---

Realizzo il layout in html e css, lasciando tutto statico.
Creo 2 classi per i diversi messaggi degli utenti, uno per l'utente che sta usando l'app e l'altro per chi sta inviando il messaggio, con unica differenza colore.

Creo un array che contenga le informazioni dei contatti (Nome, Immagine,) e con un ciclo for lo collego al mio html utilizzando vuejs, in modo che le informazioni dei contatti vengano visualizzate sulla sidebar laterale dinamicamente.

# MILESTONE 3

- Aggiunta di un messaggio: l’utente scrive un testo nella parte bassa e digitando “enter” il testo viene aggiunto al thread sopra, come messaggio verde

- Risposta dall’interlocutore: ad ogni inserimento di un messaggio, l’utente riceverà un “ok” come risposta, che apparirà dopo 1 secondo.

---

# MILESTONE 4

- Ricerca utenti: scrivendo qualcosa nell’input a sinistra, vengono visualizzati solo i contatti il cui nome contiene le lettere inserite (es, Marco, Matteo Martina -> Scrivo “mar” rimangono solo Marco e Martina)

---
