**5.1 Web Service SOAP (simple object access protocol)**
========================================================

SOAP è un protocollo utilizzato per l’interscambio di messaggi che,
sebbene possa poggiarsi su diversi protocolli di rete (es. JMS), è
standardizzato per il solo protocollo http (W3C).

SOAP, che ha visto il suo successo con l’affermarsi delle architetture a
servizi si basa su XML con una struttura di tipo “header-body”,
suddivisa nelle seguenti sezioni:

-  **Soap-Header** *(opzionale)*: in questa sezione sono presenti dati
   non legati al contenuto dell’informazione da scambiare, bensì ai
   metadati relativi ai processi di logging, instradamento, sicurezza e
   orchestrazione;

-  **Soap-Body** *(obbligatoria)*: in questa sezione sono presenti i
   dati legati all’informazione da trasmettere.

Il descrittore delle interfacce è basato sul metalinguaggio WSDL (Web
Service Description Language) e, in tal senso, per poter permettere ai
sistemi di comunicare tra loro a mezzo SOAP, è necessario che gli stessi
sistemi possano scambiare il WSDL.

La chiamata SOAP, in ultimo, utilizza esclusivamente il metodo POST di
http, con possibilità di inviare degli allegati alla richiesta.
