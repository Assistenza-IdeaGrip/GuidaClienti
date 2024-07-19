# COME APRIRE IL MODULO:

Da scheda veicoli:        
- Mezzi -> Riparazioni (così richiama la targa del mezzo)
- Riparazioni (senza filtro mezzi)

> Puoi importare direttamente gli XML delle riparazioni.

# DOMANDE DA FARE:

- Hai officina Interna?

# A COSA SERVONO?

Le riparazioni creano un EVENTO per il mezzo ed indicano quando non è disponibile.       

Servono anche per tenere uno storico delle riparazioni dei mezzi.         

![riparazioni](https://github.com/Fucio992/GuidaTir/assets/139453658/eb1c7a7d-241d-4e5d-b7a5-12247004c009)

# COM'È FATTO IL MODULO?

- PARTE DI INSERIMENTO: Qui si inseriscono i dati relativi alle riparazioni.

![inserimento](https://github.com/Fucio992/GuidaTir/assets/139453658/06f8a062-0e6b-4d33-9082-fb282c74fd54)
  
- PARTE DI RICERCA: Qui si visualizza lo storico delle riparazioni.

![visualizzazione](https://github.com/Fucio992/GuidaTir/assets/139453658/a3bdd283-ff4b-430c-9cff-be0cb0250d3a)

# COME CREARE UNA NUOVA RIPARAZIONE:

- Premi su **NUOVO** -> Il programma mi crea un numero progressivo.
> ATTENZIONE! il numero progressivo NON corrisponde al numero della fattura!

## CAMPI INSERIMENTO INTERVENTO:

![inserimento intervento](https://github.com/Fucio992/GuidaTir/assets/139453658/fa158baa-c1df-4624-80bb-ebae6c29ce16)

- NUMERO: numero progressivo che identifica la riparazione.
> Sopra al numero c'è scritto l'ID che invece identifica una specifica riga di prezzo di una specifica riparazione.       
- Data: data di inserimento della riparazione.
- N° Doc. del Fornitore: numero del documento della fattura della riparazione.
- Data Doc: data della fattura.
- N° Protocollo: lo trovi nella fattura.
- Data Scadenza Garanzia: lo trovi nella fattura.
- ESEGUITA: lo premi se la riparazione è già stata eseguita. (da flaggare a riparazione terminata).
- Fornitori: Li va a prendere dall'anagrafica dei fornitori che hanno specificato `RIPARAZIONI` alla voce `settore`.

> Compilando la ragione sociale e premendo `+` creo una nuova anagrafica fornitore con settore riparazioni.

- Targa: inserire targa mezzo.
- KM: inserire i km al momento della riparazione.
- Descrizione della Riparazione: qui va scritto quello che è stato fatto.

> Se scrivo una descrizione e poi premo `salva` mi aggiunge la descrizione fra le opzioni del menu a tendina.    

- Categoria: posso aggiungermi le categorie degli interventi.
- Tipo di Riparazione: `ORDINARIA` (se è stata programmata) o `STRAORDINARIA` (se non è stata programmata).
- Nota: note libere.
- Data ed Ora inizio / fine -> relative ad inizio e fine riparazioni.
- Imputabile ad Autista: se la riparazione è imputabile all'autista va flaggato.
> se la riparazione è imputabile ad autista e flaggo la casellina allora posso compilare i campi `Cod.Autista`, `Nome Autista`. `N°Sinistro`.   
- IVA, Importo e Totale si popolano in automatico quando vado ad inserire i prezzi.

## CAMPI INSERIMENTO PREZZI:

![inserimento prezzi](https://github.com/Fucio992/GuidaTir/assets/139453658/8a2ed3fd-0620-4efd-a5d5-c6fa42b59421)

- Descrizione Articolo: qui posso inserirmi eventuali articoli che ho acquistato per riparare il mezzo *esempio: GOMME XYZ ...*.     

> Se premi sulla `+` l'articlo verrà aggiunto fra le opzioni del menù a tendina.        

- Cod.IVA: metti codice esenzione IVA *es: articoli vari 0 22*.
- Prezzo: inserisci prezzo.
- Quantità: inserisci quantità.
- IVA: inserisci importo IVA.
- IMPORTO:  prezzo * quantità (si popola in automatico premendo tab).
- Totale: Imposto + IVA.

## AGGIUNGI RIGA:

Se lo premi aggiungi una riga di prezzo al documento.

```
ESEMPIO:
Riga 1) riparazione gomme -> Categoria: PNEUMATICA
Riga 2) altra riparazione -> Categoria: MECCANICA
Riga 3) .....
```

# RICERCA:

Posso ricercare per `Data` e/o `Targa`.

> Se una riparazione ha più righe di prezzo nella ricerca troverò un record per ogni riga di prezzo.      

```
ESEMPIO:
Riga 1) cambio gomme
Riga 2) cambio Olio
Riga 3) Riparazione mezzo
```
| NUMERO |    DESCRIZIONE     | PREZZO |
| ------ | ------------------ | ------ |
| 000002 | Cambio Gomme       |   ...€ |
| 000002 | Cambio Olio        |   ...€ |
| 000002 | Riparazione mezzo  |   ...€ |

##  BOTTONI

- SCANNER: puoi importare file relativi alle riparazioni.          
- RICERCA AVANZATA (lente rossa): apre la ricerca avanzata delle riparazioni.         
- STAMPE: stampe relative alle riparazioni.
- ESPORTA EXCEL: Crea sul desktop un file excel con tutti i dati della griglia.
- SALVA COLONNE: Salva configurazione Griglia (se allarghi o rimpicciolisci colonne)
- XML: mi cerco la cartella che contiene gli XML passivi e li importo.

> Quando importo XML con più righe di prezzo mi riporta la targa solo sulla prima riga quindi devo aggiungerla manualmente dove manca.      

