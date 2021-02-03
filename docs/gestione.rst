Gestione delle criptovalute con Eidoo
=====================================

Eidoo è un wallet di criptovalute HD sicuro e “non custodial”, in cui i fondi rimangono sempre nelle mani dell’utente.

Criptovalute Supportate
-----------------------

Eidoo supporta le seguenti criptovalute:

* Bitcoin (BTC)
* Litecoin (LTC)
* Ethereum (ETH)
   * token ERC20
   * token ERC223
   * token ERC721 (NFT, token non fungibili)

Visualizzazione dell’indirizzo di deposito di una delle criptovalute supportate
-------------------------------------------------------------------------------

La schermata principale **“I tuoi asset”** mostra il saldo complessivo del vostro wallet. Essendo il wallet appena creato è chiaramente vuoto: 0 BTC, 0 ETH, 0 LTC, etc. etc. Le valute supportate da Eidoo sono **Bitcoin**, **Litecoin**, **Ether**, token **ERC20** e **ERC223** (PNT, USDT, DAI, BAT, etc., 
`qui <https://eidoo.io/erc20-tokens-list>`_ una lista completa) e i token **NFT**.

Per ricevere sul vostro wallet un di queste criptovalute dovete innanzitutto visualizzare il vostro indirizzo di deposito (o *address*).

.. warning::
    Prima di depositare qualsiasi asset fate una prova con un importo minimo per verificare che l’address sia corretto e che non ci siano problemi.

Cliccate in alto a destra il **QR code** per visualizzare il menu per la scelta della criptovaluta da depositare.

.. image:: https://i.imgur.com/PK4nGrB.jpg
    :width: 300px
    :align: center

Cliccate sulla criptovaluta che volete gestire, ad esempio **ETH**.

.. image:: https://i.imgur.com/Stpho2W.jpg
    :width: 300px
    :align: center

Se non avete nessuna transazione potete cliccare sul tasto verde **AGGIUNGI FONDI** al centro della schermata o su Deposito in alto a sinistra. Nel caso in cui abbiate già  delle transazioni potete cliccare su Deposito.

.. image:: 
    :width: 300px
    :align: center
    
    
.. image:: 
    :width: 300px
    :align: center

In ogni caso visualizzerete il vostro **QR CODE** al centro. Questo può essere utile nel caso in cui vogliate ricevere un pagamento da un amico che utilizza a sua volta un wallet mobile come Eidoo. Semplicemente inquadrando questo codice il wallet è in grado di determinare il vostro address. 

In basso trovate anche il relativo **indirizzo di deposito** in formato esadecimale. Con i tasti **"CONDIVIDI"** e **"COPIA"** potete rispettivamente inviare il vostro address tramite SMS, mail, social o copiare l'indirizzo completo nella memoria del vostro smartphone.

.. image:: https://i.imgur.com/xHHBfKV.jpg
    :width: 300px
    :align: center

Per ricevere token **ERC20** e **ERC223** si utilizza lo stesso identico **address di Ethereum**. I wallet di Bitcoin e Litecoin hanno invece un indirizzo completamente diverso, ma il meccanismo per visualizzare l’address e condividerlo è identico.

Eidoo non supporta la generazione di indirizzi con un importo predeterminato (EIP-681).

.. hint::
    Mentre l’address del wallet di Ethereum non cambia mai, ogni volta che si ricevono bitcoin e litecoin l’indirizzo del wallet cambia. 
    Questa caratteristica è tipica degli *hierarcal deterministic wallet* ed è desiderata per proteggere meglio la vostra privacy, quindi non preoccupatevi se vedete l’indirizzo di Bitcoin cambiare ad ogni transazione. Anche se potete tranquillamente continuare a utilizzare gli indirizzi "vecchi" per ricevere bitcoin o litecoin, è sempre meglio utilizzare indirizzi nuovi per lasciare tracce meno evidenti sulla blockchain. Noterete che anche se gli address cambiano il saldo del vostro wallet viene aggiornato correttamente.

.. warning::
    Il vostro indirizzo di Ethereum è la vostra chiave pubblica dalla quale non è mai possibile risalire alla chiave privata, per cui non è pericoloso condividerlo dal punto di vista della sicurezza. Ma data la trasparenza della blockchain, attraverso il vostro indirizzo è possibile risalire a numerose informazioni come saldo, movimenti, operazioni su exchange, etc etc. quindi **condividetelo solo con persone e soggetti di cui vi fidate**.

Tempi di deposito delle criptovalute
-------------------------------------

Ogni asset richiede un certo numero di conferme (cioè numero di blocchi in cui compare la transazione) prima di essere depositato sul wallet e diventare utilizzabile dall’utente. Mentre Ethereum richiede pochi minuti, Litecoin e Bitcoin richiedono 6 conferme. Per Litecoin mediamente si parla di 15-20 minuti mentre per Bitcoin si può arrivare a più di un ora prima di vedere il proprio deposito nel wallet, in condizioni di blockchain normali (quando è intasata possono passare giorni!).

Non preoccupatevi quindi se non vedete i vostri asset immediatamente ma abbiate pazienza di aspettare i blocchi necessari. Monitorate la vostra transazione con un block explorer come ad esempio `Etherscan <https://etherscan.io/>`_ per Ethereum o `BlockChair <https://blockchair.com/bitcoin/>`_ per Bitcoin.

Dopo aver ricevuto i vostri primi fondi, la schermata iniziale “**I tuoi asset**” rappresenterà il vostro nuovo saldo. Cliccando sull’icona in alto a sinistra potrete visualizzare l’**andamento del vostro portafoglio di Ethereum** grazie al widget fornito da `Cryptonomist <http://cryptonomist.com/>`_.

.. image:: https://i.imgur.com/Ps42tLA.jpg
    :width: 300px
    :align: cente

Lo `storico delle transazioni <https://eidoo.readthedocs.io/it/latest/gestione.html#storico-delle-proprie-transazioni>`_ di ogni criptovaluta può essere visualizzato cliccando sulla stessa, in questo esempio **BTC**.

.. image:: https://i.imgur.com/7CPVVqG.jpg
    :width: 300px
    :align: cente

Invio dei token e delle criptovalute supportate
-------------------------------------------------------------------------------

Una volta che nel wallet sono presenti dei fondi diventa possibile trasferirli ad altri address.
Dalla schermata principale “**I tuoi asset**" cliccate sulla criptovaluta che volete trasferire. L’immagine seguente mostra ad il wallet di ETH dopo diverse operazioni (le operazioni a 0 ETH sono operazioni con smart contract come quello dell’exchange di Eidoo).
Per l’invio di ETH, dopo aver premuto **ETH** nella schermata principale. Cliccate sul tasto **Trasferisci**.

.. image:: https://i.imgur.com/i34brCk.jpg
    :width: 300px
    :align: center


Dovete ora inserire l’indirizzo a cui volete trasferire gli ether. Cliccate nel campo  **Scegli beneficiario**.

.. image:: https://i.imgur.com/qn16rix.jpg
    :width: 300px
    :align: center

Potete a questo punto **incollare l’indirizzo** che avete copiato precedentemente nella clipboard del vostro dispositivo scegliendo **Incolla**, o scannerizzare un **QRCode** con la fotocamera dello smartphone per acquisire direttamente l’indirizzo da un altro dispositivo cliccando su **Scannerizza un codice QR**. Questa funzione è molto utile per mandare importi ad un amico che ha una app sul telefono o a un sito web che visualizza il codice QR.
 
Eidoo supporta anche gli **indirizzi ENS**.

.. image:: https://i.imgur.com/wPYHAyr.jpg
    :width: 300px
    :align: center

Eidoo ha tolto la modalità di inserimento manuale degli indirizzi in formato esadecimale, eliminando così ogni possibilità di errore umano.  Gli unici indirizzi che si possono inserire manualmente sono gli indirizzi ENS.

.. note::
    ENS (Ethereum Name Service) è un tipo di indirizzo di Ethereum basato su smart contract, il che significa che non soffre dell'insicurezza del sistema DNS.
    ENS opera in modo distribuito sia per la sua infrastruttura che per la governance. Chiunque può registrare da solo un nome di dominio .eth partecipando
    a un processo di asta, mediato dalla blockchain. 
    ENS elimina la necessità di copiare o digitare i classici indirizzi lunghi di Ethereum. Un indirizzo ENS è per esempio ``vitalik.eth`` anziché 
    ``0x48AfeA5E66a7d0dfb83F341e45D507757a559650`` e risulta quindi molto pratico.
    
    L'unica controindicazione è che espone a problemi di privacy in quanto è più facile ricondurre le transazioni al nome con cui si è registrato l'indirizzo ENS.


Immettete poi la quantità di ETH che volete inviare nel campo Eidoo vi mostra il quantitativo disponibile, cliccando su di esso invierete l’intero importo del wallet.

.. note::
    Mantenete sempre un **saldo minimo** di almeno 0,1 ETH nel vostro wallet di Eidoo in quanto è necessario pagare il GAS per ogni transazione,
    sia essa uno scambio, uno swap o un trasferimento. Nel caso il vostro saldo per poter continuare a utilizzare le funzionalità di Eidoo dovrete
    reintegrarlo con un nuovo acquisto o mandando un importo da un indirizzo esterno.

Una volta scelto l’indirizzo del destinatario della transazione inserite l’importo che volete spedire e cliccate su “**PROCEDI**”.

.. image:: https://i.imgur.com/SIhFbmM.jpg
    :width: 300px
    :align: center

Eidoo calcolerà in automatico il prezzo la quantità di GAS necessaria per una transazione di **priorità media**. In alternativa potete cliccare in alto a sinistra sul simbolo di equalizzazione e: 
* stabilire la priorità secondo i preset **BASSA, NORMALE, ALTA***;
* immettere manualmente il **Gas Limit***;
* aumentare o diminuire il Gas di 1000 unità alla volta con i tasti **+** e **–**.

.. image:: https://i.imgur.com/KMiI7Iy.jpg
    :width: 300px
    :align: center

In questa schermata è presente anche una opzione avanzata per inserire una stringa nel campo **Data (hexadecimal)**. Non utilizzatela a meno che non sappiate quello che state facendo, la maggior parte dei casi non vi servirà.
Una volta inserite le informazioni, premete su "**CONFERMA CON PASSWORD**" se siete nella schermata di **Impostazioni Avanzate** o su "**PROCEDI**" se siete nella schermata **Trasferisci dal wallet personale**.

.. image:: https://i.imgur.com/MPwDOMH.jpg
    :width: 300px
    :align: center
    
.. image:: https://i.imgur.com/wqexsQA.jpg
    :width: 300px
    :align: center
    
Dovete ora confermare inserendo la vostra **password di spesa**, quella che avete scelto inizialmente per il wallet.
Inserite la password e cliccate su “**CONFERMA**” per spedire la transazione.
 
.. image:: https://i.imgur.com/yh48Rwl.jpg
    :width: 300px
    :align: center

Una schermata di conferma apparirà quando la transazione sarà stata inviata alla blockchain. Cliccate su “**VAI ALLA LISTA DI TRANSAZIONI**” per vedere lo storico delle transazioni relative a questo asset.
 
.. image:: https://i.imgur.com/dekvRXU.jpg
    :width: 300px
    :align: center

Storico delle proprie transazioni
-----------------------------------

Dalla schermata principale premete sulla criptovaluta di cui volete visualizzare la storia delle transazioni, ad esempio ETH.

.. image:: https://i.imgur.com/Stpho2W.jpg
    :width: 300px
    :align: center

Cliccando su ciascuna transazione visualizzerete i dettagli della stessa. Premendo invece su sul simbolo "**<**" in alto a sinistra tornerete alla
schermata iniziale “**I tuoi asset**”.

.. image:: https://i.imgur.com/PX8mUX6.jpg
    :width: 300px
    :align: center

Lo storico delle transazioni è di facile lettura grazie anche alle icone che vi permettono di capire immediatamente che tipo di transazioni sono e il
loro stato:

.. list-table:: 
   :widths: 25 25
   :header-rows: 1

   * - Simbolo
     - Tipo di Transazione
   * - .. image:: https://i.imgur.com/JQuAe49.png
     - Transazione in uscita in sospeso
   * - .. image:: https://i.imgur.com/dIfvPuw.png
     - Transazione in uscita in sospeso
   * - .. image:: https://i.imgur.com/atHi2Hp.png
     - Transazione in uscita da smart contract (ad es. scambio o swap)
   * - .. image:: https://i.imgur.com/smfFRlU.png
     - Transazione ricevuta

Token Non Fungibili NFT
---------------------------

Eidoo supporta anche i token NFT.

.. note:: 
    I token non fungibili (Non Fungible Tolens, NFT) sono elementi collezionabili all'interno della blockchain.
    Ogni token NFT si riferisce a un singolo elemento con un certo valore, e rappresenta qualcosa di unico e quindi
    senza un valore reciproco intercambiabile. In altre parole, nessun token non fungibile è lo stesso.

Il mercato dei token NFT è in pieno sviluppo e questa funzionalità di Eidoo unita alla possibilità di utilizzare altri servizi tramite  
`WalletConnect <https://eidoo.readthedocs.io/it/latest/walletconnect.html#walletconnect-tutti-i-protocolli-a-portata-di-qr-code>`_ risulta molto utile.

In particolare Eidoo supporta i token NFT su Ethereum. Per vedere i vostri NFT scorrete il banner centrale fino a quando non trovate "**NFT Manager**".

.. image:: https://i.imgur.com/rFD36Ny.jpg
    :width: 300px
    :align: center

Cliccateci sopra e scegliete "**MANAGE MY NFTS**" per vedere e spedire i vostri NFT.

.. image:: https://i.imgur.com/MYyiVLQ.jpg
    :width: 300px
    :align: center

Cliccando su "**DISCOVER NFTS**" aprirete un `link <https://opensea.io/blog/guides/non-fungible-tokens/?lang=it>`_ in inglese di approfondimento sul sito di OpenSea, uno dei maggiori mercati di NFT.

Nascondere il saldo di un token
-------------------------------

Il wallet di Eidoo offre la possibilità di nascondere dalla schermata iniziale il saldo dei token o di una criptovaluta che non vi interessano, magari ricevuti in airdrop e che non hanno un valore interessante, o che avete già scambiato e nonostante il saldo sia 0 vengono comunque mostrati.

Dalla schermata “**I tuoi asset**” andate sulla lista dei token scorrendo la pagina in basso.

.. image:: https://i.imgur.com/92f7IsH.jpg
    :width: 300px
    :align: center
 
Scorrete verso destra la criptovaluta o il token che non vi interessa e cliccate sul simbolo di Nascondi.

.. image:: https://i.imgur.com/7qYkP9V.jpg
    :width: 300px
    :align: center
 
Per ripristinare un token nascosto andate nel menu delle `impostazioni <https://eidoo.readthedocs.io/it/latest/impostazioni.html#impostazioni-avanzate>`_ in basso a destra dalla schermata iniziale e “**asset nascosti**”.

