# 🚀 Missione 00: Il tuo primo Push!

Benvenuto nel tuo primo vero progetto GitHub! 
Nel mondo del lavoro e dello sviluppo software, nessuno si scambia i file via email o con le chiavette USB. Si usa **Git** e **GitHub**. In questo esercizio imparerai il flusso di lavoro che useremo per tutto l'anno per scaricare i compiti, scriverli su CLion e consegnarli.

## Obiettivo
Creare una copia personale di questo progetto, scaricarla sul tuo computer, modificare il codice in C e "consegnarlo" (Push) su GitHub.

---

### Fase 1: Crea il TUO repository (Fallo su GitHub)
Se stai leggendo questo testo nel repository del Prof, devi prima creare la tua copia personale:
1. Clicca sul pulsante verde in alto a destra: **Use this template**.
2. Scegli **Create a new repository**.
3. Come nome del repository inserisci esattamente: `00-Setup-TuoCognome` (es. `00-Setup-Rossi`).
4. Assicurati che sia impostato su **Public** (o Private, a seconda delle indicazioni del prof) e clicca su **Create repository**.

Ora sei nel TUO repository. Copia l'URL che trovi nella barra degli indirizzi del browser (oppure clicca sul tasto verde "Code" e copia il link).

---

### Fase 2: Porta il codice su CLion (Clone)
Ora dobbiamo scaricare il codice sul tuo PC per poterci lavorare:
1. Apri **CLion**.
2. Nella schermata di benvenuto, clicca su **Get from VCS** (Version Control System). Se hai già un progetto aperto, vai su `File -> New -> Project from Version Control...`.
3. Nella casella "URL", **incolla il link** del tuo repository che hai copiato poco fa.
4. Clicca su **Clone**. CLion scaricherà i file e configurerà il progetto in automatico!

---

### Fase 3: Scrivi il codice in C
1. Nel pannello di sinistra (Project), fai doppio clic sul file `main.c` per aprirlo.
2. Troverai un programma vuoto. Il tuo compito è scrivere un semplice programma che stampi a schermo questa esatta frase (sostituendo il tuo nome):
   > "Ciao GitHub! Sono [Tuo Nome] e sono pronto per iniziare a programmare in C."
3. Testa il programma premendo il tasto verde ▶️ (Play) in alto a destra. Se la console in basso stampa la frase corretta, ci siamo!

---

### Fase 4: Consegna il compito (Commit & Push)
Il codice ora funziona sul tuo PC, ma dobbiamo mandarlo su GitHub per farlo vedere al Prof.
1. Su CLion, premi la combinazione magica: **`Ctrl + K`** (se hai Windows) o **`Cmd + K`** (se hai Mac). Si aprirà la finestra di Commit a sinistra.
2. Controlla che ci sia la spunta blu vicino al file `main.c` (significa "voglio inviare queste modifiche").
3. Nello spazio "Commit Message" scrivi un breve messaggio che descrive cosa hai fatto (es. *"Completato setup e aggiunto il saluto"*). Non lasciare mai questo spazio vuoto!
4. In basso, non cliccare solo su "Commit", ma clicca sulla freccina di fianco e scegli **Commit and Push...**
5. Si aprirà un'ultima finestrella, clicca sul pulsante azzurro **Push**.

🎉 **Fatto!** Torna sulla pagina del tuo repository su GitHub e ricarica la pagina: se vedi il tuo nuovo codice nel file `main.c`, hai appena completato con successo la tua prima consegna da vero sviluppatore!
