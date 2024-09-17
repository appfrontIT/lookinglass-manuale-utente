---
description: >-
  In questa appendice verrà descritto il tool di preventivazione presente nel
  portale Lookinglass.
---

# Appendice A Teoria RCA

## Preventivi

Dalla pagina Dashboard è possibile accedere al tool di preventivazione tramite il bottone "Emetti Polizza" presente sul menù di sinistra.

L'elaborazione del preventivo da parte dell'utente avviene tramite l'inserimento delle informazioni necessarie al calcolo della tariffa. La procedura è suddivisa in cinque passi più un sesto di riepilogo.&#x20;

Il preventivo può essere elaborato anche in più sessioni, una volta iniziato sarà possibile richiamarlo dalla lista delle "Quotazioni" presente in Dashboard. I preventivi non finalizzati avranno nello stato l'etichetta WIP (Work In Progress). E' bene sottolinare che un preventivo etichettato come WIP non è ancora emesso e, di conseguenza, non ha valore nei confronti del cliente.&#x20;

A seguito del controllo dei valori immessi nella schermata di riepilogo, è possibile emettere e stampare il preventivo. Lo stato del preventivo verrà aggiornato su ISSUED (Emesso). Tale preventivo ha ora valore vincolante nei confronti del cliente.&#x20;

Se il cliente accetterà il preventivo e verrà emessa la relativa polizza lo stato del preventivo verrà aggiornato su POLICY (Polizza _emessa_).&#x20;

<figure><img src=".gitbook/assets/image (60).png" alt=""><figcaption><p>Passi necessari alla realizzazione di un preventivo</p></figcaption></figure>

Il primo form, identificato dall'indirizzo [https://lookinglass.ipagency.it/emetti-polizza/targhe](https://lookinglass.ipagency.it/emetti-polizza/targhe), prevede in primis l'inserimento della targa sulla quale si vuole calcolare una tariffa. Va anche indicato se il veicolo associato a tale targa è già di proprietà del cliente, in corso di acquisto o se al contrario si tratta della sostituzione della targa causa usura o smarrimento. E' inoltre possibile indicare due opzioni speciali inerenti la volontà di emettere una polizza su veicoli storici o solamente l'emissione di una copertura CVT o di assistenza.&#x20;

<figure><img src=".gitbook/assets/image (61).png" alt=""><figcaption><p>Il primo form della procedura per la preventivazione</p></figcaption></figure>

Il sistema si occuperà in automatico di recuperare l'ATR dal database di ANIA oltre che di suggerire il modello del veicolo che dovrà essere inserito tramite l'utilizzo dei menù a tendina sottostanti. E' fondamentale, per l'emissione di coperture CVT, inserire anche il corretto tipo di allestimento del veicolo in modo da computare con esattezza la tariffa. Nel caso in cui l'allestimento non sia presente nel database, è possibile inserire manualmente la quotazione del mezzo nell'apposita casella "Quotazione Ritiro". Nei paragrafi "Le targhe" e "Gli attestati di Rischio" verranno introdotti i dettagli nel caso di necessità di inserire targhe particolari o di dover ricorrere al recupero dell'ATR da un'altra targa o ancora nel caso di applicazione del decreto Bersani.&#x20;

### Le targhe

Il tool di preventivazione accetta targhe in vari formati che dipendono sia dal tipo di veicolo che dall'anno di immatricolazione dello stesso.&#x20;

La targa degli autoveicoli standard ha il formato XXyyyXX dove la "X" corrisponde ad una lettera e la "y" ad una cifra numerica. Gli autoveicoli immatricolati prima del 1993 presentano invece il formato XX yyyy dove le lettere "XX" rappresentano il capoluogo di provincia dove è stata effettuata l'immatricolazione (fa eccezione "Roma" che è indicata per intero) mentre le cifre ("y") possono essere 4 o 5, in taluni casi intervallati da una lettera. E' bene notare la presenza di uno spazio vuoto tra i caratteri del capoluogo e le cifre.&#x20;

Le targhe dei veicoli classificati come rimorchi devono essere inserite dopo il carattere "R".&#x20;

Le targhe dei veicoli classificati delle macchine agricole semoventi devono essere inserite dopo i caratteri "MAS".&#x20;

Le targhe dei veicoli classificati delle macchine operatrici semoventi devono essere inserite dopo i caratteri "MOS".

Le targhe dei veicoli classificati come rimorchi agricoli devono essere inserite dopo i caratteri "RAG".

Le targhe dei veicoli classificati come macchine operatrici trainate devono essere inserite dopo i caratteri "MOT".

E' possibile richiamare un pannello informativo direttamente dalla pagina del tool di preventivazione cliccando sul punto interrogativo presente vicino alla scritta in rosso "Targa polizza" presente sulla parte alta della scheda.&#x20;

<figure><img src=".gitbook/assets/image (2).png" alt=""><figcaption><p>Tipologie di targhe accettate dal sistema.</p></figcaption></figure>

### Gli attestati di rischio

Una volta inserita la targa di cui si vuole eseguire la preventivazione, il sistema recupera dal database nazionale di ANIA il relativo Attestato di Rischio (ATR). La classe di merito li indicata, insieme allo stato del pagellino, verranno utilizzati per il calcolo del premio. &#x20;

### Le operazioni recupero ATR e Bersani

E' possibile eseguire operazioni quali il recupero dell'ATR da un'altra targa nel caso in cui il veicolo precedentemente posseduto sia stato rubato, venduto o demolito. E' inoltre possibile recuperare l'ATR di un familiare o un cointestatario di una precedente assicurazione.&#x20;

E' inoltre possibile applicare i vantaggi del decreto Bersani nel recupero della classe di merito di un parente facente parte dello stesso stato di famiglia indicando l'apposita opzione nel relativo menù a tendina. Va specificato che il decreto Bersani permette di recuperare la classe di merito del convivente ma non il suo pagellino.&#x20;

Le operazioni di recupero ATR o di applicazione del decreto Bersani sono soggette ad un ulteriore livello di controllo relativo alla regione di residenza del richiedente e del convivente da cui si recupera l'ATR. Nel caso di situazioni ambigue, è necessario contattare gli uffici IPA per l'autorizzazione a procedere con l'emissione del preventivo.&#x20;

### I dati del contratto

<figure><img src=".gitbook/assets/image (1) (1).png" alt=""><figcaption><p>Il secondo form della procedura di preventivazione relativo al percorso di vendita</p></figcaption></figure>

Il secondo form del tool di preventivazione permette di inserire la data e l'ora della decorrenza della copertura, nonché la tipologia di frazionamento annuale o semestrale. Inoltre è possibile verificare la catena di vendita in atto in base al codice dell'intermediario/produttore e all'utente indicati (VA INSERITO IL RIASSEGNAMENTO DI UN PREVENTIVO?). E' inoltre possibile inserire qui le informazioni relative ad un vincolo, se presente.&#x20;

Il terzo form del tool permette l'inserimento dei dati anagrafici del cliente. Il codice fiscale viene recuperato dalla compilazione eseguita nel primo form. Oltre ai dati relativi alla data e alla città di nascita (o paese estero), è necessario inserire l'indirizzo di residenza e, se differente, quello di domicilio del cliente.&#x20;

### I dati anagrafici

<figure><img src=".gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

Vanno inoltre inseriti, tramite gli appositi menù a tendina, la nazionalità, lo stato civile, il titolo di studio, la professione nonché l'anno di conseguimento della patente e se il contraente è anche il conducente principale del mezzo.&#x20;

L'indirizzo email inserito come dato di contatto verrà utilizzato come destinatario del preventivo una volta che questo verrà finalizzato.&#x20;

### I prodotti e le garanzie

Nel quarto form della procedura è possibile selezionare il prodotto, relativo alla tipologia di veicolo cui la targa inserita per la preventivazione fa riferimento. I prodotti sono di seguito elencati:&#x20;

RC Auto&#x20;

RC Van

RC Truck

RC Rimorchi

RC Motocicli

RC Ciclomotori

RC Auto Epoca (solo per alcuni intermediari)



Nel caso di RC Truck, sono presenti sul sistema dei prodotti differenziati in funzione del peso del camion considerato. Il sistema selezionerà automaticamente il prodotto con la fascia di peso corretta tra le seguenti:&#x20;

35q - 70q

70q - 120q

120q - 440q

oltre 440q

<figure><img src=".gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

Ogni prodotto è caratterizzato da una serie di garanzie, la principale è quella inerente la copertura per la Responsabilità Civile (RC). A seconda della tipologia di veicolo è necessario inserire alcuni informazioni quali il massimale, la tipologia di guida (libera, esperta), se il veicolo è ad uso privato o meno ed altro. Nello stesso panello verranno ricapitolate alcune informazioni che concorrono al computo del premio assicurativo.&#x20;

A meno che nel primo form non sia stata selezionata l'opzione "solo CVT", è necessario inserire la garanzia RC per permettere poi l'aggiunta di un contratto di assistenza o delle coperture accessorie quali gli infortuni del conducente, la copertura kasko, il furto e incendio o la copertura per i danni ai cristalli.&#x20;

### I premi e gli sconti

Alcune tipologie di sconto, visualizzabili nel form successivo, sono attivabili solamente se, ad esempio, alla RC Auto è associato anche un contratto di assistenza stradale.&#x20;

<figure><img src=".gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

Gli sconti possono essere applicati separatamente sulle varie garanzie selezionate. Lo sconto massimo applicabile dipende dagli accordi commerciali intrapresi tra IPA e l'intermediario stesso e dipende dalla garanzia selezionata. Ad esempio, alcuni intermediari possono effettuare degli sconti sulle RC Truck ma non sulle RC Auto. Nel caso in cui la spunta presente vicino al valore indicante lo sconto massimo applicabile risulti essere rossa, è possibile cliccarci per vedere quali condizioni non sono state raggiunte e di conseguenza perché lo sconto non è applicabile.&#x20;

Una volta impostato il valore di sconto che si vuole applicare al cliente, è necessario cliccare sul bottone "Ricalcola" per aggiornare il computo delle tasse prima di poter proseguire al form di riepilogo.

### Il riepilogo

Nell'ultimo form della procedura di emissione della polizza vengono inizialmente elencate le informazioni salienti del veicolo che si vuole assicurare e del contraente.&#x20;

<figure><img src=".gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

Infine vengono riepilogate le informazioni economiche relative al preventivo appena compilato&#x20;

<figure><img src=".gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

Prima di poter procedere all'emissione del preventivo è necessario aggiungere il documento di identità del contraente e il libretto di circolazione del mezzo che si vuole assicurare. Come già sottolineato, un preventivo non emesso formalmente non ha valore legale nei confronti del cliente.

### Emissione



Tramite il menù presente in Dashboard è possibile visionare l'elenco dei preventivi lavorati. Aprendo uno con lo stato "ISSUED" è possibile navigare tra i vari form liberamente.

<figure><img src=".gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

Nel caso in cui il cliente sia interessato all'acquisto del preventivo emesso è possibile, dal form di riepilogo, selezionare il bottone "EMETTI POLIZZA".

Prima dell'emissione della polizza è necessario far compilare al cliente il "QUESTIONARIO PER LA VALUTAZIONE DELLA COERENZA DEL CONTRATTO CON LE RICHIESTE ED ESIGENZE ASSICURATIVE".&#x20;

Il questionario deve essere compilato integralmente e fatto firmare dal cliente per poi essere ricaricato a sistema insieme al modulo per la privacy. A questo punto è possibile emettere la polizza.&#x20;

Un preventivo emesso (ISSUED) ha una validità legale di 60 giorni. Se il cliente ne richiede l'acquisto superato questo termine, è necessario eseguire una nuova preventivazione.&#x20;

## Anatomia della polizza

Una volta emessa la polizza, è possibile stamparla in formato pdf dalla pagina in cui sono mostrati i dettagli della polizza stessa (azione "Guarda" dall'elenco delle polizze). Il pdf della polizza è composto da quattro pagine: la prima mostra i dati del veicolo assicurato, del contraente/proprietario e le tipologie di garanzie incluse nella polizza;&#x20;

<figure><img src=".gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

la seconda riepiloga le dichiarazioni del contraente;&#x20;

<figure><img src=".gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

la terza riepiloga le modalità di pagamento;&#x20;

<figure><img src=".gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

la quarta contiene l'elenco dei titoli di pagamento relativi alla polizza in oggetto.&#x20;

<figure><img src=".gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

### I dati più importanti

Nella parte alta della prima pagina della polizza sono presenti alcuni dei dati più importanti quali:

* il numero di polizza
* la targa del veicolo assicurato
* la data e l'ora di decorrenza
* la data e l'ora di termine&#x20;
* il nominativo del contraente e del proprietario
* il codice IUR&#x20;

<figure><img src=".gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

La parte centrale della polizza contiene informazioni essenziali per il cliente quali le garanzie presenti nella polizza, i massimali coperti dalla garanzia RC ed il numero di riferimento nel caso di necessità di assistenza stradale.

<figure><img src=".gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

E' inoltre importante per il cliente verificare in quali paesi esteri la polizza può considerarsi valida.

<figure><img src=".gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

## Titoli

Il titolo rappresenta una operazione contabile eseguita nel caso di aggiornamenti sullo stato di validità di una polizza. E' importante sottolineare che nel caso di emissione di una nuova polizza non vengono inviate ad ANIA le informazioni relative alla copertura assicurativa fintanto che il relativo titolo non viene impostato come incassato.&#x20;

Tale concetto è valido più in generale per tutti i titoli, che siano di rinnovo o cancellazione: le modifiche allo stato della copertura assicurativa non vengono comunicate ad ANIA fintanto che lo stato del titolo non viene portato ad "incassato".&#x20;

I titoli sono suddivisi in base al tipo di operazione che viene identificata con un numero a due cifre come di seguito riportato:&#x20;

* 10 - nuova emissione polizza
* 11 - quietanza di pagamento semestrale
* 12 - sostituzione
* 13 - riattivazione
* 14 - sospensione
* 16 - polizza con compensazione del premio
* 18 - cancellazione
* 19 - sospensione
* 21 - rinnovo
* 61 - operazione di storno di una quietanza
* 62 - operazione di storno di una sostituzione
* 63 - operazione di storno di una riattivazione
* 68 - operazione di storno di una cancellazione
* 69 - operazione di storno di una sospensione
* 71 - operazione di storno di un rinnovo
* 90 - rimborso generico
* 92 - rimborso integrativo sostituzione
* 98 - rimborso integrativo annullamento
* 99 - riclassificazione CU

E' bene notare la possibilità di attribuire alle operazioni di storno un titolo dedicato per ogni tipologia di operazione precedentemente effettuata.&#x20;

### Quietanze

La polizza assicurativa ha sempre valenza annuale (360 giorni), è scelta del cliente differire il pagamento in due soluzioni, la prima alla firma del contratto di assicurazione e la seconda dopo sei mesi. &#x20;

Il titolo di quietanza (operazione 11) viene generato automaticamente dal portale cinque mesi dopo la data di decorrenza della polizza e deve essere incassato entro il mese successivo al fine di garantire la continuità della copertura assicurativa per tutto l'anno di valenza del contratto.&#x20;

Il mancato incasso della quietanza non comporta la cancellazione del contratto di assicurazione ma la copertura verrà sospesa dopo 15 giorni dalla data di pagamento. Nel momento in cui il cliente effettuerà il pagamento, la copertura assicurativa verrà riattivata.&#x20;

Nel caso di mancato pagamento della quietanza non è possibile cambiare compagnia assicurativa se non dopo aver esplicitamente richiesto l'annullamento del contratto precedente. Per l'annullamento valgono le regole indicate nell'apposito paragrafo.&#x20;

Le operazioni di sostituzione e sospensione richiedono il pagamento delle quietanze eventualmente scadute: non è possibile, ad esempio, sospendere una polizza dopo la scadenza del pagamento della quietanza se quest'ultima non è stata pagata.&#x20;

### Rinnovi

A ridosso della scadenza di una polizza verrà generata una quotazione per il rinnovo che tiene conto dei criteri assuntivi attualmente validi (inclusi eventuali sconti concordati con l'intermediario).&#x20;

### Sostituzioni

Una polizza assicurativa in corso di validità può essere trasferita da un veicolo della stessa tipologia ad un altro previa richiesta del cliente. Si ricorre alla procedura di sostituzione anche nel caso in cui il cliente cambi la propria residenza.&#x20;

L'operazione di sostituzione richiama il tool di preventivazione precedentemente descritto al fine di computare un'eventuale cambio di premio, sia in eccesso che in difetto. Il preventivo di sostituzione, se accettato, comporterà la generazione di un titolo di sostituzione (operazione 12) che una volta incassato comporterà il trasferimento della copertura assicurativa sul nuovo veicolo.&#x20;

La data di scadenza della nuova polizza, associata alla nuova targa, sarà la medesima della polizza originale.&#x20;

### Annullamenti

Le polizze assicurative possono essere annullate prima del decorso annuale (indicato nella data termine riportata nel pdf della polizza). L'operazione di annullamento può essere richiesta dal cliente nei seguenti casi:

* vendita
* rottamazione
* furto&#x20;
* esportazione

Inoltre, può essere richiesto l'annullamento nel caso di decesso del contraente.&#x20;

E' inoltre diritto del cliente richiedere l'annullamento della polizza per "ripensamento" ma solamente nell'arco di 5 giorni dalla data di emissione della polizza stessa.&#x20;

Nel caso di annullamento, al cliente viene restituita la quota parte del premio netto pagato in funzione dei giorni di copertura non fruiti rispetto ai 360 giorni di valenza annuale.&#x20;

Ad esempio, nel caso in cui si richieda l'annullamento della polizza dopo 180 giorni dalla data di decorrenza, al contraente verrà restituito metà dell'importo netto pagato.&#x20;

La restituzione delle tasse avviene unicamente nel caso di ripensamento entro i 5 giorni dalla data di emissione, nel caso in cui la richiesta avvenga nello stesso mese solare della data di emissione.

### Sospensioni e riattivazioni
