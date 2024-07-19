# FORMAZIONE FATTURAZIONE

La Fatturazione parte dalle Conferme.       
Se le conferme sono inserite male qui appariranno Errori.       

**Per aprire il Modulo Fatturazione:**          
AMMINISTRAZIONE -> FATTURAZIONE          

Il modulo si compone di due schede: `Selezione` e `Fatture`.





## SELEZIONE:

### VISUALIZZA CONFERME:

Qui puoi filtrare le conferme.

FILTRI:    
- Per DATA -> Da - A
- Per Importo -> Da X € a Y €
- Per Azienda -> In caso di Multiaziendale

Posso anche Filtrare per CLIENTE o VETTORE (con vari dati disponibili).

Per selezionare le conferme mi basta spuntare la casella `Sel`.                  
Con Doppio Click su NumRic posso aprire la conferma, se non si apre controlla se nella prima tendina sopra alla tabella c'è scritto `CONFERME`.               

> Le conferme segnate in giallo hanno il flag da `DA COMPLETARE` e NON posso fatturarle finchè non le completo.        


### CRITERI DI FATTURAZIONE:

Qui posso modificare la nomenclatura per le fatture.       
*esempio: 23A0001*
- 23 = Anno
- A = Carattere Aggiuntivo
- 0001 = Progressivo Fattura

CAMPI:        
- Anno -> qui si inserisce l'anno in corso.     
- Carattere Aggiuntivo -> qui si può inserire un numero oppure una lettera che mi permette di identificare le fatture.
- Data Fattura -> La data della Fattura.
- Nr. Fattura -> Progressivo Generato


## COME CREARE FATTURE:

Basta Selezionare le conferme che mi interessano e premere sulla `MATITA`.         
Dopo aver premuto sulla Matita le Fatture appariranno nella scheda `FATTURE`.           

> Il programma crea una fattura per ogni cliente.      

Se premi sul Foglio puoi generare una Fattura Manuale.     

> Nel caso di Fatture Esterne o Note di Accredito o Debito posso fare delle Fatture Manuali.

- FATTURE MANUALI: Appariranno in Verde
- NOTE DI CREDITO O DEBITO: Appariranno in Azzurro

Su `Tipo Fattura` posso scegliere se fare una Fattura Manuale o Note di Credito o Debito.       
Quando Creo una Fattura Manuale devo premere su "+" per aggiungere una nuova riga di prezzo.        

> Per le Fatture è indispensabile che siano segnati SDI o PEC in Anagrafiche

> Se cancelli le fatture NON elimini anche le conferme.       

## FATTURE:

Qui posso esportare le fatture da inviare allo `SDI` oppure posso stampare le fatture e crearmi una copia PDF e/o cartacea.

> Se metto il numero solo su `Dalla` e premo cerca mi popola automaticamente il campo `Alla`.      

### VISUALIZZA FATTURE:

Come nella scheda di Selezione anche qui posso filtrare le fatture per data e numero fattura.

> Se selezioni fatture e clicchi su matita ti apre la fattura.      

### RIEPILOGO:

Dati riepilogativi delle Fatture filtrate.         

- Se premi sulla `Matita` puoi modificare la fattura.

In fase di modifica della Fattura puoi inserire eventuali aggiunte.           
*esempio: bollo virtuale con relativa esenzione*

## GENERARE XML:
Per Generare il file `XML` da inviare all'agenzia delle entrate devo cliccare sull'icona con il `LUCCHETTO`.       
Una volta cliccato il lucchetto si aprirà la scheda tracciati.

> ??? A fianco del lucchetto posso generare i file Ri.BA da importare in Home Banking.

> Contabilizza le Fatture SOLO quando XML è giusto e senza errori di scarto.

- Controlla Partita IVA e cartella di destinazione del file XML generato (percorso di default: `C:\Import1\`)
- Controlla Anno di Esercizio ed IVA
- Controlla pagamento IVA
- **IMPORTANTE** Controllare il `TIPO FATTURA`: *esempio TD01 = Fattura generica* -> Per problemi sentire il commercialista.
- Premere su `FATTURA ELETTRONICA`

> Si sconsiglia di inserire allegati in quanto potrebbero appesantire troppo il file XML e questo potrebbe essere scartato dallo SDI.           

Ora si Aprirà una scheda riepilogativa in cui posso selezionare se sto fatturando a *Publica Amministrazione* o *Privati*.            

Posso scegliere se flaggare 4 voci:           
- Riepilogativa
- Dettaglio Prezzo Completo
- Richiesta Allegato per fattura
- Bollo Virtuale

Posso scegliere `ESIGIBILITÀ IVA`, se *IMMEDIATA* o *DIFFERITA*.        
Serve ad agenzia delle entrate per vedere disponibilità IVA, di solito è immediata ma devono chiedere a commercialista.

> Posso creare due XML uguali e quello nuovo sostituirà il Vecchio.          

Gli XML verranno generati nella cartella IMPORT1

Una volta inviato il file XML ad Agenzia delle Entrate posso contabilizzare la fattura selezionandola e 
cliccando su FLAG `CONTABILIZZA` e poi sul `LUCCHETTO` (Contabilizza).           
Una fattura contabilizzata avrà il Flag su `CONTABILIZZATA` nella tabella di visualizzazione.               

Una volta contabilizzata la fattura NON potrò più modificarla (o modificare le conferme associate) se prima non la sblocco cliccando su flag `CONTABILIZZA` 
e poi su `CHECKBOX` (Sblocca Fatture Selezionate).

ATTENZIONE: Così facendo si sbloccano TUTTE le fatture che si vedono sulla griglia.         

Per sbloccare una o più Fatture dovrò scrivere "CONTINUA" e premere `OK`.       

> Il tasto per De-Contabilizzare ha effetto su **TUTTE** le fatture visualizzate in griglia quindi dovrò assicurarmi di visualizzare SOLO quelle che mi interessano (filtrando).      

> Le fatture contabilizzate mi generano un tracciato che posso importare nel mio programma di contabilità.


Invio Mail fa invio massivo delle stampe di cortesia di tutte le fatture selezionate.    
> Se lo chiedono NON configurarlo sul momento ma fissa un appuntamento perché può durare anche 15 minuti.       

## DA VISUALIZZAZIONE FATTURA:

Se modifichi le conferme devi ricalcolare le conferme premendo sul tasto calcolatrice.            

## FATTURE MANUALI:

Le fatture manuali vengono fuori di colore verde mentre le note di accredito in azzurro.

Devo cliccare sul Foglio nuovo in tab di SELEZIONE e poi selezionare il tipo di documento.

TIPO DOCUMENTO:
- FATTURA
- NOTA DI ACCREDITO
- NOTA DI DEBITO

Quando modifico il documento la calcolatrice diventa rossa.

## SE VOGLIO AGGIUNGERE UNA COLONNA ALLA VISUALIZZAZIONE?

In dropdown menu seleziona il campo che ti interessa e chiudi e riapri il modulo.
> Posso aggiungere solo una colonna.      
> Esempio: la colonna Taghe si chiama **TARGHEPREV**.           

## CONTROPARTITA FATTURA MANUALE:

Per attivare l'utilizzo della contropartita in fatture manuali:      
In cartella Import troverò il TXT: PianoRicavo.txt

In questo modo le aziende possono dividere i ricavi.

## FLAG ITALIA / ESTERO

Mi fa vedere le conferme VERSO l'Italia oppure l'estero.         

## AUMENTO PREZZI

Crea una riga di prezzo aggiuntiva all'interno di tutte le conferme visualizzate in griglia che riporta un aumento.               

## RIPREZZAMENTO MODIFICA FATTURE

Nasce per l'adeguamento del Gasolio.         
Perché a parità di conferma se il prezzo del gasolio aumenta potrei perderci dal mio viaggio quindi devo riprezzare la fattura.  
> Di norma l'adeguamento va da 1 a 10%

