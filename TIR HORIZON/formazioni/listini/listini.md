# FORMAZIONE LISTINI

> Su TIR: Listini.exe
> Su Horizon: Cartella ListiniLuogoSpedizionieri (con dentro ListiniLuogoSpedizionieri.exe)
> Su Horizon R: Cartella NuoviListiniSpedizionieri con dentro NuoviListiniSpedizionieri.exe

Per ora faccio formazione su Listini Horizon.        

Di solito si spiegano direttamente da dentro le conferme perché così il cliente vede subito l'output dell'effetto del listino.          

**Il prezzo si può creare Manualmente o con Listino.**              

Il prezzo può essere richiamato cliccando su "+" da riga prezzo oppure salvando la conferma.      
Se spunto `NO PR CLIENTE` e poi salvo la conferma non mi prende il prezzo ma se premo su "+" mi richiama comunque il prezzo.       

# LISTINI:     

Da Prodotti -> Servizi Cliente -> Vai a Listini

> Appena lo apro è vuoto quindi devo premere su cerca.         

Senza `Listino Preferenziale` NON mi prende il listino in automatico.     
Per caricare listino senza Listino Preferenziale devo aggiungere una riga di prezzo e poi selezionare il listino, premere tab e salvare.      

OPZIONI LISTINO PREFERENZIALE:    
- Classi (non va selezionato dalla tendina)
- Luogo
- Luogo Nullo

La casella di testo Listino Preferenziale si popola solo quando aggiungo un listino.        

Per prendersi il listino il programma fa un controllo in ordine di priorità, dalla cosa più generica al dettaglio.           

TIPI LISTINO:
- Prov: mi aggancia il listino leggendo la provincia di Carico e Scarico
- Luogo: mi aggancia il listino leggendo il luogo di Carico e Scarico
- Mitt/Dest: mi aggancia il listino leggendo Mittenti e Destinatari

> Per chi ha il listino automatico deve esserci la spunta in configurazione applicazione -> Modulo Conferme/Prezzi Auto (Dovrebbe essere spuntata di default)

Valuta Sede è una discriminante per la sede del `Cliente`.

### MF = Minimo fatturabile.

Flagga: FoMF per attivare minimo fatturabile.     
- MF: Minimo Fatturabile di quantità
- MFImporto: Minimo Fatturabile di importo
Una fascia fissa in se è un MINIMO FATTURABILE.

Se io ho MF a 10, se nel mio ordine metto solo 5 bancali lui mi prende l'importo per 10.     

*Esempio prezzo fisso a Tratta:*          
| TIPO | Carico | Scarico | Importo |
| --- | --- | --- | --- |
| prov | TV | VE | 100 |

> La descrizione si crea in automatico.

*Esempio listino Prodotto:*          
| TIPO | Carico | Scarico | Importo | Nota (UM) |
| --- | --- | --- | --- | --- |
| prov | PD | VR | 5 | BANCALI |

> Se mi segno UM Preferenziale dopo mi appare anche in modulo conferme: Prodotti -> U.M.

*Esempio listino Prodotto a Fasce:*           
| TIPO | Carico | Scarico | Importo | Nota (UM) |
| --- | --- | --- | --- | --- |
| prov | PD | VR | 0 | BANCALI |

- Aggiungi Fascia:
         
| MIN | MAX | Arr | Prezzo | Fisso |
| --- | --- | --- | --- | --- |
| 1 | 16 | 0 | 130 | F |
| 17 | 23 | 0 | 160 | F |
| 24 | 33 | 0 | 260 | F |

Senza F nelle fasce mi calcola il prezzo al bancale o a esempio tonnellaggio.        

CodiceL: qui posso aggiungere un filtro per codice prodotto.
> Per considerare CodiceL devi spuntare flag `Verifica Codice Prodotto`.    

Al posto di Codice L posso aggiungere un filtro per *CONTRATTO* aggiungendo il flag su `Valuta Contratto`.           
Le voci che inserisco in contratto le trovo nel dropdown "*Tipo Spedizione*" su conferme.

Senza la F di Fisso lui mi fa il calcolo sul NUMERO di bancali.        
Es: fascia 1-16 bancali = 100€ quindi se io carico 8 bancali il prezzo sarà 8*100€

### Listino a KM:

| TIPO | Importo | Nota (UM) |
| --- | --- | --- |
| km | 100 | Km |

IMPOSTAZIONI:
- Listino preferenziale: LuogoNullo
- UM Preferenziale KM
- Metodo di Calcolo: Bancale

### Rapporto Peso Volume (RPV)/ Rapporto Peso Pianale (RPP)

Il valore da INSERIRE in RPV o RPP è un coefficiente e di solito lo sa già il cliente (di solito 150,230...)

Il listino è a PESO e moltiplica il coefficiente RPV/RPP per il volume e poi controlla in quale fascia di peso ricade il risultato.

### PREZZO COMMESSA:
Funzioni da Attivare (o uno o l'altro):
- Prezzo più alto commessa: fa il calcolo sul luogo più lontano
- Prezzo somma commessa: mi calcola il totale dei prodotti

**METODO DI CALCOLO**

Prima trova la tratta e se c'è un match valuta le discriminanti come ad esempio "prodotto".          

# AGGIUNGI PRODOTTO A LISTA PRODOTTI:

Da conferme apri lista prodotti ed aggiungi voce prodotto a lista.       
Se da lista prodotti faccio doppio Click sulla riga del prodotto chee mi interessa mi crea una nuova riga prodotto nelle conferme.          

# LISTINI ACCESSORI:

# IMPORTAZIONE LISTINI:

Dopo aver preparato i file excel di import basta andare su `Servizi Cliente` e poi listini.      
Da schermata listini basta premere su `Import` e poi sul tipo di import (a sinistra delle frecce).       
