Punto di accesso telematico
============================

Il Punto di accesso telematico DEVE permettere l’erogazione di Servizi 
in rete verso gli utenti finali in un’ottica di progressiva multicanalità, 
nel rispetto del principio mobile first. 

Il punto unico di accesso telematico si compone delle seguenti 
componenti architetturali:

1. uno o più front-end dedicato alla fruizione dei servizi da parte degli utenti finali
2.	un back office dedicato ai Soggetti Erogatori
3.	sistemi back-end che comunicano con i front-end e il back office menzionati e con terze parti di cui integra i servizi

Il domain model del Punto di accesso telematico è descritta 
all’allegato 4.

Front-end per gli utenti finali
-------------------------------
Il Punto di accesso telematico si compone di un front-end multicanale; 
esso DEVE almeno includere una applicazione per dispositivi mobili e 
tablet (“**App IO”**) e DOVREBBE includere una versione web.

Il front-end a sua volta interagisce con il back-end che, tramite 
interfacce applicative (API) conformi alle [LG INTEROP TEC], abilita 
la possibilità di usufruire dei Servizi erogati tramite il Punto di 
accesso telematico.

L’utilizzo del front-end da parte dell’utente finale richiede 
un’autenticazione forte, ai sensi della normativa applicabile, favorendo 
il massimo livello di sicurezza e il pieno rispetto della privacy.

Successivamente all’autenticazione, l’utente finale PUÒ ricevere 
informazioni e effettuare operazioni per tramite del back-end con i 
dati provenienti dai sistemi dei Soggetti erogatori. 

L’insieme di funzionalità rese disponibile dai front-end sono indicate 
nell’allegato 2 e le stesse sono implementate nei limiti delle tecnologie 
del singolo canale.

Back-end del Punto di accesso telematico
----------------------------------------
Il back-end abilita il front-end all’erogazione dell’esperienza di 
utilizzo personalizzata dell’utente finale identificato in maniera 
univoca.

Il back-end ricopre inoltre il ruolo di piattaforma abilitante verso i 
Soggetti erogatori, permettendo l’integrazione con i Moduli del Punto 
di accesso telematico attraverso API, conformi alle [LG INTEROP TEC] e 
[LG SICUREZZA], i Soggetti erogatori POSSONO ricevere le richieste degli 
utenti finali e inviare comunicazioni ai cittadini che utilizzano il 
Punto di accesso telematico.

La riservatezza dei contenuti dei Messaggi scambiati tra i sistemi dei 
Soggetti erogatori e i front-end che transitano per la back-end è 
assicurata dall’applicazione di tecniche di crittografia asimmetrica. 
In tale contesto il back-end DOVREBBE assicurare il deployment delle 
chiavi pubbliche generate per client (il singolo front-end istanziato 
dall’utente finale) ai sistemi dei Soggetti erogatori. 

Il Punto di accesso telematico, nelle transazioni con i Sistemi 
dell’Ente, assicura  decorazione dei messaggi con un identificativo 
univoco dello stesso. 

Back office dei Soggetti erogatori
----------------------------------
Il back office dei Soggetti erogatori (di seguito “Portale”) è l’insieme 
dei sistemi e delle componenti tecnologiche sviluppate e gestite dal 
Gestore per: 

- la registrazione dei Soggetti erogatori al Punto di accesso 
  telematico;
- l’utilizzo da parte dei Soggetti erogatori dei servizi e interfacce 
  messi a disposizione dal Punto di accesso telematico; 
- l’integrazione tecnologica dei sistemi dei Soggetti erogatori con il 
  Punto di accesso telematico per il tramite delle API individuate dal 
  Gestore; 
- la fornitura di reportistica e analisi del servizio reso dal Gestore 
  per implementare i Servizi in rete per il tramite del Punto di 
  accesso telematico;  
- ogni altro servizio che il Gestore rende disponibile ai Soggetti 
  erogatori.

Repertorio dei Servizi in rete fruibili dal del Punto di accesso telematico
---------------------------------------------------------------------------
Il Gestore DOVREBBE rende disponibile un repertorio dei Servizi in rete 
disponibili tramite il Punto di accesso telematico e ne cura 
l’aggiornamento. 

I Soggetti erogatori DEVONO identificare ciascun Servizio di rete 
all’interno del Punto di accesso telematico almeno attraverso i seguenti 
elementi, secondo i formati indicati nelle specifiche per 
l’identificazione del servizio predisposte dal Gestore:

- identificativo univoco;
- nome: un nome chiaro e riconoscibile per ciascun Servizio, 
  corrispondente a quello impiegato dal Soggetto erogatore negli altri 
  canali a sua disposizione;
- descrizione: descrizione sintetica e chiara del Servizio stesso, con 
  indicazione puntuale delle esigenze collettive che è in grado di 
  assolvere; 
- area territoriale: area geografica (locale o nazionale) cui si 
  riferisce il Servizio del Soggetto erogatore, al fine di permettere 
  all’utente di selezionare le aree di proprio interesse;
- identificazione del Soggetto erogatore: esposizione del nome e del 
  logo ufficiale del soggetto che lo eroga;
- link alla documentazione applicabile: ciascun Soggetto erogatore deve 
  esporre, in forma testuale o ipertestuale, secondo le specifiche 
  tecniche trasmesse e in ossequio alla specifica documentazione di 
  prodotto trasmessa dal Gestore, la documentazione che regola il 
  rapporto tra il Soggetto erogatore e il cittadino, compresa la 
  documentazione relativa al trattamento dei dati personali del 
  cittadino da parte del Soggetto erogatore;
- contatti: canali e i recapiti di contatto del Soggetto erogatore e 
  degli uffici competenti che l’utente finale può utilizzare per 
  contattare il Soggetto erogatore o può altrimenti fruire del Servizio. 
  Il Soggetto erogatore valuta, di concerto con il Gestore, l’esposizione 
  di un contatto amministrativo e di un contatto tecnico.

Integrazione del Punto di accesso telematico con le piattaforme previste dal CAD e normative specifiche
--------------------------------------------------------------------------------------------------------
In coerenza con il Piano triennale per l’informatica nella Pubblica 
Amministrazione ed, in generale, il modello strategico di riferimento 
dell’informatica nella PA, il Punto di accesso telematico DEVE 
assicurare l’integrazione con le piattaforme tecnologiche che offrono 
funzionalità fondamentali, trasversali, abilitanti e riusabili nella 
digitalizzazione dei processi e dei servizi della PA. 

Il Gestore e i soggetti titolari delle singole piattaforme DEVONO 
assicurare l’interoperabilità del Punto di accesso telematico con le 
piattaforme di cui all’allegato 3. A tal fine, i soggetti di cui 
all'articolo 2, comma 2, i fornitori di identità digitali e i prestatori 
dei servizi fiduciari qualificati DEVONO esporre le API in ottemperanza 
al comma 1-bis dell’articolo 50-ter del CAD. 

L’integrazione DOVREBBERO essere realizzata nel rispetto del modello 
di interoperabilità delle Pubbliche Amministrazioni (in breve ModI) e, 
nello specifico, delle [LG INTEROP TEC]. 

Il Punto di accesso telematico esegue la tracciatura delle transazioni 
con le piattaforme di cui all’allegato 3 registrando per le singole 
interazioni realizzate:

- la data e l’ora della transazione;
- l’identificativo univoco assegnato dal Punto di accesso telematico 
  alla transazione;
- la request effettuata dal Punto di accesso telematico alla piattaforma 
  della Pubblica Amministrazione.

I soggetti di cui all'articolo 2, comma 2, i fornitori di identità 
digitali e i prestatori dei servizi fiduciari qualificati definiscono 
i livelli di qualità dei servizi resi disponibili al Punto di accesso 
telematico in accordo con il Gestore e assicurano il rispetto degli 
stessi. I livelli di qualità sono definiti a partire dagli indicatori 
di qualità indicati al successivo paragrafo 7.4 Indicatori di qualità.

Funzionalità del Punto di accesso telematico
--------------------------------------------
Il Punto di accesso telematico DEVE assicurare le funzionalità previste 
all’allegato 2. 

Il Gestore PUÒ implementare funzionalità aggiuntive nelle more 
dell'aggiornamento dell’allegato 2. Le funzionalità implementate in 
maniera aggiuntiva dal Gestore sono semestralmente motivate e comunicate 
ad AgID che, a valle delle verifiche di merito, valuta l'aggiornamento 
dell’allegato 2.

.. forum_italia::
   :topic_id: 23485
   :scope: document
