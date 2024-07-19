# AUTOFATTURE ESTERE

A partire dal 1 Luglio sarà dismesso l’esterometro e le fatture, sia attive che passive dovranno essere inviate allo SDI.

Le fatture attive, in realtà, si sono sempre inviate all’Agenzia delle Entrate, per cui per queste non cambierà assolutamente nulla.

Le fatture passive invece, dovranno essere registrate nell’apposito modulo delle Registrazioni Passive, dentro Amministrazione.

![REG PASS](https://user-images.githubusercontent.com/105659714/176213989-28375952-ccf7-49d7-8fa8-8c89242d8a6f.png)

Prima di registrarle però, bisogna che le anagrafiche dei fornitori/vettori siano compilate a dovere, come per i clienti esteri. 

![EST](https://user-images.githubusercontent.com/105659714/176214057-dee96602-0bea-4ea9-814f-a408b402b87b.png)

-Il campo Codice SDI dovrà essere popolato con le 7 X maiuscole, in quanto gli esteri non possiedono un intermediario.

-Il campo CAP dovrà obbligatoriamente contenere 5 cifre. Qualora il fornitore o cliente avesse per esempio 2 cifre, si aggiungeranno davanti 3 zeri per arrivare a 5 numeri (es. 00047). Se invece non ne possiedono uno, basterà compilare il campo con 5 zeri ( es. 00000)

-Il campo Stato verrà scelto dal menù a tendina, che in automatico inserirà la sigla, la quale dovrà essere riportata come Provincia, poiché non può rimanere vuota e deve contenere 2 caratteri.

-Importante inserire anche tipo di pagamento, IVA o esenzione e banca.

Torniamo alla registrazione delle fatture passive:

![FATT](https://user-images.githubusercontent.com/105659714/176214224-5783bf9c-5019-462d-9e7d-36c26da06187.png)

Per inserire una nuova fattura basterà cliccare il foglio bianco.

-I campi data reg, data ricevimento e data fattura, si inseriranno in automatico, ma si possono cambiare scegliendo la data desiderata. Bisognerà inserire anche il N°Fattura, mentre il Prt., che è il protocollo interno, sarà automatico e consecutivo.

-Nel caso di Nota credito, basterà spuntare a destra “Nota accredito” inserendo come N°Fattura, il numero della nota credito, mentre come Rif.Doc. il numero della fattura che storna.

-Scegliere dal menù a tendina il fornitore o vettore, precaricato correttamente nelle anagrafiche, in modo che tutti gli altri campi si auto-compilino. 

-Copiare l’imponibile o totale esente della fattura nell’apposito campo e con il tasto TAB, oppure cliccando nel campo adiacente, si compilerà il Totale Documento.

-Al salvataggio con il floppy disk in alto, comparirà una piccola schermata che chiederà di creare le scadenze, in base al metodo di pagamento.

-Una volta effettuato il salvataggio, si dovranno inserire le righe di prezzo (si può mettere anche una sola riga di prezzo col totale fattura)

-Cliccare su Dettaglio Righe: 

![rig](https://user-images.githubusercontent.com/105659714/176214380-df7fb623-0c38-4589-9b61-f357fae69103.png)

-Cliccare su foglio bianco, inserire la descrizione specifica del prezzo, oppure generica della fattura, nel caso in cui si volessero accorpare tutti i prezzi, quindi il totale imponibile.

-IVA o esenzione verrà inserita in automatico in base a quella scelta nell’anagrafica.

-Importo UN. Si inserirà o il prezzo unitario oppure l’imponibile/esente con la qtà annessa.

-Conferma Riga per salvare.

-Se ci sono prezzi di conferme/viaggi che devono essere agganciati alla fattura passiva, basterà cliccare su Carica da viaggi e scegliere la conferma da abbinare e poi confermare la riga.

Ora la nostra fattura è compilata.



Per esportare l’Autofattura, quindi creare l’XML, cliccare sul terz’ultimo o quart’ultimo tasto in alto a destra:

![exp](https://user-images.githubusercontent.com/105659714/176214513-9fec5065-5471-4c3d-9db5-0ae3cc43e6e7.png)

E comparirà la seguente schermata :

![dyl](https://user-images.githubusercontent.com/105659714/176214539-f071326f-2d52-407b-8bce-53bda164d835.png)

-Qui si sceglieranno le date per la ricerca delle fatture e dal menù a tendina si può selezionare anche il fornitore/vettore.

-Cliccare sulla lente di ingrandimento per ultimare la ricerca.

Se si registrano sia fatture passive estere che italiane, il modulo non consente di selezionare tra Italia ed Estero, ma starà a voi spuntarle.

-Per selezionarle basterà, o cliccare il flag in alto di fianco alla chiave inglese, il quale selezionerà tutte le fatture, oppure selezionarle a mano, cliccando 1 volta sull’ultima cella di ogni riga, nella colonna selezione. Essa si illuminerà di verde.


-Una volta selezionate le fatture da esportare, cliccare sul tasto Esporta in alto a destra e comparirà la seguente maschera: 

![fattura](https://user-images.githubusercontent.com/105659714/176214662-5c763c4a-f174-4dbf-a2b0-55b21a3f2a0d.png)

È la stessa schermata delle fatture attive, infatti gli XML delle autofatture, si genereranno nella stessa cartella.

Quindi basterà scegliere dal menù a tendina il Tipo Fattura Standard, ovvero tra TD16, TD17, TD18 e TD19 e cliccare su Fattura Elettronica.

Per sapere che codice usare, consultare il nostro manuale che spiega a cosa si riferiscono, consultare ulteriormente il proprio commercialista.

La fattura verrò contabilizzata in modo da sapere successivamente quale è stata inviata e quale no.

Se si ha il nostro intermediario Dylog, la fattura verrà inviata in automatico, come attiva.

Ovviamente il Prestatore sarà il vostro fornitore/vettore, mentre il Cedente diventerà la vostra azienda.

Per chi ha l’intermediario diverso dal nostro, ovviamente gli XML dovranno essere caricati nel proprio portale come fatture attive.







