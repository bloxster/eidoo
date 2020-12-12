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
Le valute supportate da Eidoo sono attualmente **Bitcoin**, **Litecoin**, **Ether** o token **ERC20** quali PNT, USDT, DAI, BAT, etc., 
`qui <https://eidoo.io/erc20-tokens-list>`_ una lista completa.

Per ricevere sul vostro wallet un di queste criptovalute dovete innanzitutto visualizzare il vostro indirizzo (o *address*).

**IMPORTANTE: prima di depositare qualsiasi asset fate una prova con un importo minimo per verificare che l’address sia corretto e che non ci siano problemi.**

Cliccate in alto a destra il QR code per visualizzare il menu per la scelta della criptovaluta da depositare.

Cliccate sulla criptovaluta che volete gestire, ad esempio **ETH,** e vi si aprirà una schermata che rappresenta il saldo di ETH e lo storico delle transazioni, nel caso ce ne siano.

.. image:: ./images/kix.mw5xrn33nyrn.png


`Apple Store <https://itunes.apple.com/app/eidoo/id1279896253?mt=8>`_                     



 
Vedrete che per alcuni coin/token sono già presenti le opzioni di **COMPRA** e **SWAP** che vedremo in seguito.
*Per l’opzione ***Bitcoin su Ethereum*** ***(pBTC)*** o gli asset tokenizzati di pToken in genere vedete il capitolo dedicato.*
.. image:: ./images/kix.e9jvn1gborve.png



 
Cliccando su **AGGIUNGI FONDI **in basso al centro, o su Deposito in alto a sinistra visualizzerete il vostro **QR CODE **e il relativo** address **in formato esadecimale in basso.

.. image:: ./images/kix.gg3bu3uqra25.png



Per ricevere token **ERC20 e ERC223** si utilizza l’**address di Ethereum. **I wallet di Bitcoin e Litecoin hanno invece un indirizzo completamente diverso, ma il meccanismo per visualizzare l’address è identico.
Ogni asset richiede un certo numero di conferme (cioè numero di blocchi in cui compare la transazione) prima di essere depositato sul wallet e diventare utilizzabile dall’utente. Mentre Ethereum richiede pochi minuti, Litecoin e Bitcoin richiedono 6 conferme. Per Litecoin mediamente si parla di 15-20 minuti mentre per Bitcoin si può arrivare a più di un ora prima di vedere il proprio deposito nel wallet, in condizioni di blockchain normali (quando è intasata possono passare giorni!).
Non preoccupatevi quindi se non vedete i vostri asset immediatamente ma abbiate pazienza di aspettare i blocchi necessari. Monitorate la vostra transazione con un block explorer (``Etherscan`_ <https://etherscan.io/>`_,`` `_ <https://live.blockcypher.com/>`_``Blockcypher.com`_ <https://live.blockcypher.com/>`_ ).
Dopo aver ricevuto i vostri primi fondi, la schermata iniziale “**I tuoi asset**” rappresenterà il vostro nuovo saldo.
Cliccando sull’icona in alto a sinistra potrete visualizzare l’**andamento del vostro portafoglio di Ethereum **grazie al widget fornito da`` `_ <http://cryptonomist.com/>`_``Cryptonomist.com`_ <http://cryptonomist.com/>`_.

.. image:: ./images/kix.r5ynfmr07yzu.png



 
Lo storico delle transazioni di ogni criptovaluta può essere visualizzato cliccando sulla stessa, in questo esempio **BTC**.


**ATTENZIONE**: mentre l’address del wallet di Ethereum non cambia mai, ogni volta che si ricevono bitcoin e litecoin l’indirizzo del wallet cambia. Questa caratteristica  denominata *hierarcal deterministic wallet* è desiderata per proteggere meglio la vostra privacy, quindi non preoccupatevi se vedete l’indirizzo di Bitcoin cambiare ad ogni transazione. Anche se potete tranquillamente continuare a utilizzare gli indirizzi vecchi per ricevere bitcoin o litecoin, meglio utilizzare indirizzi sempre nuovi per lasciare meno tracce sulla blockchain. Noterete che anche se gli address cambiano il saldo del vostro wallet viene aggiornato correttamente.

Condivisione del proprio indirizzo
==================================
Cliccando su **COPIA** nella schermata dell’indirizzo copierete l’indirizzo di Ethereum sulla clipboard del vostro smartphone in modo da poterla poi “incollare” su qualsiasi applicazione.
 
.. image:: ./images/kix.ksjabtq151d7.png



Premendo invece il pulsante **CONDIVIDI **potete** **inviare direttamente il vostro indirizzo attraverso la modalità di condivisione dello smartphone ad es. sui vari social.
Eidoo non supporta la generazione o la lettura di indirizzi con un importo pre-determinato (EIP-681).
**ATTENZIONE**: il vostro indirizzo di Ethereum è la vostra chiave pubblica dalla quale non è mai possibile risalire alla chiave privata, per cui non è pericoloso condividerlo dal punto di vista della sicurezza. Ma data la trasparenza della blockchain, attraverso il vostro indirizzo è possibile risalire a numerose informazioni come saldo, movimenti, operazioni su exchange, etc etc. quindi è opportuno **condividerlo solo con persone e soggetti di cui vi fidate**.

Invio dei token e delle criptovalute supportate
===============================================
Una volta che nel wallet sono presenti dei fondi diventa possibile trasferirli ad altri address.
Dalla schermata principale “**“I tuoi asset””** cliccate sulla criptovaluta che volete trasferire. L’immagine seguente mostra ad il wallet di ETH dopo diverse operazioni (le operazioni a 0 ETH sono operazioni con smart contract come quello dell’exchange di Eidoo).
Per l’invio di ETH, dopo aver premuto **ETH **nella schermata principale. Cliccate sul tasto “**Trasferisci**”.
.. image:: ./images/kix.nahb4stor7ll.png





Dovete ora inserire l’indirizzo a cui volete trasferire gli ether. Cliccate nel campo** Scegli beneficiario**.

.. image:: ./images/kix.rsjmm8846gmj.png



Potete a questo punto **incollare l’indirizzo **che avete copiato precedentemente nella clipboard del vostro dispositivo scegliendo **Incolla**, o scannerizzare un **QRCode **con la fotocamera dello smartphone per acquisire direttamente l’indirizzo da un altro dispositivo cliccando su **Scannerizza un codice QR**. Questa funzione è molto utile per mandare importi ad un amico che ha una app sul telefono o a un sito web che visualizza il codice QR.
 
Eidoo supporta anche gli **indirizzi ENS** come vitalik.eth, facili da ricordare e da inserire.



.. image:: ./images/kix.tnzphp3duqfs.png





Eidoo ha tolto la modalità di inserimento manuale degli indirizzi in formato esadecimale, eliminando così ogni possibilità di errore umano.  Gli unici indirizzi che si possono inserire manualmente (INSERISCI L’INDIRIZZO) sono gli indirizzi ENS.
Immettete poi la quantità di ETH che volete inviare nel campo Eidoo vi mostra il quantitativo disponibile, cliccando su di esso invierete l’intero importo del wallet.
**ATTENZIONE**: **mantenete sempre un saldo di almeno 0,1 ETH** nel vostro wallet di Eidoo in quanto è necessario pagare il GAS per ogni transazione, sia essa uno scambio, uno swap o un trasferimento. Nel caso il vostro saldo per poter continuare a utilizzare le funzionalità di Eidoo dovrete reintegrarlo con un nuovo acquisto o mandando un importo da un indirizzo esterno.
Una volta scelto l’indirizzo del destinatario della transazione inserite l’importo che volete spedire e cliccate su “**PROCEDI**”.

.. image:: ./images/kix.tn7do63ayeqr.png

  
 
Eidoo calcolerà in automatico il prezzo la quantità di GAS necessaria per una transazione di **priorità media**.
In alternativa potete cliccare in alto a sinistra sul simbolo di equalizzazione e:
* stabilire la priorità** **secondo i preset **BASSA, NORMALE, ALTA*** immettere manualmente il **Gas Limit*** aumentare o diminuire il Gas di 1000 unità alla volta con i tasti **+** e **–**.

.. image:: ./images/kix.rdncp7rv2q9c.png



In questa schermata è presente anche una opzione avanzata per inserire una stringa nel campo **Data (hexadecimal)**. Non utilizzatela a meno che non sappiate quello che state facendo.
Una volta inserite le informazioni, premete su **CONFERMA CON PASSWORD **se siete nella schermata di **Impostazioni Avanzate** o su **PROCEDI **se siete nella schermata **Trasferisci dal wallet personale.** 
.. image:: ./images/kix.l9691otuxbio.png



Dovete ora confermare inserendo la vostra **password di spesa**, quella che avete scelto inizialmente per il wallet.
Inserite la password e cliccate su “**CONFERMA**” per spedire la transazione.
 
.. image:: ./images/kix.blkylxfm1tuk.png



Una schermata di conferma apparirà quando la transazione sarà stata inviata alla blockchain. Cliccate su “**VAI ALLA LISTA DI TRANSAZIONI**” per vedere le transazioni relative a questo asset (vedi capitolo dedicato).
 
 


** **
.. image:: ./images/kix.n17h4kvffk3y.png


Token nNon Fungibili NFT
===============================================

Eidoo supporta anche i token non fungibili o NFT. Gli NFT sono lll


