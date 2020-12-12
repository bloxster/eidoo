Gestione delle criptovalute con eidoo
=====================================

Eidoo è un wallet di criptovalute `HD <https://www.cryptohelper.it/glossario/hd-wallet-hierarchical-deterministic-wallet/>`_ sicuro e “non custodial”, in cui i fondi rimangono sempre nelle mani dell’utente.


Criptovalute Supportate
-----------------------

Eidoo supporta le seguenti criptovalute:

* Bitcoin (BTC)
* Litecoin (LTC)
* Ethereum (ETH)
   * token ERC20
   * token ERC23
   * token ERC721 (NFT, token non fungibili)


Visualizzazione dell’indirizzo di deposito di una delle criptovalute supportate
-------------------------------------------------------------------------------

La schermata principale **“I tuoi asset”** mostra il vostro saldo. Essendo il wallet appena creato è chiaramente vuoto: 0 BTC, 0 ETH, 0 LTC, etc. etc.
Le valute supportate da Eidoo sono attualmente **Bitcoin**, **Litecoin**, **Ether**, token **ERC20** (PNT, USDT, DAI, BAT, etc., 
`qui <https://eidoo.io/erc20-tokens-list>`_ una lista completa) o token **NFT**.

Per ricevere sul vostro wallet un di queste criptovalute dovete innanzitutto visualizzare il vostro indirizzo di deposito (o *address*).

**IMPORTANTE: prima di depositare qualsiasi asset fate una prova con un importo minimo per verificare che l’address sia corretto e che non ci siano problemi.**

Cliccate in alto a destra il QR code per visualizzare il menu per la scelta della criptovaluta da depositare.

.. image:: https://i.imgur.com/ViVjALd.jpg
    :width: 500px
    :align: center

Cliccate sulla criptovaluta che volete gestire, ad esempio **ETH**.

.. image:: https://i.imgur.com/uHWDfKT.jpg
    :width: 500px
    :align: center

Cliccando su **AGGIUNGI FONDI** in basso al centro, o su Deposito in alto a sinistra visualizzerete il vostro **QR CODE** al centro. Questo può essere utile nel caso in cui vogliate ricevere un pagamento da un amico che utilizza a sua volta un wallet mobile come Eidoo. Semplicemente inquadrando questo codice il wallet è in grado di determinare il vostro address. 

In basso trovate anche il relativo **indirizzo di deposito** in formato esadecimale. Con i tasti **"CONDIVIDI"** e **"COPIA"** potete rispettivamente inviare il vostro address tramite SMS, mail, social o copiare l'indirizzo completo nella memoria del vostro smartphone.

.. image:: https://i.imgur.com/3FcxdZZ.jpg
    :width: 500px
    :align: center

Per ricevere token **ERC20 e ERC223** si utilizza lo stesso identico **address di Ethereum.**. I wallet di Bitcoin e Litecoin hanno invece un indirizzo completamente diverso, ma il meccanismo per visualizzare l’address e condividerlo è identico.

Eidoo non supporta per la generazione di indirizzi con un importo predeterminato (EIP-681).

.. note::
    Mentre l’address del wallet di Ethereum non cambia mai, ogni volta che si ricevono bitcoin e litecoin l’indirizzo del wallet cambia. Questa caratteristica     denominata      *hierarcal deterministic wallet* è desiderata per proteggere meglio la vostra privacy, quindi non preoccupatevi se vedete l’indirizzo di Bitcoin cambiare ad         ogni       transazione. Anche se potete tranquillamente continuare a utilizzare gli indirizzi vecchi per ricevere bitcoin o litecoin, meglio utilizzare indirizzi sempre nuovi             per lasciare meno tracce sulla blockchain. Noterete che anche se gli address cambiano il saldo del vostro wallet viene aggiornato correttamente.

.. warning::
    Il vostro indirizzo di Ethereum è la vostra chiave pubblica dalla quale non è mai possibile risalire alla chiave privata, per cui non è
    pericoloso condividerlo dal punto di vista della sicurezza. Ma data la trasparenza della blockchain, attraverso il vostro indirizzo è possibile
    risalire a numerose informazioni come saldo, movimenti, operazioni su exchange, etc etc. quindi **condividetelo solo con persone e
    soggetti di cui vi fidate**.

Tempi di deposito delle criptovalute
-------------------------------------------------------------------------------

Ogni asset richiede un certo numero di conferme (cioè numero di blocchi in cui compare la transazione) prima di essere depositato sul wallet e diventare utilizzabile dall’utente. Mentre Ethereum richiede pochi minuti, Litecoin e Bitcoin richiedono 6 conferme. Per Litecoin mediamente si parla di 15-20 minuti mentre per Bitcoin si può arrivare a più di un ora prima di vedere il proprio deposito nel wallet, in condizioni di blockchain normali (quando è intasata possono passare giorni!).

Non preoccupatevi quindi se non vedete i vostri asset immediatamente ma abbiate pazienza di aspettare i blocchi necessari. Monitorate la vostra transazione con un block explorer come ad esempio `Etherscan <https://etherscan.io/>`_ per Ethereum o `BlockChair <https://blockchair.com/bitcoin/>`_ per Bitcoin.

Dopo aver ricevuto i vostri primi fondi, la schermata iniziale “**I tuoi asset**” rappresenterà il vostro nuovo saldo. Cliccando sull’icona in alto a sinistra potrete visualizzare l’**andamento del vostro portafoglio di Ethereum** grazie al widget fornito da `Cryptonomist.com <http://cryptonomist.com/>`_.

.. image:: https://i.imgur.com/Ps42tLA.jpg
    :width: 500px
    :align: cente

Lo storico delle transazioni di ogni criptovaluta può essere visualizzato cliccando sulla stessa, in questo esempio **BTC**.

.. image:: https://i.imgur.com/7CPVVqG.jpg
    :width: 500px
    :align: cente

Invio dei token e delle criptovalute supportate
-------------------------------------------------------------------------------

Una volta che nel wallet sono presenti dei fondi diventa possibile trasferirli ad altri address.
Dalla schermata principale “**I tuoi asset**" cliccate sulla criptovaluta che volete trasferire. L’immagine seguente mostra ad il wallet di ETH dopo diverse operazioni (le operazioni a 0 ETH sono operazioni con smart contract come quello dell’exchange di Eidoo).
Per l’invio di ETH, dopo aver premuto **ETH **nella schermata principale. Cliccate sul tasto **Trasferisci**.

.. image:: https://i.imgur.com/suMgNU3.jpg
    :width: 500px
    :align: center

Dovete ora inserire l’indirizzo a cui volete trasferire gli ether. Cliccate nel campo  **Scegli beneficiario**.

.. image:: https://i.imgur.com/7wkk68y.jpg
    :width: 500px
    :align: center

Potete a questo punto **incollare l’indirizzo** che avete copiato precedentemente nella clipboard del vostro dispositivo scegliendo **Incolla**, o scannerizzare un **QRCode** con la fotocamera dello smartphone per acquisire direttamente l’indirizzo da un altro dispositivo cliccando su **Scannerizza un codice QR**. Questa funzione è molto utile per mandare importi ad un amico che ha una app sul telefono o a un sito web che visualizza il codice QR.
 
Eidoo supporta anche gli **indirizzi ENS** come 'vitalik.eth', facili da ricordare e da inserire.

.. image:: https://i.imgur.com/cWml80Y.jpg
    :width: 500px
    :align: center

Eidoo ha tolto la modalità di inserimento manuale degli indirizzi in formato esadecimale, eliminando così ogni possibilità di errore umano.  Gli unici indirizzi che si possono inserire manualmente (INSERISCI L’INDIRIZZO) sono gli indirizzi ENS.
Immettete poi la quantità di ETH che volete inviare nel campo Eidoo vi mostra il quantitativo disponibile, cliccando su di esso invierete l’intero importo del wallet.

.. note::
    Mantenete sempre un **saldo minimo** di almeno 0,1 ETH nel vostro wallet di Eidoo in quanto è necessario pagare il GAS per ogni transazione,
    sia essa uno scambio, uno swap o un trasferimento. Nel caso il vostro saldo per poter continuare a utilizzare le funzionalità di Eidoo dovrete
    reintegrarlo con un nuovo acquisto o mandando un importo da un indirizzo esterno.

Una volta scelto l’indirizzo del destinatario della transazione inserite l’importo che volete spedire e cliccate su “**PROCEDI**”.

.. image:: https://i.imgur.com/qKV6BIV.jpg
    :width: 500px
    :align: center

Eidoo calcolerà in automatico il prezzo la quantità di GAS necessaria per una transazione di **priorità media**. In alternativa potete cliccare in alto a sinistra sul simbolo di equalizzazione e: 
* stabilire la priorità secondo i preset **BASSA, NORMALE, ALTA***;
* immettere manualmente il **Gas Limit***;
* aumentare o diminuire il Gas di 1000 unità alla volta con i tasti **+** e **–**.

.. image:: https://i.imgur.com/8PrVr29.jpg
    :width: 500px
    :align: center

In questa schermata è presente anche una opzione avanzata per inserire una stringa nel campo **Data (hexadecimal)**. Non utilizzatela a meno che non sappiate quello che state facendo, la maggior parte dei casi non vi servirà.
Una volta inserite le informazioni, premete su **CONFERMA CON PASSWORD** se siete nella schermata di **Impostazioni Avanzate** o su **PROCEDI** se siete nella schermata **Trasferisci dal wallet personale.**

.. image:: https://i.imgur.com/hD0CIh8.jpg
    :width: 500px
    :align: center
    
.. image:: https://i.imgur.com/qKV6BIV.jpg
    :width: 500px
    :align: center
    
Dovete ora confermare inserendo la vostra **password di spesa**, quella che avete scelto inizialmente per il wallet.
Inserite la password e cliccate su “**CONFERMA**” per spedire la transazione.
 
.. image:: https://i.imgur.com/euBXcBD.jpg
    :width: 500px
    :align: center

Una schermata di conferma apparirà quando la transazione sarà stata inviata alla blockchain. Cliccate su “**VAI ALLA LISTA DI TRANSAZIONI**” per vedere le transazioni relative a questo asset (vedi capitolo dedicato).
 
.. image:: https://i.imgur.com/mp0oYq3.jpg
    :width: 500px
    :align: center

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

.. image:: https://i.imgur.com/KJ9NIp2.jpg
    :width: 500px
    :align: center

Cliccateci sopra e scegliete "**MANAGE MY NFTS**" per vedere e spedire i vostri NFT.

.. image:: https://i.imgur.com/tOL7ZHd.jpg
    :width: 500px
    :align: center

Cliccando su "**DISCOVER NFTS**" aprirete un `link <https://opensea.io/blog/guides/non-fungible-tokens/?lang=it>`_ in inglese di approfondimento sul sito di OpenSea, uno dei maggiori mercati di NFT.

