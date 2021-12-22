**3.2 Application Programming Interface (API)**
===============================================

Nell’ambito della comunicazione tra sistemi esterni e TDH vengono
definite due modalità di interscambio:

-  API web RESTful (consigliata),

-  Web Services su standard SOAP, qualora i sistemi non prevedano
   l’utilizzo di *API web RESTful.*

Per API (Application Programming Interface) si intende “un insieme di
protocolli/ funzionalità/ definizioni attraverso le quali è possibile
realizzare sistemi applicativi integrati; in tal senso, l'API è
concepita come una "black box", ossia una funzionalità richiamabile per
la quale è necessario solo conoscerne l'interfaccia, senza la necessità
di conoscere eventuali dettagli implementativi” [1]_.

Le Web API sono delle API richiamabili da Web (principalmente basate su
protocollo HTTP), il cui obiettivo è di ottenere un alto livello di
astrazione che si interpone tra lo strato di logica e i client che ne
richiedono il servizio. Le Web API sono principalmente di tipo REST o di
tipo SOAP.

Il formato dati per le Web API SOAP (o Web Service SOAP) è di tipo XML,
mentre per le API web RESTful è possibile sfruttare i formati previsti
dal protocollo HTTP come definito dalla W3C.

In ambito API web RESTful, si fa riferimento all’architettura REST,
secondo il modello di maturità di Richardson [2]_; in tal senso, il
modello RESTful è compliant con il livello 3 di maturità - Hypermedia
Controls.

Le Linee Guida individuano le modalità con cui gli sviluppatori/aderenti
al TDH022 implementano le proprie API, quali elementi tecnologici di
base attraverso i quali è possibile stabilire l’interconnessione con il
TDH e la fruizione di servizi e/o contenuti da parte degli utenti
finali.

.. [1]
   “Linee Guida sull’interoperabilità tecnica della Pubbliche
   Amministrazioni” – paragrafo 3.2 (si rimanda alla sezione
   “Bibliografia e Sitografia di riferimento” a fine documento per link
   con redirect al documento)

.. [2]
   Il Richardson Maturity Model è un modello che fornisce delle linee
   guida per la creazione di servizi REST e consiste in 4 livelli (da 0
   a 3) con ogni livello superiore a cui corrisponde un'aderenza più
   completa al design REST relativamente al servizio/API creato. Il
   livello successivo contiene anche tutte le caratteristiche del
   precedente; il livello 3 rispetta le caratteristiche tecniche di un
   Web Service RESTful \| Fonte: “A Maturity Model for Semantic RESTful
   Web APIs” (Salvadori, Siquera – 06/2015) Riferimento Online:
   https://www.researchgate.net/publication/281287283_A_Maturity_Model_for_Semantic_RESTful_Web_APIs
