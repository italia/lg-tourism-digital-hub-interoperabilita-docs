**3.4 Service Level Agreement (SLA)**\  [1]_
============================================

L’integrazione può coinvolgere numerosi aderenti al TDH che espongono le
proprie API. Al fine di allinearsi sulla QoS, gli erogatori e i fruitori
di API utilizzano quelli che vengono definiti Service Level Agreement
(SLA), ovvero accordi sul livello di servizio. Uno SLA è costituito dai
seguenti elementi:

+-----------------------------------+-----------------------------------+
| **Scopo**                         | Ragioni che hanno portato alla    |
|                                   | definizione dello SLA;            |
+-----------------------------------+-----------------------------------+
| **Parti**                         | Soggetti interessati e rispettivi |
|                                   | ruoli (es. erogatore e fruitore   |
|                                   | API);                             |
+-----------------------------------+-----------------------------------+
| **Periodo di validità**           | Intervallo di tempo, espresso     |
|                                   | mediante data e ora di inizio,    |
|                                   | data e ora di fine, per il quale  |
|                                   | si ritiene valido un particolare  |
|                                   | termine di accordo all’interno    |
|                                   | degli SLA;                        |
+-----------------------------------+-----------------------------------+
| **Perimetro**                     | Operazioni interessate dallo      |
|                                   | specifico SLA;                    |
+-----------------------------------+-----------------------------------+
| **Service Level Objectives        | I singoli termini di accordo      |
| (SLO),** ovvero **obiettivi sul   | all’interno di uno SLA. Di        |
| livello di servizio**             | solito, sono definiti utilizzando |
|                                   | dei Service Level Indicators      |
|                                   | (SLI), ovvero indicatori sul      |
|                                   | livello di servizio, che          |
|                                   | quantificano i singoli aspetti di |
|                                   | QoS (ad es. la disponibilità);    |
+-----------------------------------+-----------------------------------+
| **Penalità**                      | Sanzioni che si applicano nel     |
|                                   | caso in cui l’erogatore           |
|                                   | dell’interfaccia di servizio non  |
|                                   | dovesse assicurare gli obiettivi  |
|                                   | specificati in SLA;               |
+-----------------------------------+-----------------------------------+
| **Esclusioni**                    | Aspetti della QoS non coperti     |
|                                   | dagli SLA;                        |
+-----------------------------------+-----------------------------------+
| **Amministrazione**               | Processi mediante i quali le      |
|                                   | parti possono monitorare la QoS.  |
+-----------------------------------+-----------------------------------+

Gli SLA possono essere statici o dinamici. Negli SLA dinamici, gli SLO
(con associati SLI) variano nel tempo e i periodi di validità
definiscono gli intervalli di validità di questi ultimi (ad es. in
orario lavorativo gli SLO possono essere differenti da quelli imposti
durante la notte). La misurazione dei livelli di QoS all’interno di uno
SLA richiede il tracciamento delle operazioni effettuate in un contesto
infrastrutturale multi-dominio (geografico, tecnologico e applicativo).

.. [1]
   Il contenuto di questo paragrafo è in linea con quanto prescritto
   dalle “Linee Guida sull’interoperabilità tecnica delle Pubbliche
   Amministrazioni” edite da AgID, di cui al paragrafo 3.4 del documento
   citato (si rimanda alla sezione “Bibliografia e Sitografia di
   riferimento” a fine documento per link con redirect al documento)
