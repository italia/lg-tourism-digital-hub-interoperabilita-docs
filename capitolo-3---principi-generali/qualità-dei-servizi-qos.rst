**3.3 Qualità dei Servizi (QoS)**\  [1]_
========================================

Qualità dei Servizi, comunemente chiamata Quality of Service (QoS), fa
riferimento alla descrizione non funzionale di API, ovvero alla capacità
di quest’ultima di soddisfare le aspettative dei fruitori.

Assicurare la QoS in ambito Internet ai fini dell’interoperabilità è una
sfida critica a causa della natura dinamica e in costante evoluzione del
contesto tecnologico. Cambiamenti negli schemi di traffico, la presenza
di transazioni critiche, gli effetti dei problemi di rete, le
performance dei protocolli e degli standard di rete richiedono una
definizione accurata e precisa della QoS offerta da una API.

Gli elementi chiave a supporto della QoS possono essere riassunti come
segue:

+-----------------------------------+-----------------------------------+
| **Disponibilità**                 | La probabilità che una API sia    |
|                                   | disponibile e funzionante in un   |
|                                   | istante casuale. Associato al     |
|                                   | concetto di disponibilità è       |
|                                   | quello di Time-To-Repair (TTR),   |
|                                   | ovvero il tempo necessario a      |
|                                   | ripristinare una API una volta    |
|                                   | che questa diventa indisponibile. |
|                                   | La disponibilità di una API       |
|                                   | dovrebbe potere essere verificata |
|                                   | tramite l’esposizione di una API  |
|                                   | di monitoraggio, dedicata e a     |
|                                   | basso impatto (quindi a elevata   |
|                                   | disponibilità);                   |
+-----------------------------------+-----------------------------------+
| **Accessibilità**                 | La capacità di una API di essere  |
|                                   | contattabile in un qualunque      |
|                                   | istante di tempo;                 |
+-----------------------------------+-----------------------------------+
| **Prestazioni**                   | Misurate solitamente rispetto a   |
|                                   | due valori: il throughput e la    |
|                                   | latenza. Il throughput            |
|                                   | rappresenta il numero di          |
|                                   | richieste soddisfatte in un dato  |
|                                   | intervallo. La latenza            |
|                                   | rappresenta la quantità di tempo  |
|                                   | che passa tra l’invio di una      |
|                                   | richiesta e la ricezione di una   |
|                                   | risposta (una API con buone       |
|                                   | prestazioni ha un elevato         |
|                                   | throughput e una bassa latenza);  |
+-----------------------------------+-----------------------------------+
| **Affidabilità**                  | La capacità di una API di         |
|                                   | funzionare correttamente e        |
|                                   | consistentemente, fornendo la     |
|                                   | stessa QoS a dispetto di          |
|                                   | malfunzionamenti di diversa       |
|                                   | natura. Di solito è espressa in   |
|                                   | termini di fallimenti in un dato  |
|                                   | lasso di tempo;                   |
+-----------------------------------+-----------------------------------+
| **Scalabilità**                   | L’abilità di servire in modo      |
|                                   | consistente, efficiente e         |
|                                   | performante le richieste          |
|                                   | all’aumentare o al diminuire del  |
|                                   | loro numero. È strettamente       |
|                                   | connessa al concetto di           |
|                                   | accessibilità;                    |
+-----------------------------------+-----------------------------------+
| **Sicurezza**                     | Aspetti quali confidenzialità,    |
|                                   | integrità, autorizzazione e       |
|                                   | autenticazione;                   |
+-----------------------------------+-----------------------------------+
| **Transazionalità**               | La capacità di una operazione di  |
|                                   | rispettare l’esecuzione           |
|                                   | transazionale, ove richiesto, è   |
|                                   | parte della QoS.                  |
+-----------------------------------+-----------------------------------+

I soggetti (pubblici o privati) aderenti al TDH che rendono disponibili
dati e contenuti, devono intraprendere tutte le iniziative necessarie a
garantire i requisiti di QoS richiesti dal caso d’uso. Questo include
anche l’utilizzo di buone pratiche, ad esempio, per assicurare
prestazioni e scalabilità, nonché l’implementazione di meccanismi che
assicurino il maggior risparmio di banda possibile.

.. [1]
   Il contenuto di questo paragrafo è in linea con quanto prescritto
   dalle “Linee Guida sull’interoperabilità tecnica delle Pubbliche
   Amministrazioni” emanate da AgID, di cui al paragrafo 3.3 del
   documento citato (si rimanda alla sezione “Bibliografia e Sitografia
   di riferimento” a fine documento per link con redirect al documento)
