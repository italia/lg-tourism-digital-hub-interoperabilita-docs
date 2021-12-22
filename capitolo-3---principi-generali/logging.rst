**3.6 Logging**\  [1]_
=======================

Il logging riveste un ruolo fondamentale nella progettazione e nello
sviluppo di API. Le moderne piattaforme middleware, oltre ad integrare
meccanismi di logging interni, possono connettersi ad API esterne che
permettono la raccolta (log collection), la ricerca e la produzione di
analytics, utili all’identificazione di problemi e al monitoraggio del
sistema e della QoS. L’utilizzo di log collector permette di
centralizzare non solo i log relativi all’utilizzo delle API, ma anche
quelli di eventuali altri servizi digitali e componenti di rete (ad es.
proxy e application-gateway). Ai fini di non ripudio, i messaggi
applicativi possono essere memorizzati insieme alla firma digitale, ed
archiviati nel rispetto della normativa sulla conservazione e sulla
privacy. L’erogatore deve documentare in dettaglio il formato e le
modalità di tracciatura, consultazione e reperimento delle informazioni.

|image0|

*Figura 3 - Schema esplicativo del processo di logging TDH*

Nell’ambito dell’interoperabilità TDH022, l’erogatore non traccerà nei
log informazioni riservate quali password, chiavi private o token di
autenticazione; inoltre dovrà tracciare un evento per ogni richiesta
contenente almeno i seguenti parametri minimi:

-  Timestamp della richiesta;

-  identificativo del fruitore e dell’operazione richiesta;

-  tipologia di chiamata;

-  esito della chiamata;

-  ove applicabile, identificativo del Consumatore del Servizio API o
   altro soggetto operante la richiesta comunicato dal Fruitore - che
   provvederà alla codifica e all’anonimizzazione, ove necessario;

-  un identificativo univoco della richiesta, utile a eventuali
   correlazioni.

.. [1]
   Il contenuto di questo paragrafo è in linea con quanto prescritto
   dalle “Linee Guida sull’interoperabilità tecnica delle Pubbliche
   Amministrazioni” edite da AgID, di cui al paragrafo 3.6 del documento
   citato (si rimanda alla sezione “Bibliografia e Sitografia di
   riferimento” a fine documento per link con redirect al documento)

.. |image0| image:: ../media/image4.png
   :width: 6.38971in
   :height: 1.5in
