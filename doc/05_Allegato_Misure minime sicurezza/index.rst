Allegato 5: Misure minime di sicurezza
######################################

Obblighi del Gestore
====================
Ferma restando la necessaria predisposizione di ogni misura tecnica e 
organizzativa adeguata a garantire un livello di sicurezza adeguato al 
rischio, ai sensi dell’art. 32 GDPR e nel rispetto del principio di 
responsabilizzazione, il Gestore e i Soggetti erogatori DEVONO 
implementare almeno le misure indicate nel presente Allegato.

Il Gestore DEVE provvedere al monitoraggio dell’infrastruttura del Punto 
di accesso telematico attraverso l’implementazione di:

- Firewall;
- sistema di DDoS Protection;
- Web Application Firewall, Intrusion Prevention / Detection System.

La gestione degli accessi all’infrastruttura DEVE avvenire attraverso 
l’implementazione almeno delle seguenti misure:

- l’accesso all’infrastruttura del Punto di accesso telematico  da 
  parte di soggetti con privilegi di amministratore prevede 
  un’autenticazione a due fattori con rilascio di token; 
- l’accesso al Portale prevede un’autenticazione a due fattori con 
  invio di SMS o chiamata a numero di telefonia mobile.

Le chiamate dei Soggetti erogatori relativamente ai Servizi in rete 
realizzati per il tramite del Punto di accesso telematico avvengono, 
nel rispetto delle indicazioni presenti nelle dalle [LG INTEROP TEC] 
e [LG SICUREZZA], attraverso l’implementazione almeno delle seguenti 
misure:

- generazione dei token di autorizzazione necessarie per autenticare 
  le chiamate API;
- restrizione su base IP sorgente, qualora tecnicamente applicabile;
- mutual TLS (mTLS) authentication  tra l’infrastruttura del Punto di 
  accesso telematico e  i sistemi dei Soggetti erogatori.

Gli eventi elencati di seguito, che si svolgono sull’infrastruttura, 
vengono registrati e conservati in appositi log, gestiti dal Gestore 
nel rispetto della normativa in materia di trattamento di dati 
personali:

- richieste per tracciamento (debug e incident response verso i 
  Soggetti erogatori);
- richieste di autenticazione mediante SPID (come prescritto dal 
  DPCM 24 ottobre 2014) e CIE;
- accessi degli amministratori di sistema (come prescritto dal 
  Provvedimento dell’Autorità Garante per la protezione dei dati 
  personali del 27 novembre 2008). 

Il Gestore DEVE effettuare periodicamente l’analisi dei rischi, nel 
rispetto dello standard internazionale ISO 27005. Al fine di garantire 
una più efficace gestione del rischio, il Gestore DEVE valutare 
periodicamente le necessarie implementazioni per l’adeguamento 
dell’infrastruttura ai requisiti della certificazione prevista dallo 
standard internazionale ISO/IEC 27001:2017.

Il Gestore DEVE  sottoporre periodicamente la piattaforma a procedure 
di vulnerability assessment e penetration test, svolte anche da soggetti 
terzi, assicurando l’individuazione proattiva di eventuali problematiche 
di sicurezza e vulnerabilità e le implementazioni di sviluppo necessarie 
per la loro mitigazione in base al livello di severità, effettuate 
periodicamente anche tramite:

- Mobile Application Penetration Test, con simulazione dei possibili 
  scenari di attacco a un’applicazione mobile;
- Secure Code Review (SCR) del Punto di accesso telematico;
- API Security Assessment delle API esposte dal Punto di accesso 
  telematico.

Obblighi del Soggetto erogatore
===============================
Il Soggetto erogatore DEVE  implementare  almeno le seguenti misure di 
sicurezza:

- gestione e tracciatura degli accessi, con una profondità storica tale 
  da consentire la raccolta e l’analisi di informazioni relative a 
  incidenti e malfunzionamenti anche per finalità diagnostiche; le 
  informazioni così raccolte devono essere leggibili e conservate al 
  fine di essere rese disponibili al Gestore e alle Autorità di 
  controllo, ove richiesto;
- implementazione di sistemi adeguati di controllo, disaccoppiamento e 
- filtraggio tipici dei servizi esposti su rete pubblica; 
- configurazioni di sicurezza di sistema avanzate, da adottare sui 
- sistemi che ospitano le applicazioni web;
- verifica periodica dei livelli di sicurezza comprese le attività di 
- analisi dei rischi, vulnerability assessment e penetration testing.

Le misure di sicurezza e le specifiche tecniche sono adottate in 
ossequio alla normativa in tema di protezione dei dati personali, 
in conformità alle [LG SICUREZZA], alle best practice del settore e 
alle specifiche impartite dal Gestore nella documentazione correlata 
al rapporto di adesione.

Il Gestore e i Soggetti erogatori DEVONO vigilare sull’adeguatezza 
delle misure e delle specifiche tecniche e procedere alle 
implementazioni necessarie a mantenere livelli di sicurezza adeguati, 
nel rispetto del principio di responsabilizzazione di cui all’art. 5, 
par. 2 GDPR.


.. forum_italia::
  :topic_id: 22254
  :scope: document

