# Pawse
Pawse è un'app che monitora il comportamento dell'utente sui social e utilizza l'AI per riconoscere lo scrolling passivo. Un cane virtuale reagisce alle abitudini dell'utente, motivandolo a ridurre l'uso e a fare pause attraverso un legame emotivo.


Priorità con metodo MoSCoW:
M = Must (indispensabile)
S = Should (importante)
C = Could (facoltativa)


1. REQUISITI FUNZIONALI:

	A - ACCOUNT E ONBOARDING
		- RF1 Come utente, voglio adottare un cucciolo scegliendo razza, colore e nome, in modo da creare un legame personale con lui.
      		Priorità: M
		- RF2 Come utente, voglio impostare un limite giornaliero di utilizzo, in modo da avere un obiettivo chiaro da rispettare.
      		Priorità: M
		- RF3 Come utente, voglio scegliere quali app social monitorare tra quelle installate, in modo da controllare solo ciò che mi interessa.
      		Priorità: M
		- RF4 Come utente, voglio impostare obiettivi personali (es. "niente TikTok dopo mezzanotte"), in modo da personalizzare il mio percorso.
      		Priorità: S
		- RF5 Come utente, voglio concedere i permessi con una spiegazione trasparente, in modo da sapere cosa l'app può e non può vedere.
      		Priorità: M
		- RF6 Come utente, voglio fare il "patto con il cucciolo", in modo da sentirmi coinvolto emotivamente fin dall'inizio.
      		Priorità: C
		- RF7 Come utente, voglio registrarmi, accedere e modificare il mio profilo, in modo da poter usare amici e classifiche.
      		Priorità: M

	B - MONITORAGGIO DEI SOCIAL
		- RF8 Come utente, voglio vedere il tempo trascorso sulle app scelte, in modo da capire quanto le uso davvero.
      		Priorità: M
		- RF9 Come utente, voglio vedere il numero di aperture, in modo da accorgermi di quanto spesso le riapro.
      		Priorità: M
		- RF10 Come utente, voglio vedere il numero di sessioni e di scroll, in modo da avere un quadro completo del mio uso.
       		Priorità: M
		- RF11 Come utente, voglio analizzare velocità e durata dello scrolling, in modo da capire quando divento più compulsivo.
       		Priorità: S
		- RF12 Come utente, voglio vedere le mie sessioni più lunghe e ripetitive, in modo da individuare i momenti critici.
       		Priorità: S
		- RF13 Come utente, voglio vedere il comportamento "apro → scrollo → chiudo → riapro", in modo da riconoscere il loop.
       		Priorità: S
		- RF14 Come utente, voglio vedere quanti chilometri ho percorso con il pollice, con paragoni comprensibili, in modo da rendere tangibile il mio scrolling.
       		Priorità: S
		- RF15 Come utente, voglio vedere gli orari di maggiore utilizzo, in modo da scoprire quando sono più a rischio.
       		Priorità: S

	C - INTELLIGENZA ARTIFICIALE
		- RF16 Come utente, voglio attivare l'analisi AI che distingue uso attivo da scrolling passivo, con eventuale notifica,
       		in modo da non essere penalizzato quando rispondo a un amico.
       		Priorità: M
		- RF17 Come utente, voglio ricevere a fine giornata un resoconto scritto dall'AI (Pawse Report), in modo da capire com'è andata la giornata.
       		Priorità: M
		- RF18 Come utente, voglio che il report includa i momenti positivi e un suggerimento per domani,
       		in modo da sentirmi incoraggiato e non giudicato.
       		Priorità: S
		- RF19 Come utente, voglio che l'AI riconosca le mie abitudini dopo alcuni giorni, in modo da scoprire pattern che non noto da solo.
       		Priorità: S
		- RF20 Come utente, voglio che l'AI confronti ogni giorno il mio comportamento con i miei obiettivi, in modo da sapere se sto migliorando.
       		Priorità: S

	D - IL CUCCIOLO
		- RF21 Come utente, voglio che il cane reagisca al mio uso dei social, in modo da vedere subito le conseguenze del mio comportamento.
       		Priorità: M
		- RF22 Come utente, voglio guadagnare ossi con un uso consapevole per dargli da mangiare, in modo da essere motivato a rispettare i limiti.
       		Priorità: M
		- RF23 Come utente, voglio vedere gli stati del cane (affetto, umore, energia, cura), in modo da capire come sta.
       		Priorità: M
		- RF24 Come utente, voglio ricevere notifiche dal cane in prima persona e mai aggressive, in modo da essere richiamato con dolcezza.
       		Priorità: S
		- RF25 Come utente, voglio essere avvisato progressivamente (giorni 3, 5, 7) prima che il cane se ne vada, in modo da avere il tempo di cambiare abitudini.
      		 Priorità: S
		- RF26 Come utente, voglio adottare un nuovo cucciolo o riconquistare quello perso, in modo da poter ricominciare dopo un abbandono.
       		Priorità: S

	E - INTERVENTI E BLOCCHI
		- RF27 Come utente, voglio che l'app interrompa lo scrolling quando rileva un loop
      		e mi chieda [Continua] / [Esci], in modo da fare una scelta consapevole.
       		Priorità: M
		- RF28 Come utente, voglio guadagnare punti affetto quando scelgo "Esci", in modo da essere premiato per aver smesso.
       		Priorità: S
		- RF29 Come utente, voglio bloccare solo sezioni specifiche delle app
       		(Shorts, Reels, feed), in modo da continuare a usare le parti utili.
       		Priorità: S
		- RF30 Come utente, voglio impostare orari personalizzati per i blocchi, in modo da adattarli alla mia routine.
       		Priorità: C

	F - CONFRONTO E SOCIAL
		- RF31 Come utente, voglio confrontare i miei report con la media degli utenti, in modo da capire dove mi colloco.
       		Priorità: C
		- RF32 Come utente, voglio confrontare i miei report con quelli dei miei amici, in modo da motivarmi insieme a loro.
       		Priorità: C
		- RF33 Come utente, voglio lanciare sfide e vedere una classifica con gli amici, in modo da rendere il miglioramento un gioco.
       		Priorità: C


2. REQUISITI NON FUNZIONALI:

		- RNF1 Usabilità: interfaccia semplice, tono dolce e mai giudicante.
		- RNF2 Prestazioni: schermate caricate in meno di 2 secondi.
		- RNF3 Basso consumo: il monitoraggio in background non deve scaricare la batteria  né rallentare il telefono. È fondamentale, perché l'app gira sempre.
		- RNF4 Sicurezza: dati protetti e cifrati, in locale e in trasmissione.
		- RNF5 Privacy by design: elaborazione locale quando possibile e all'AI solo metriche aggregate.
		- RNF6 Affidabilità: il servizio di monitoraggio deve restare attivo anche se il sistema chiude le app in background.
		- RNF7 Disponibilità: server per confronti, classifiche e amici attivi 24/7.
		- RNF8 Scalabilità: supportare la crescita degli utenti, ad esempio 10.000 contemporanei.
		- RNF9 Compatibilità: prima fase su Android, iOS in una seconda fase con funzioni ridotte.
		- RNF10 Reattività: gli interventi in tempo reale (es. i 45 swipe in 2 minuti) devono scattare quasi subito.
		- RNF11 Accuratezza: la distanza in km è una stima, e l'app deve dirlo chiaramente.
		- RNF12 Accessibilità: testi leggibili e contrasti adeguati.
		- RNF13 Manutenibilità: aggiungere facilmente nuove razze, accessori e app monitorabili.
   

4. REQUISITI DI DOMINIO:

		- RD1 GDPR: i dati comportamentali sono dati personali. Servono consenso esplicito, minimizzazione, e diritto di accesso, esportazione e cancellazione.
		- RD2 Nessun contenuto raccolto: mai screenshot, video o messaggi. Si analizza solo come si scrolla, non cosa si guarda.
		- RD3 Policy Google Play sui servizi di accessibilità: l'uso di questi permessi va dichiarato e spiegato con una schermata chiara all'utente, altrimenti l'app può essere rifiutata.
		- RD4 Tutela dei minori: probabile pubblico giovane, quindi serve un'età minima o il consenso dei genitori.
		- RD5 Nessuna promessa medica: Pawse aiuta a usare meglio i social, non cura la dipendenza. Va scritto nei termini d'uso.
		- RD6 Etica del design: niente senso di colpa aggressivo o dark pattern. L'app può interrompere lo scroll ma non deve bloccare con la forza.
		- RD7 Regola uso attivo/passivo: solo lo scrolling passivo e lo sforamento del limite penalizzano il cane. Rispondere a un amico non costa nulla.
		- RD8 Regola di abbandono: il cane se ne va dopo 8 giorni di sforamento o uso intensivo. Un giorno sano fa risalire parzialmente la fiducia.
		- RD9 Regola del cibo: gli ossi si guadagnano solo restando nei limiti.
