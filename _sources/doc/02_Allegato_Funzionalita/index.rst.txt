Allegato 2: Funzionalità del Punto di accesso telematico
#########################################################

Identificazione degli utenti finali
===================================
L’accesso dell’utente finale all’interno al Punto di accesso telematico 
DEVE avvenire tramite gli strumenti previsti all’articolo 64 del CAD. 
A tal fine, il Gestore aderisce alla federazione SPID in qualità di 
aggregatore della Presidenza del Consiglio dei Ministri, previa stipula 
di apposita convenzione con AgID e aderisce al sistema CIE secondo la 
procedura determinata dal Ministero dell’Interno. 

Una volta effettuata l’autenticazione dell’utente finale tramite gli 
strumenti previsti all’articolo 64 del CAD, il Gestore PUÒ prevedere 
la creazione di una sessione utente, con un time to live massimo di 
30 giorni, accessibile tramite codice o altri metodi di identificazione 
offerti dal dispositivo stesso, in linea con l’evoluzione tecnologica 
e gli standard di settore (es. riconoscimento impronta digitale), nel 
rispetto della normativa sul trattamento dei dati personali. 

Messaggi
========
La funzione “messaggi” consente all’utente di ricevere le comunicazioni 
a lui indirizzate da parte dei Soggetti erogatori che utilizzano le API 
messe a disposizione dal Gestore.

Il Gestore permette all’utente di ordinare e/o filtrare i messaggi 
ricevuti sulla base di distinti parametri, quali, ad esempio, la data 
di invio del messaggio, l’identificativo del servizio mittente del 
messaggio, l’oggetto indicato nel messaggio, etc. 

L’utente, se lo desidera, potrà attivare ulteriori funzionalità collegate, 
quali la possibilità di gestire le preferenze di recapito per uno 
specifico servizio, condividere con terzi il messaggio, ricevere avvisi 
in merito alla scadenza legata al messaggio (nel caso, per esempio, di 
avvisi di pagamento), etc.

Il Gestore DEVE consentire ai Soggetti erogatori di  interrogare un 
servizio per sapere se uno specifico utente ha lo stesso attivo sul 
Punto di accesso telematico e se ha espresso delle preferenze (per 
esempio nel caso in cui il cittadino non voglia più ricevere messaggi 
dall'ente).

I messaggi possono contenere delle call to action volte, ad esempio, 
a inserire un “Promemoria” nel proprio calendario personale o un tasto 
“Paga” per facilitare l’avvio di un flusso di pagamento. Le Call to 
Action nei messaggi possono inoltre essere personalizzate dal Soggetto 
erogatore (es. “Visualizza”, “Richiedi”, “Iscrivi”, etc) e dare inizio 
a specifici flussi o azioni dispositive integrate nell’esperienza 
dell’utente all’interno del Punto di accesso telematico tramite 
single-sign-on verso i servizi gestiti dal Soggetto erogatore e vista 
in webview dei passaggi necessari al completamento dell’azione. 

Portafoglio
===========
La sezione “portafoglio”, integrata con il la piattaforma di cui 
all’art. 5, comma 2 del CAD (“**Piattaforma PagoPA**”), consente 
all’utente di pagare un Soggetto erogatore, di salvare e gestire i 
propri metodi di pagamento e di avere a disposizione la lista delle 
transazioni eseguite.

Le funzioni di pagamento consentono di eseguire le transazioni economiche 
all’interno di IO, rimanendo nello stesso ambiente e utilizzando i 
metodi di pagamento già inseriti, portando al completamento 
dell’operazione in pochi passaggi.

Tutti i dati relativi ai metodi di pagamento e alle transazioni e 
operazioni di pagamento effettuate vengono mantenuti all'interno 
della Piattaforma PagoPA, in ambiente PSI.

Nell’ambito della funzione “portafoglio”, il Gestore PUÒ inoltre 
rendere disponibili servizi specifici legati a bonus e agevolazioni che 
permettono all’utente finale di gestire tramite il Punto di accesso 
telematico sia azioni di pagamento che la ricezione di crediti o 
l’utilizzo di sistemi di bonus per il pagamento verso terzi. 

Servizi
=======
La funzione “servizi” permette all’utente finale di verificare in ogni 
momento quali sono i servizi disponibili all’interno del Punto di accesso 
telematico e approfondire i dettagli per ciascun servizio. 

Ogni servizio è descritto in modo completo, in modo che l’utente sappia 
cosa aspettarsi da quello specifico servizio all’interno del Punto di 
accesso telematico. Per la descrizione, il Soggetto  erogatore indica 
per ciascun servizio: il logo, la descrizione dell’offerta di servizi 
disponibile tramite il Punto di accesso telematico e una serie di 
metadati necessari per individuare maggiori approfondimenti o mettersi 
in contatto con il Soggetto erogatore in caso di necessità (la URL 
dell’informativa privacy, la URL dei termini di servizio, indirizzo 
fisico, email, eventuale numero di telefono, eventuali altri canali 
di supporto, etc.). 

L’utente può inoltre decidere se attivare o disattivare ciascun servizioe 
gestire le preferenze in termini di invio di notifiche push e forward 
del messaggio sulla propria mail. In particolare:

- l'abilitazione della preferenza inbox per il servizio mittente, 
  genera l'archiviazione del messaggio nella casella del cittadino e 
  la visualizzazione del messaggio nella schermata “Messaggi” 
  dell’app IO;
- l'abilitazione della preferenza di ricezione via e-mail per il 
  servizio mittente determina l’invio del contenuto del messaggio via 
  e-mail verso l'indirizzo di posta elettronica indicato dall’utente;
- l'abilitazione della preferenza di notifica push per il servizio 
  mittente determina l’invio di un messaggio di notifica push sullo 
  smartphone su cui è installata l'app IO.

Il Gestore DEVE assicurare che all’utente venga fornita la possibilità 
di attivare i servizi di cui intende usufruire attraverso il Punto di 
accesso telematico e gestire le relative preferenze.

Profilo
=======
La sezione “profilo” consente all’utente di consultare un riepilogo 
delle proprie informazioni rilevanti sul Punto di accesso telematico e 
di impostare alcune scelte di carattere generale che risultano 
trasversali all’erogazione dei Servizi e che verranno usate per 
personalizzare il servizio erogato all’utente da parte del Gestore e 
dei Soggetti erogatori. Alcune di queste scelte, una volta effettuate 
dall’utente, potranno essere interrogate e utilizzate in tempo reale 
dai Soggetti erogatori.

Di seguito, si riportano a titolo di esempio alcune preferenze che 
potranno essere definite dell’utente:

- lingua preferita;
- e-mail personale dell’utente.

L’e-mail di default è quella legata agli attributi SPID o, nel caso di 
login con CIE, inserita dall’utente in fase di login. L’eventuale 
aggiornamento dei dati anagrafici nel Punto di accesso telematico non 
verrà comunicato agli Identity Provider SPID e avrà effetto solo 
all'interno del Punto di accesso telematico e dei servizi offerti dai 
Soggetti erogatori.

Con la stessa funzione “profilo” l’utente può gestire eventuali strumenti 
complementari di identificazione e sicurezza quali PIN o, se abilitati 
dall’utente sul proprio dispositivo, strumenti di identificazione 
biometrica.

L'utente potrà inoltre visualizzare uno storico degli accessi e interrompere 
la sessione attualmente attiva sull’applicazione (logout).

Infine, con la funzione “profilo” l’utente potrà:

- verificare i termini e condizioni d’uso del servizio in vigore;
- consultare le informative sul trattamento dei dati personali dei 
  Soggetti erogatori e l'informativa relativa al Punto di accesso 
  telematico resa dal Gestore;
- chiedere la sospensione dell’account o la cancellazione dello stesso.

.. forum_italia::
  :topic_id: 23489
  :scope: document
