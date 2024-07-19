# SCOPO FORMAZIONE

Lo scopo della formazione è di rendere autonomo il cliente nella creazione delle fatture.      

# FORMAZIONE

La Fatturazione parte dalle Conferme.       
Se le conferme sono inserite male le fatture usciranno incomplete oppure errate.       

**Per aprire il Modulo Fatturazione:**          
AMMINISTRAZIONE -> FATTURAZIONE          

Il modulo si compone di due schede: `Genera Fatture` ed `Elenco Fatture`.

## GENERAZIONE FATTURE

La prima cosa da fare è selezionare l'azienza con la quale si desidera fatturare.    

> Eventualmente posso selezionare il sezionale oppure premendo il bottoncino con la matita posso aggiungerne 1 o più, se non scelgo un sezionale viene adottata la numerazione di default `AA0000X` (esempio: *2400001*).    

Una volta filtrate le conferme posso selezionarne 1 o più dalla griglia e premere il bottone `Genera Fatture` per generare le fatture.    

> In questa visualizzazione ho a disposizione un ordinamento colonne ed un bottone con la `I` che mi apre la gestione delle lettere d'intento.    

> `Aggiorna NR Fattura` serve per recuperare l'ultimo numero di fattura nel caso in cui avessi modificato la numerazione.

### LETTERA D'INTENTO

Qui posso cercarmi i Clienti con la lettera d'intento (precedentemente caricata in anagraficha Cliente) e posso scalare il plafond in base alle fatture a cui voglio abbinare la lettera d'intento.     

> In alto vedo il `Plafond Totale` ed il `Plafond Residuo`.
> Devi abbinare manualmente tutti i prezzi (si basa sulla riga di prezzo)

### FATTURA MANUALE

Da qui posso creare Fatture, Note di Accredito e Note di Addebito.    

> Si creano fatture manuali per tutto ciò che è estraneo al servizio di trasporto (e non è legato alle conferme) come ad esempio:
> Vendita Mezzi
> Fatture non legate all'attività di Trasporto

**IMPORTANTE**: per le note di accredito: gli importi devono essere in `POSITIVO`.   
> Se emetto una fattura di 1000€ ma in realtà erano 900€ devo emettere una `NOTA DI ACCREDITO` di 100€,    
> se per sbaglio emetto una nota di credito di 150€ per correggerla devo emettere una `NOTA DI ADDEBITO` di 150€       
> e poi riemettere una `NOTA DI CREDITO` di 100€

È importante selezionare il tipo di documento.    
> Esempio:    
> TD01 - Fattura    
> TD24 - Fattura Differita    

Se premo sul bottone della matita nel quadratino posso cambiare manualmente il numero della fattura ed il bottonino affianco mi permette di duplicare la fattura.    

Poi seleziono la Cliente e Sede e la banca.    

Una volta selezionati i dati relativi al cliente posso procedere ad inserire le varie righe di prezzo che compongono la fattura ed eventualmente posso aggiungere 3 aggiunte.    
Per aggiungere una riga di prezzo devo premere su `+`, compilare i campi e poi premere su `SALVA`.    

## ELENCO FATTURE

Da qui posso modificare le Fatture, generare gli XML da inviare allo `SDI` oppure stampare le fatture e/o crearmi una copia PDF.

Prima di esportare l'XML posso filtrare le fatture.

> CONTABILIZZA serve solo per chi ha un programma di contabilità altrimenti basta fare `Genera XML`.

Per aprire una fattura precedentemente generata devo selezionarla, premere con il tasto destro e poi cliccare `Modifica Fattura`.



### DISPOSIZIONI RIBA

Per poterlo utilizzare dev'essere selezionato un metodo di pagamento RiBa altrimenti non vedo le fatture nella griglia.      

Dalla scheda che mi apre devo selezionare `Genera disposizioni RiBa` e poi devo riportare i dati.        
- Nella prima riga (Con ABI, CAB ...) devo riportare i dati della banca PROPRIA.    
- SIA, PIVA e RAGIONE SOCIALE devono essere della banca PROPRIA. (perché la banca del cliente è già nella fattura)    

Nella lista in Basso mi fa vedere tutte le fatture che contengono RiBa come metodo di pagamento.    
Da qui posso deselezionarle e riselezionarle ed una volta terminato mi basta cliccare su `CREA RI.BA.`     
per generare le disposizioni che poi devo riportare in Home Banking.



# GENERARE XML:
Per Generare il file `XML` da inviare all'agenzia delle entrate devo cliccare sull'icona con il `LUCCHETTO`.       
Una volta cliccato il lucchetto si aprirà la scheda tracciati.

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

Gli XML verranno generati di default nella cartella IMPORT1

> Per sbloccare le fatture di cui è già stato creato l'XML devi selezionarla e premere su `BLOCCA/SBLOCCA XML`.

Le fatture vanno contabilizzate SOLO se si ha il programma di Contabilità.      
Per contabilizzare le fatture bisogna cliccanre sul FLAG `CONTABILIZZA` e poi sul `ESPORTA CONTABILITÀ + XML`.           
> Una volta contabilizzata la fattura avrà il Flag `CONTABILIZZATA` nella tabella di visualizzazione e per de-contabilizzarla dovrò andare in contabilizza e poi in `SBLOCCA CONTABILIZZATE` (Attenzione, quel bottone sblocca TUTTE le fatture visualizzate in griglia).               

Una volta contabilizzata la fattura NON potrò più modificarla (o modificare le conferme associate) se prima non la sblocco.

> Eventualmente posso contabilizzare lo stesso la fattura una volta che è arrivata al cliente in modo da bloccare le conferme (ma non serve).

Invio Mail fa invio massivo delle stampe di cortesia di tutte le fatture selezionate.    

> Se lo chiedono NON configurarlo sul momento ma fissa un appuntamento perché può durare anche 15 minuti.       
