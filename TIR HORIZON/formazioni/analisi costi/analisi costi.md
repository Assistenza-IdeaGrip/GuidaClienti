# SCOPO FORMAZIONE:

Questa formazione permette al cliente di capire come inserire le varie spese e come poter verificare se uno specifico viaggio porta un profitto oppure una perdita in modo da decidere se farlo o meno o se eventualmente 
aumentare il prezzo.       

# COM'È STRUTTURATA LA FORMAZIONE ANALISI COSTI:

Si spiega come inserire i vari costi:
- Mezzi/Rimorchi
- Autisti
- Rifornimenti
- Pedaggi

Poi si spiega come generale la scheda spese viaggio e come leggerla per vedere i vari costi.           


# MEZZI/RIMORCHI:

La prima cosa da fare all'interno dell'anagrafica mezzi è inserire il numero di `Giorni Lavorativi Mensili` che dovrebbero coincidere con quelli dell'autista che li guida.       

Le spese relative a mezzi e rimorchi si trovano premendo sul pulsante `SPESE` all'interno dell'anagrafica mezzi.

![spese mezzi](https://github.com/Fucio992/GuidaTir/assets/139453658/ec592761-567f-40f2-8d31-896e26f35987)

Una volta aperta la scheda di `Gestione Spese Mezzi` premendo in "*visualizza tutti*", CATEGORIA e ricerca, posso filtrare i mezzi per categoria.      

![filtro categoria mezzo](https://github.com/Fucio992/GuidaTir/assets/139453658/67bfc757-afa8-488e-9893-91e78256595c)

Così facendo posso riportare una specifica spesa su tutti i mezzi che ho selezionato.       

## SPESE MEZZO/RIMORCHIO:

Ai fini dell'analisi costi qui dovrei riportare tutte le spese del mezzo suddivise per Tot tempo oppure Km.       

> In caso di spese Kilometriche per comodità le posso inserire dal camioncino perchè fa automaticamente il calcolo spesa / numero km ma posso anche scrivermi la spesa manualmente se so ho già fatto la divisione.      
> *esempio spese kilometriche: gomme, tagliando...*
>              
> ![camioncino](https://github.com/Fucio992/GuidaTir/assets/139453658/dd7dc066-7429-4ac3-b8e6-a63441789606)

Per abbinare una spesa a più mezzi devo selezionare la voce `visualizza tutti` in alto a sinistra, flaggare i mezzi dove voglio riportare la spesa (colonna `ABBINA`) ed infine premere `Riporta Spesa`.  

![riporta spesa](https://github.com/Fucio992/GuidaTir/assets/139453658/6178ed97-5e1a-4672-9338-3483a0b7ffbc)

> Usando le categorie posso escludere i vettori

# AUTISTI:

Le spese lorde relative agli autisti si inseriscono dall'anagrafica autisti nella scheda `Dati Economici`.            
Qui devo inserire lo stipendio medio dell'autista e la media dei contributi. (è consigliabile fare la media annuale quindi tot costi / mesi)             

ATTENZIONE: è importante inserire la media dei giorni lavorativi dell'autista.            

> Posso fare un analisi costi a consultivo inserendo le singole buste paga nella scheda che si apre premendo il simbolino **€**
> Per fare in modo che il programma consideri le singole buste paga devo attivare il custom 331.      

> Le buste paga si possono importare per codice (con il codice interno generato da TIR)

Premendo `Gestione Spese` si apre una scheda che mi permette di aggiungere altre spese relative all'autista come Tredicesima, Quattordicesima e TFR.



# SPESE GESTIONALI:

PRIMA DELLA FORMAZIONE: **ATTIVARE** i custom 621 e 351 in GestioneCustom \ Spese Viaggio.

Il modulo si trova in SPESEmenu -> Spese Gestionali.

![gestione_spese](https://github.com/Fucio992/GuidaTir/assets/139453658/3438b621-400e-4e65-99ec-0b1da7c573a0)

E si suddivide in:
- Lista Spese:

![lista spese](https://github.com/Fucio992/GuidaTir/assets/139453658/99cc290b-f4ec-4c71-b3cb-efe2f54cd2ea)

- Visualizzazione Inserimenti Spese:

![visualizzazione inserimenti](https://github.com/Fucio992/GuidaTir/assets/139453658/b9909078-0987-4ecd-983d-a34d2f14741c)

La prima cosa da fare è inserire le varie voci spese nella scheda che si apre premendo il quadratino a destra di spesa ed inserire i GG nel campo di testo in alto a destra.

> GG: fa riferimento ai giorni di suddivisione per le spese di default (es: se l'azienda è aperta da lunedì a venerdì sarà 22).         
> Ogni volta che creo una nuova spesa mi prendè in automatico questo valore.

Poi si seleziona una spesa in `Seleziona Spesa` e dopo aver premuto Tab e la matita in alto si inserisce:
- Prezzo
- Periodo
- Giorni Suddivisione (se l'ufficio è aperto da lunedì a venerdì saranno 22)

> Le Spese Gestionali possono essere gestite Annualmente o Mensilmente ma nel caso di spesa annuale i giorni lavorativi saranno ad esempio 22 * 12 (se l'azienda è aperta da lunedì a venerdì).

Nella parte a sinistra si può vedere i vari inserimenti fatti nei vari mesi.

Il Filtro Dal - Al svuota i campi sotto alla lista spese.

> Riporta Costi serve a riportare una spesa (selezionata) da un mese ad un'altro



# RIFORNIMENTI:

Per vedere i rifornimenti devi andare in scheda Veicoli e poi premere Rifornimenti Gasolio.

Il programma inizia a calcolarmi le media dal secondo rifornimento in poi.       

# CARICARE LA CISTERNA:

Per caricare la cisterna devo premere su nuovo e segnare il rifornimento con i vari dati che lo compongono *(DATA, ORA, LITRI, COSTO AL LITRO, FORNITORE, DDT, N°FATTURA)*.

![rifornimenti interni](https://github.com/Fucio992/GuidaTir/assets/139453658/9290e61a-69de-4ea5-97aa-aece6b29ba27)

Se cambio o cancello un rifornimento perché ho sbagliato ad inserirlo devo premere sul bottone `Ricalcola`:

![ricalcola](https://github.com/Fucio992/GuidaTir/assets/139453658/799723df-90af-4d59-942c-1c89bfc94bc9)

## RIFORNIMENTI:

![rifornimenti](https://github.com/Fucio992/GuidaTir/assets/139453658/69707a37-1026-4227-a819-9252923a9330)

## AGGIUNGERE UNA CISTERNA:

La quantità in cisterna si aggiorna in automatico mano a mano che inserisco i rifornimenti.          
La quantità totale della cisterna la devo mettere a mano.             

## RIFORNIMENTO INTERNO:

Per aggiungere un rifornimento interno mi basta premere su Nuovo e compilare tutti i campi.     

I campi più importanti sono quelli relativi al Mezzo ed al tipo di rifornimento.      
In caso di rifornimento interno devo scegliere quale cistena sto utilizzando.        

in `Tipo Carico` posso scegliere se il mio rifornimento è un rifornimento a Tappo oppure un semplice rabbocco.       

> ATTENZIONE: per aggiornare il campo `Disponibilità Sede` devo riportare la quantità di litri del mio rifornimento nel campo testuale sotto ad "aggiungi e togli" ed usare i bottoni affianco per aggiungere o togliere.               
> (Aggiungo se ricarico la cisterna e Tolgo se ricarico un Mezzo)          

## RIFORNIMENTO ESTERNO:

Uguale al rigornimento interno solo che non metterò la cisterna e riporterò invece il Fornitore che mi ha erogato il servizio.     

# PEDAGGI:

Dopo aver creato i viaggi posso importare i relativi pedaggi.    

ATTENZIONE: in fase di importazione il programma confronta la data del pedaggio con quella dei viaggi relativi a quella specifica targa.             
per questo è molto importante che il pedaggio ricada fra data di carico e scarico di un viaggio altrimenti NON lo aggancia.            

Bisogna configurare i tracciati per le importazioni.        



# VIAGGI: 

Nei viaggi vanno inseriti `KM INIZIALI`, `KM FINALI`, orari di `PARTENZA` ed `ARRIVO`, `TARGA MOTRICE`, `TARGA RIMORCHIO` (se presente) e `NOME AUTISTA`.          

Ci sono diversi custom che si possono attivare:

 - **417**: Se faccio più viaggi in un giorno divide le spese per il numero di Viaggi.
 -  **418** Se faccio più viaggi in un giorno divide i km per il numero di Viaggi.
 - **662** Forza i Km Iniziali e Km Finali a zero, da attivare insieme a 442.        
 - **442** Se i Km Iniziali ed i Km Finali sono a 0 prende i Km dalla `Mappa`.



# SCHEDA COSTI VIAGGIO:

Qua troveremo le spese dei pedaggi, rifornimenti, spese mezzo e spese autista e spese di gestione, all’interno della spesa del viaggio.

Si possono rielaborare le spese eventualmente su tutti i viaggi con filtro per periodo, togliendo il flag e cliccando ricalcola.

 - **409 Calcola gasolio dei mezzi quindi la media dichiarata in anagrafica**
 - **688 Costo medio per periodo (da attivare con 409)**
 - **672 Media Rif. Del Mese (da attivare con 409)**
 - **657 Media rifornimento dell’anno**
 - **308 Storico spese mezzi**

Gestire i KM a vuoto o con le mappe mettendo le due operazioni alla fine e all’inizio, oppure con i satellitari calcola direttamente tutti i KM da quando parto dalla prima messa in moto dall’azienda al ritorno del mezzo in azienda.

Come calcolare spese viaggio multiple:

Togli il flag a fianco di rielabora e premi il tasto.
Seleziona periodo e viaggi e verranno generate in automatico le schede spese viaggio

![rielabora schede viaggio](https://github.com/Fucio992/GuidaTir/assets/139453658/9cd9d3ef-c731-41ba-928b-fabb415fb08c)



# RICERCA SPESE VIAGGIO:

Si trova in Personale -> Ricerca Spese Viaggio:

![spese viaggio](https://github.com/Fucio992/GuidaTir/assets/139453658/eaa52a94-46fa-4420-a547-2c4c2939d155)

Riassume le schede spese viaggio generate per i vari viaggi inseriti.         
Nella parte destra c’è un riepilogo dei margini e delle spese.

> Da qui è possibile lanciare la stampa `riepilogo spese viaggio`.







## **RIPARAZIONI**

ATTENZIONE CON LE RIPARAZIONI PERCHÉ SFASANO I DATI!

Le riparazioni, vanno inserite le spese che è imputata al mese corrente, è possibile splittare l’importo per dividere su più mesi, cliccando PIANO INTERVENTO nelle riparazioni, posso attribuire il cambio a più mesi, imputando la spesa della riparazione a più mesi.

Oltre i 512 euro si possono spalmare su più esercizi.

Per fare andare le riparazioni sulla scheda spese bisogna attivare il custom 352


## **SPESE PARAMETRICHE**

L’eseguibile SPESEGESTPARAM.EXE

La spesa gestionale ripartita sull’area di business

Nel campo spese si inseriscono le spese che possono essere diversamente i centri di costo

Quando si inseriscono/importano le fatture passive, definisce a quale centro di costo appartiene la fattura e quindi il programma la riporta nel piano dei conti, e quindi la suddivide per area di business.

Solitamente la usano delle aziende un po’ più strutturate e seguono più aree di business, è più vincolante anche nell’inserimento della conferma.

Da far vedere solo nel caso di richiesta, analizzare la situazione ed eventualmente programmare la formazione.





