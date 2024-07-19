# FORMAZIONE CONFERME

Le conferme sono ordini CONFERMATI del Cliente che poi andranno in `fatturazione` e Viaggi.            
L'analisi costi NON viene fatta sulle conferme ma su VIAGGI.      

> Sono le spedizioni

> Se previsto da contratto posso importare le conferme tramite Excel.

## BARRA IN ALTO:

> Approfondisci solo tasti fino ad F6 poi il resto va approfondito solo in caso di necessità.       

Visualizazione e scelta conferme     
- Lente = Ricerca Conferme
- Foglio = Nuova conferma
- Fogli 1 = Duplica
- Fogli 2 = duplica avanzata -> Ha dei filtri
- Matita = Modifica
- Cestino = Elimina
- Stampante = Stampa ordini
- WhatsApp = Collega a WhatsAppWeb ed invia messaggio
- Spaccatratta
- Esporta
- Importa
- Scanner Documenti
- Stampa Etichetta (SERVE ETICHETTATRICE)
- Contrassegni
- Resi
- Assegni
- Giacenze
- Danni
- Bancali
- Riprezzamento -> In caso avessi sbaglito a fare listino lo premo e lui mi ricalcola in automatico i prezzi
- Nascondi Colonne: serve per limitare l'overflow di informazioni nei monitor piccoli
- Preventivo
- Formulario Rifiuti
- Duplica il ritiro
- Stampa allegati
- Gestione CMR
- C -> Switch Conferme (C) e Richieste (R)
- R/C -> Cambia richiesta in conferma
- Visualizza dati

> Su richiesta si può aggiungere il pulsante CV che permette di creare viaggi direttamente dalle conferme. 

## PARTE DI INSERIMENTO:

### CLIENTE:

Il cliente si richiama dalle Anagrafiche Clienti (Se premi enter richiama ricerca clienti avanzata).     
per confermare il cliente premi TAB così richiama anche il Codice cliente (IMPORTANTE).

> Se premi su cliente ti apre `ANAGRAFICHE CLIENTE`.

> Se flaggo non fatturare, la conferma non apparirà nel modulo fatturazione.

> Date Importanti:                 
> DataR: Data RICHIESTA -> La data in cui ricevo la richiesta d'ordine da parte del cliente.        
> DataC: Data di Carico                   
> DataS: Data di Scarico          

- SEDE:    
Qui va inserita la sede di fatturazione del Cliente.         
Le sedi le trovo in basso nell'anagrafica Clienti.

- VETTORE:
Qui vanno inseriti eventuali Vettori.

- AGENTE:  
Qui vanno inseriti eventuali Agenti.

> Il campo network va spiegato solo a chi lo ha anche se in genere viene auto valorizzato.

> In caso posso valorizzare in manuale la commessa ma dev'essere un codice UNIVOCO altrimenti mi si legano gli ordini.
> *Esempio: se creo una commessa 1234 con 2 ordini e dopo 1 anno creo un'altro ordine con commessa 1234 i 3 ordini mi si legano.* 

### CARICO/SCARICO:

Per prima cosa si inseriscono `DATA` ed `ORA` di carico/scarico.   
Se premi `CL` verranno richiamati i dati del Cliente.
Se premi `SV` si svuotano i campi.

> Se premo su `TASSATIVO` significa che il carico / scarico DEVE essere eseguito entro una specifica Data / Ora.
> Sulla casella di testo che appare posso aggiungere delle note.     

Dopo aver scritto i dati di un nuovo Mittente/Destinatario:
Se premi su Mittente/Destinatario hai la possibilità di salvare i dati in anagrafiche Mittenti/Destinatari (eventualmente come luogo comune o/e destinatario).            
> Se lo premo dopo aver richiamato un mitt/dest già inserito posso aggiornare.

- Solo Comuni: se è flaggato all'inserimento di un Mittente/Destinatario aggiunge un Mitt/Dest comune a tutti i Clienti altrimenti funge da filtro per i menù a tendina

(Apri): apre le anagrafiche mittenti/destinatari     
> Se salvi il mitt/dest senza luogo viene fuori un'errore.

HUB -> Fa riferimento ad HUB di magazzino (CODICE del magazzino)

> Casella di testo a destra di flag `SOLO COMUNI` mostra il codice del destinatario.

> Flag Booking segnala che il campo Note Carico/Scarico 2 è un campo booking. 

Zona: Viene preimpostata su mittente destinatario e può essere utilizzata anche come listino.    
*Esempio: Provincia di Venezia è vasta quindi se voglio posso scinderla in varie zone*

### DETTAGLI:

- In Booking posso inserire i codici prenotazione
- Motrici, Rimorchi ed autisti posso anche ometterli perché sono previsti e non definitivi, I definitivi li seleziono in fase di viaggio.           
  > Se premo su campi mi apre le relative anagrafiche.           
- Il flag affianco a Motrice è un filtro che permette di selezionare solamente i mezzi dei `VETTORI`.
- DDT -> Può essere inserito in un secondo momento con flag "da completare"
- KM -> Posso inserire i km manualmente oppure calcolarli con le mappe

> ALTRI DETTAGLI va su XML mentre le Note sono solo note interne.

\# FLAG DA COMPLETARE:     

Flag + Descrizione.      
Mi permette di contrassegnare un ordine dome da completare,        
gli ordini "da completare" NON possono essere Fatturabili.

### PRODOTTI:

Il bottone "+" permette di aggiungere una nuova riga alla tabella prodotti.       
Se fai Doppio Click su Prodotti si apre il form per la personalizzazione delle colonne.       
\# spiega come salvare i template

- UM -> Permette di inserire le unità di misura (ex: bancali o colli).     

- Il bottone prodotti permette di creare delle anagrafiche prodotti che possono essere poi richiamate.       

> Lista Formulario serve per chi trasporta rifiuti.

> Area Business mi serve per l'analisi csti per suddividere le conferme in base all'area di appartenenza.     

### PREZZI:

> Sede Competenza: viene utilizzato di solito nel caso in cui ci siano filiali ma dipede dalla configurazione.
> Viene preso in gestione da parte di una determinata sede per una gestione interna in caso di multi-sede (qui vanno le MIE sedi).

Premi "+" per inserire una nuova riga di prezzo.      
Puoi inserire i Prezzi Manualmente oppure dai listini (ma si vedranno più avanti)
       
       
Da qui eventualmente puoi anche creare Sconti/Maggiorazioni

> NO prezzo cliente -> mi serve per bypassare il Listino nel caso in cui per una specifica conferma volessi fare per esesmpio un prezzo concordato anzichè prendere il prezzo dal listino.
> Idem per NO Prezzo Vettore.

> Per creare sconto/maggiorazione su riga devo selezionare la riga altrimenti NON mi popola il campo "SU".
> In alternativa posso flaggare "su totale".                

## COLONNA DI SINSTRA:          

Qui sono mostrate le ultime 20 conferme.    
Per vederne di più eventualmente va fatta una modifica.

## MULTICARICO/SCARICO:
  
Se ho più punti di scarico o carico posso creare una `COMMESSA` che comprende più conferme.      
POSSO FARLO IN 2 MODI:    
- Premi "+" a fianco di Carico o Scarico
- In colonna a destra seleziona Flag e premi "+"
    -  Carico -> la nuova conferma mantiene il precendente punto di Scarico
    -  Scarico -> la nuova conferma mantiene il precendente punto di Carico
    -  Entrambi -> la nuova svuota i precendenti punti di Carico e Scarico
    -  Inverti -> la nuova conferma inverte i precendenti punti di Carico e Scarico
    -  Duplica -> la nuova conferma mantiene i precendenti punti di Carico e Scarico
 
Nella colonna di Destra posso vedere il resoconto del mio viaggio in caso di Multiscarichi.

> In caso di multiscarico NON premere il bottone CV ma premi `Crea Viaggio per la Commessa` nella colonna di Destra.
> Perché il bottone CV crea un viaggio per l'ordine selezionato mentre `Crea Viaggio per la Commessa` crea un viaggio con tutti gli ordini facenti parte della commessa specificata.              


## RICERCA CONFERME:
- Posso Filtrare per data, carico, scarico, richieste, cliente, sede....     
- Se uso spaccatratte posso visualizzare qui le singole tratte.      
- In Opzioni ho dei filtri avanzati
- Se premo O posso personalizzare la visualizzazione delle colonne
- Per aggiornare dopo cambiamenti devo premere ancora "Cerca"
- Posso variare le personalizzazioni delle colonne per utente
- Posso cambiare schemi di visualizzazione nel dropdown `Schema Visualizzazione`
- FILTRI AVANZATI: fai click sinistro su una cella e poi click destro sull'intestazione della colonna      
  Mostra `OR` e vari filtri/comparatori

Su Opzioni Avanzate se flaggo "MODIFICA DDT" posso modificare il DDT direttente dalla ricerca conferme.        
> Questo è utile se per esempio carico tutti i DDT a fine mese (così non mi devo aprire le conferme una dopo l'altro).        

- Flag Completo: esclude le conferme "da completare"
- Controllata: Colora di verde le conferme controllate (è un flag su una colonna della tabella)
