![Header](https://github.com/ScribbleLabApp/ScribbleLab/assets/129311622/eb1953ca-f14f-43ba-84d9-a50b7db93303)

## ScribbleLab for iOS, macOS and visionOS

ScribbleLab è un editor di testo rivoluzionario progettato esclusivamente per gli studenti, portando una fantastica user experience su piattaforme iOS, macOS e visionOS. Creato dagli studenti, per gli studenti, offre un editor leggero ma potente con un design visivamente accattivante e un'interfaccia utente intuitiva.

> [!NOTA]
> ScribbleLab è attualmente in fase di sviluppo e non è ancora pronto per l'uso in produzione. Se lo desideri, puoi provare la [versione alpha/dev build](https://github.com/ScribbleLabApp/ScribbleLab/releases/latest) a tuo rischio. Accogliamo volentieri feedback [qui](https://github.com/ScribbleLabApp/ScribbleLab/issues).

> [!ATTENZIONE]
> ScribbleLab non funziona come previsto su iOS 17.4 beta. Si prega di utilizzare Xcode 15.2 e iOS 17.3.1. Attualmente i nostri sviluppatori stanno indagando su questo problema.

### Translations
Questo README è disponibile in diverse lingue:
[Inglese](https://github.com/ScribbleLabApp/ScribbleLab/tree/main) · [Tedesco](https://github.com/ScribbleLabApp/docs/blob/main/translations/README~de.md) · [Italiano](https://github.com/ScribbleLabApp/docs/blob/main/translations/README~de.md) · [日本語 `(まだ利用できません)`]()

## Motivation
Noi di ScribbleLab abbiamo scoperto che gli attuali editor di testo presenti sul mercato erano troppo complicati, mancavano di funzionalità essenziali o erano difficili da personalizzare per le nostre specifiche esigenze.

Ci siamo chiesti: "Perché non esiste un'app che abbia tutto ciò di cui hai bisogno?"

Ecco perché abbiamo deciso di creare il nostro editor di testo, con il controllo completo sulla sua funzionalità e caratteristiche.

## Mission
La nostra missione a ScribbleLab è creare un'app che renda la vita quotidiana più semplice per gli studenti.

Gli studenti spesso hanno bisogno di utilizzare più app per organizzare la loro vita accademica. Tenendo conto dei flussi di lavoro degli studenti, combiniamo quattro app esistenti (Promemoria, Calendario, Timetable e Orologio) in due app con un design accattivante e un editor integrato in modo impeccabile: **ScribbleLab** e **ScribbleLink**

Ci sforziamo di rimanere fedeli alle [linee guida per l'interfaccia umana di Apple](https://developer.apple.com/design/human-interface-guidelines) e ai [modelli di design](https://developer.apple.com/design/human-interface-guidelines/patterns), garantendo che ScribbleLab abbia l'aspetto e la sensazione di un'applicazione sviluppata direttamente da Apple stessa, con una meticolosa attenzione ai dettagli.

## Features
Il nostro editor costituisce la parte "Scribble" di ScribbleLab, mentre le nostre funzionalità comprendono il "Lab".

ScribbleLab offre una suite completa di strumenti, tra cui:

- Collaborazioni in tempo reale (prossimamente)
- Archiviazione cloud collegata (Dropbox, Google Drive, iCloud Drive, ecc.)
- Modelli personalizzabili (pagine, copertine, ecc.)
- Importazione/esportazione di PDF, PNG e file .scribble (formato file personalizzato, prossimamente)
- Supporto AI (prossimamente)
- Integrazione con ScribbleLink

Le funzionalità sono facilmente accessibili dalla barra laterale, offrendo un'esperienza potente e allo stesso tempo intuitiva. La nostra selezione di funzionalità è guidata dai feedback della comunità e dei tester, garantendo rilevanza e utilità per gli studenti.

Molte delle nostre funzionalità sono disponibili dalla barra laterale dove possono essere accessibili con un semplice clic.

## Community
Per decidere quali funzionalità includere, invitiamo e valutiamo i feedback dalla nostra [community](https://discord.gg/7eyQFUws7A) e dai nostri tester, garantendo che l'elenco delle funzionalità sia rilevante e utile agli studenti.

La nostra comunità comprende collaboratori da GitHub, tester, sviluppatori e utenti. Unisciti al nostro [**server Discord**](https://discord.gg/7eyQFUws7A) per migliorare la comunicazione tra i membri della comunità.

## Privacy
È sicuro creare un account con ScribbleLab? Assolutamente sì!

Noi di ScribbleLab crediamo che la privacy sia un diritto fondamentale e debba essere trattata con la massima importanza. Quando si tratta di dati personali, è importante che vengano memorizzati in modo sicuro e responsabile. È cruciale che gli individui abbiano il controllo dei propri dati. Dovresti poter accedere, gestire ed eliminare facilmente e privatamente i tuoi dati. Questo è particolarmente importante nel contesto delle violazioni dei dati, dove le informazioni personali possono cadere nelle mani sbagliate.

Pertanto, memorizziamo i tuoi dati solo sul tuo dispositivo o sui tuoi account di archiviazione cloud di terze parti, garantendo che i dati non siano accessibili a individui o entità non autorizzati. Utilizziamo [Google Firebase](https://firebase.google.com/) (che include [FirebaseAuth](https://firebase.google.com/docs/auth?hl=en), [FirebaseStorage](https://firebase.google.com/docs/storage?hl=en), e [Cloud Firestore](https://firebase.google.com/docs/firestore?hl=en)) per memorizzare in modo sicuro i tuoi dati. Questo significa che nessuno può accedere ai tuoi dati personali, come documenti creati o servizi cloud, nemmeno noi. L'unica cosa che possiamo vedere è quante persone hanno un account ScribbleLab, insieme ai dati da [Google Analytics](https://developers.google.com/analytics?hl=en) e [Google Crashlytics](https://firebase.google.com/docs/crashlytics?hl=en) per tracciare crash e altri eventi o bug insoliti.

Garantire la sicurezza del nostro software è una priorità assoluta per noi. Rilasciamo regolarmente aggiornamenti software che includono correzioni di bug e patch di sicurezza per mantenere sicuri i tuoi dati e il sistema. È importante installare questi aggiornamenti non appena diventano disponibili per garantire di essere protetti dalle ultime minacce.

Per rendere più semplice il processo di aggiornamento del software, abbiamo implementato una funzione di aggiornamento automatico che ti chiederà di installare nuovi aggiornamenti non appena diventano disponibili. Ti consigliamo vivamente di abilitare questa funzione in modo che tu abbia sempre installati gli ultimi aggiornamenti di sicurezza.

Oltre agli aggiornamenti automatici, forniamo anche istruzioni manuali per l'aggiornamento su macOS sul nostro sito web. Assicurati di seguire attentamente queste istruzioni per garantire un processo di aggiornamento senza intoppi.

Ricorda, rimanere aggiornato con gli aggiornamenti software è una parte essenziale per mantenere la sicurezza e l'integrità del tuo sistema.

> [!ATTENZIONE]
> Non viene fornita alcuna garanzia per le versioni di test Alpha, Beta, nightly o RC. Utilizzale a tuo rischio e pericolo.

## Contributing
Fai parte della prossima rivoluzione nell'editing del codice contribuendo al progetto. Si tratta di un'iniziativa guidata dalla comunità, quindi diamo il benvenuto a quanti più contributori possibili che possono aiutare. Leggi la [guida per contribuire](https://github.com/ScribbleLabApp/ScribbleLab/blob/main/CONTRIBUTING.md) per ulteriori informazioni.

Questo progetto si estende su [diverse repository](https://github.com/ScribbleLabApp/ScribbleLab#related-repositories) quindi anziché navigare tra le "issue" nella scheda delle issue, potrebbe essere utile trovare un problema con cui iniziare nel nostro [project board](https://github.com/orgs/ScribbleLabApp/projects/1/views/1).

Per gli incarichi e/o le problematiche su cui vogliamo concentrarci attualmente, ti preghiamo di consultare [questa sezione]().

## License
Quando crei un account ScribbleLab, accetti il nostro [Contratto di Licenza](LICENSE_AGREEMENT.md) così come le licenze dei nostri pacchetti software di terze parti.

Questo progetto open-source è stato licenziato con due licenze separate. La Licenza Apache 2.0 si applica all'intero progetto, mentre la Licenza AGPL 3.0 si applica specificamente al codice e al servizio di autenticazione di ScribbleLab. La Licenza Apache 2.0 è una licenza permissiva che consente la distribuzione del software sotto determinate condizioni. D'altra parte, la Licenza AGPL 3.0 è una licenza copyleft che richiede che qualsiasi modifica o derivazione del codice venga rilasciata sotto la stessa licenza. È importante notare che le licenze non sono intercambiabili e il rispetto di entrambe è necessario per un corretto utilizzo e distribuzione del progetto.

[ScribbleLab's main LICENSE](LICENSE) · [ScribbleLab's Auth LICENSE](LICENSE-AUTH)

## Support Us
Il tuo supporto è prezioso per noi e ci aiuta a dedicare più tempo a migliorare e mantenere questo repository. Ecco come puoi contribuire:

**⭐️ Lascia una stella:** Se trovi questo repository utile o interessante, considera di lasciare una stella su GitHub. Le tue stelle ci aiutano a ottenere visibilità e incoraggiano altri membri della comunità a scoprire e beneficiare di questo lavoro.

**📲 Condividi con gli amici:** Se ti piace l'idea dietro a questo progetto, condividilo con i tuoi amici, colleghi o chiunque possa trovarlo utile.

## Related Repositories

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/ScribbleLabApp/ScribbleLink">
        <img src="ScribbleLab/Ressources/Assets.xcassets/Logos/Documentation.imageset/ScribbleLab.png" height="128">
        <p>&nbsp;&nbsp;&nbsp;&nbsp;ScribbleLink&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p>
      </a>
    </td>
  <!---->
  <td align="center">
      <a href="https://github.com/ScribbleLabApp/ScribbleCompose">
        <img src="ScribbleLab/Ressources/Assets.xcassets/Logos/Documentation.imageset/ScribbleLab.png" height="128">
        <p>&nbsp;&nbsp;&nbsp;&nbsp;ScribbleCompose&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p>
      </a>
    </td>
  <!---->
  <td align="center">
      <a href="https://github.com/ScribbleLabApp/AvatarKit">
        <img src="https://github.com/ScribbleLabApp/ScribbleLab/assets/129311622/965258c0-6947-4742-ba4e-90523a808df1" width="128" height="128">
        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AvatarKit&nbsp;&nbsp;&nbsp;&nbsp;</p>
      </a>
    </td>
  </tr>
</table>

