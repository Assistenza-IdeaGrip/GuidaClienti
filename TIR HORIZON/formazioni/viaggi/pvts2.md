# COS'È IL PVTS2?

Il PVTS2 è un calendario che mi permette di creare e gestire i viaggi.        

> Per fare **ANALISI COSTI** devo comunque aprire i viaggi!

Sull'asse delle ordinate (Y) ci sono `TARGHE` (ed eventuali autisti assegnati) mentre sull'asse delle ascisse (X) ci sono i `GIORNI`.

# STRUTTURA FORMAZIONE:

- FILTRI VISUALIZZAZIONE
- BOTTONI
- IMPOSTAZIONI
  - COLORI
- CALENDARIO
  - MENU TASTO DESTRO

# FILTRI VISUALIZZAZIONE

![visualizzazione pvts2](https://github.com/Fucio992/GuidaTir/assets/139453658/2578b221-c6a5-45cc-bb17-08a2217a5185)

### DATA -> Datetime

Permette di selezionare la data di partenza per costruire la tabella.

### BOTTONE "OROLOGIO" -> Bottone

Permette di tornare alla data odierna.

### VISUALIZZA PER -> Menù a Tendina

Scegli cosa visualizzare nell'asse delle ordinate.

- MEZZI: visualizza per `Targhe` ed `Autisti` Abbinati.
- RIMORCHI: visualizza per `Targhe` rimorchi.
- AUTISTI: visualizza per `Autisti` e `Targhe` abbinate.
- CLIENTI: visualizza per `Clienti`.

### CATEGORIA MEZZO -> Menù a Tendina

Se in visualizza per hai selezionato `MEZZI` o `RIMORCHI` vedrai questo menù.         
Questo menù a tendina filtra per `Categoria`, campo che si trova nell'anagrafica **MEZZI**.

### QUALIFICA AUTISTA -> Menù a Tendina

Se in visualizza per hai selezionato `AUTISTI` vedrai questo menù.             
Questo menù a tendina filtra per `Qualifica Autista`, campo che si trova nell'anagrafica **AUTISTI** alla voce **Qualifica**.

### VISUALIZZA VETTORI -> Checkbox

Se flaggato nell'asse delle ordinate saranno visualizzati i vettori.

### ELEMENTO -> Testo

Questa casella di testo applica un filtro sui valori dell'asse delle ordinate.

*esempio: se scrivo AB e sono in visualizzazione per mezzi il programma mi farà vedere solamente i mezzi che hanno la targa che contiene "AB"*

### PAROLA CHIAVE -> Testo

Se valorizzo questo campo il programma evidenzierà i blocchi (unione riga-colonna) che contengono quel valore e nasconderà gli altri.

### MOSTRA LIBERI -> Checkbox

Se flaggato mi farà vedere solo le targhe/autisti che NON hanno viaggi programmati oggi.

# BOTTONI

![bottoni](https://github.com/Fucio992/GuidaTir/assets/139453658/825e3b1d-6fb3-4035-8a51-4a8fcd37cfda)

- STAMPA: Apre il modulo stampe.       
- INSERIMENTO RAPIDO: Permette di inserire rapidamente una conferma (con meno campi) che perà figurerà come "da completare" nel modulo conferme.      
- AGGIUNGI NUOVO: Apre il modulo conferme.
- AGGIORNA: Aggiorna la visualizzazione.
- LISTA ORDINI: Apre la schermata che mi permette di abbinare le conferme ad un autista/mezzo.

## ABBINAMENTO ORDINI

![assegna conferme](https://github.com/Fucio992/GuidaTir/assets/139453658/898c195e-4dd1-44ea-8efa-fddd713b9016)

In alto c'è un filtro di ricerca che permette di filtrare le conferme per data.

> Posso anche filtrare escludendo i vettori oppure mostrare tutte le conferme escludendo le date

### COME ABBINARE UN ORDINE:

Puoi selezionare un'ordine cliccandolo con il tasto sinistro oppure più di uno premendo shift o control (funziona come la selezione dei file).            
Una volta selezionato uno o più ordini puoi abbinare Motrice, Rimorchio ed Autista

Per Abbinare gli ordini devi premere su `ABBINA ORDINI`.

Se ho già creato un viaggio per una targa / autista posso comunque abbinare un ordine a quella coppia targa / autista ed in questo caso il programma mi chiederà se abbinare l'ordine al viaggio già esistente oppure creare un viaggio nuovo.

> Anche qui c'è la possibilità di gestire le colonne attraverso il bottone `GESTISCI COLONNE`.

# IMPOSTAZIONI

![impostazioni](https://github.com/Fucio992/GuidaTir/assets/139453658/5a02f230-f519-4cef-8e9b-69987e74c494)

Qui ci sono tutte le impostazioni configurabili del PVTS2.        
> Ci sono molte impostazioni che vanno configurate in base alle esigenze del cliente.          

### Visualizza dettagli Viaggio:

Qui posso selezionare i dati che vedrò all'interno dei rettangoli che rappresentano i viaggi.         

### Visualizzazione (Colori):

Qui posso scegliere i colori dei rettangoli che rappresentano i viaggi in base al loro stato. (I colori li trovo sul sito che viene linkato)

Ci sono quattro stati:
- Carico: nella giornata carico solamente
- Transito: il mio mezzo è già carico ed in transito verso il punto di scarico. (viene dopo una giornata di carico)
- Scarico: nella giornata scarico solamente
- Carico-Scarico: in giornata carico e scarico

# CALENDARIO

In questa visualizzazione posso vedere i viaggi associati ad una specifica targa, autista o rimorchio.

![calendario pvts2](https://github.com/Fucio992/GuidaTir/assets/139453658/93201e5b-81d1-4dae-8e47-9a64733359c0)

## MENU TASTO DESTRO

**CASELLINA VUOTA:**

Posso Aggiungere un nuovo `Ordine` (apre le conferme e mi aggancia in automatico motrice, autista e rimorchio) oppure un nuovo `Evento` (*esempio: riparazione*).

EVENTI MEZZO:
- Riparazione

EVENTI AUTISTA:
- Malattia
- Ferie

**CASELLINA CON UN VIAGGIO:**

- Annulla Viaggio -> Annulla tutto il viaggio disassociando le conferme inserite.
- Annulla Ordine -> Permette di rimuovere una conferma da un Viaggio.
- Getisci Viaggi -> Serve per decidere in che ordine visualizzare i viaggi.
- Gestisci Ordini -> Apre Ordinamento Punti.
- Visualizza Ordini -> Mi fa vedere gli ordini contenuti nel viaggio e se faccio doppio click li posso aprire direttamente nelle conferme.
- Spacca Tratta -> Posso aggiungere un punto di intermezzo fra tratta 1 e tratta 2 (la seconda tratta è da ripianificare).
- Sgancio Rimorchio -> Come spaccatratta ma la seconda tratta è già pianificata su un'altra targa.
- Cambio Targa -> Posso spostare la targa.
- Stampa Viaggio -> Apre le stampe.
- Stampa Cartacea -> Apre le stampe
- Taglia -> Taglia un Viaggio.
- Copia -> Copia un Viaggio.
- Incolla -> Incolla un Viaggio in una casella nuova.
- Autista Avvisato -> Aggiunge l'omino in Alto a Destra sul contenitore del viaggio che significa che l'autista è stato avvisato.
- Integra Ordine -> Aggiungi una conferma al Viaggio.

TRASFERIMENTI A VUOTO
Creano una conferma senza cliente con DDT `trasferimento`. 
Servono per muovere i rimorchi senza metterlo in conto ad un cliente (quindi con la spunta non fatturabile).        

# UTILITÀ:
## PER SISTEMARE GLI EVENTI SU PVTS2:
Da SSMS fare TRUNCATE delle tabelle PLN (Categorie e tipi).

# OPZIONI:

- **Visualizza solo Scarichi oggi**: Nei viaggi di più giorni anziché mostrare carico e scarico ripetuti in ogni giornata lavorativa scrive solo il carico nella giornata di carico, lo scarico nella giornata di scarico e transito per le giornate fra carico e scarico.
- **Visualizza Vettori all'Avvio**: Applica in automatico il filtro "Visualizza Vettori"


