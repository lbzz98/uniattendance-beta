# UniAttendance — beta macOS e Windows

Calendario, syllabus, materiali e presenze UniCamillus. **Versione Mac: 3.0.2 beta; Windows: 2.3.6 beta**. Serve una licenza per il proprio dispositivo, rilasciata dall’organizzatore della beta.

## Aggiornamento 21 ottobre 2026

- **Mac 3.0.2:** calcolo delle presenze più rapido; aggiornamento strutturato di Anatomic Pathology II e lettura delle email nei syllabus corretti. Regole di frequenza e dati personali invariati.
- **iPhone/iPad 0.4.6:** scorri le intestazioni del calendario per passare al giorno o alla settimana precedente/successiva. La barra segue il dito con paginazione e decelerazione native; in Giorno compare il nome completo del giorno.
- **English:** faster Mac attendance calculations and corrected syllabus parsing; native iOS calendar-header paging and full weekday names. Windows is unchanged.

## Sei anni, coorti e gruppi

- Tutti i sei anni di **Medicine and Surgery in inglese a Roma, 2026/27**. La coorte segue l’anno di immatricolazione: 2026/27 per il primo anno, fino a 2021/22 per il sesto.
- Al primo avvio scegli anno e poi gruppo; puoi cambiarli nelle impostazioni. Terzo anno: gruppo unico. Altri anni: A/B.
- Calendari, cronologie e anomalie separati per anno; dati precedenti del quarto anno conservati. Materiali Online offre il filtro del tuo anno.
- **19 syllabus ufficiali offline**, controllati nelle pagine italiana e inglese della coorte corretta. Scientific English: 6 CFU dal PDF italiano coerente con 2+3+1; Laboratory Medicine conserva l’anomalia ufficiale 7 contro 8. Neurological Sciences usa provvisoriamente il syllabus ufficiale 2025/26 della coorte precedente (6 CFU, 4+1+1), con provenienza esplicita: la ricerca del documento attuale rimane attiva all’apertura e ogni ora.
- Le celle senza gruppo sono temporaneamente mostrate ad A e B, con nota nei dettagli. La vecchia lezione del 15 ottobre 2025 nel PDF del secondo anno è esclusa dal 2026/27 e segnalata nelle Anomalie.

**English:** Mac 3.0.2 and iPhone/iPad 0.4.6 support all six Rome English Medicine years for 2026/27, with the correct enrolment cohorts, year/group selection and separate calendars/history. Existing fourth-year data is retained. Nineteen current official syllabi and one explicitly labeled previous-cohort Neurological Sciences reference are available offline; current-cohort pages remain checked on launch and hourly. The third year has one group; other years have A/B. The iOS personal development build is installed separately through Xcode. **Windows remains 2.3.6, with its existing fourth-year functionality.**

I sottogruppi **Biology Lab** restano nel calendario del primo anno, ma non entrano nelle percentuali, nei riepiloghi o nelle proiezioni degli obiettivi. Le sovrapposizioni restano nelle Anomalie senza eliminare le lezioni. Il totale di Laboratory Medicine rimane 7 CFU / 70 ore; la discordanza dei moduli nel PDF attuale resta segnalata.

**English:** Biology Lab subgroups remain on the calendar but do not contribute to course attendance totals or goals. Overlaps remain informational anomalies. Laboratory Medicine retains its official 7 ECTS total and the unresolved module-allocation warning.

Su iPhone/iPad **0.4.6**, la configurazione chiede prima l’anno e poi il gruppo quando necessario, anche se una precedente configurazione incompleta aveva già salvato un anno. La prima conferma viene richiesta una sola volta senza eliminare i dati. Inoltre ogni voce di Anomalie e cronologia indica il gruppo o i gruppi coinvolti. Le incongruenze dei syllabus sono comuni ai gruppi del corso; le segnalazioni sui tornelli riguardano le badgiate personali, indipendentemente dal gruppo delle lezioni. I cambiamenti mostrano gruppo precedente e successivo.

**English:** iOS 0.4.6 asks for study year before group during setup, including incomplete migrated installations; confirmation is saved without deleting existing data. It also explicitly identifies groups in anomalies and calendar history, including before/after group changes. Course-wide syllabus notices and personal turnstile-scan warnings clearly state their scope.

## Installazione macOS

1. Apri [le release](https://github.com/lbzz98/uniattendance-beta/releases) e scarica **UniAttendance-3.0.2-macOS-universal.zip** dagli Assets. Per l’edizione UniAttendance Beta scarica **UniAttendance-3.0.2-beta.1-macOS-universal.zip**. Non scaricare Source code.
2. Chiudi la copia precedente, estrai lo ZIP e trascina l’app in **Applicazioni**, sostituendo la stessa edizione. Mantieni la stessa edizione per usare il medesimo archivio locale.
3. Apri da Applicazioni. Se macOS blocca questa beta non notarizzata, dopo il primo tentativo vai in **Impostazioni di Sistema → Privacy e sicurezza → Apri comunque** e conferma. Consenti solo la copia scaricata da questo repository. [Istruzioni Apple](https://support.apple.com/it-it/102445).
4. Al primo avvio premi **Copia richiesta di attivazione** e inviala all’organizzatore. Non servono password o credenziali UniCamillus per la licenza.
5. Importa il file **.ualicense** ricevuto con **Apri file licenza…**, oppure incolla il codice e premi **Attiva licenza**. La licenza è legata a quel Mac e installazione; le licenze valide restano utilizzabili dopo l’aggiornamento.
6. Scegli l’anno di corso (1–6), il gruppo quando richiesto e la lingua. Al terzo anno il gruppo è unico. Il tempo rimanente è visibile nella barra laterale: cliccalo per scadenza e rinnovo.
7. Gli aggiornamenti si controllano all’avvio e ogni ora mentre l’app è aperta. Da **Impostazioni → Aggiornamenti dell’app** puoi scaricare, verificare, installare e riavviare automaticamente, conservando dati e licenza. Non serve un account GitHub.

Richiede **macOS 14 o successivo**, Apple Silicon o Intel.

## Installazione Windows

1. Scarica **UniAttendance-2.3.6-beta.1-windows-x64.zip** da [le release](https://github.com/lbzz98/uniattendance-beta/releases) ed estrai tutto in una cartella scrivibile.
2. Avvia **UniAttendance.exe**. .NET è incluso; se manca WebView2, usa il collegamento ufficiale Microsoft mostrato nell’app.
3. Invia la richiesta Windows all’organizzatore e importa la licenza per quel PC. Le licenze Mac non attivano Windows. La scadenza è visibile nella barra laterale.
4. Scegli gruppo e lingua e accedi a UniCamillus con il tuo CAPTCHA. Il salvataggio delle credenziali in Gestione credenziali Windows è facoltativo.
5. Per gli aggiornamenti usa **Impostazioni → Aggiornamenti dell’app**. Non eliminare la cartella dati locale quando sostituisci il programma. Leggi INSTALL.txt incluso nello ZIP.

Target: **Windows 11 x64**, beta non firmata Authenticode. **Il collaudo dell’interfaccia, del login reale, delle credenziali e dell’installazione automatica su PC Windows resta da completare.**

## Colori dei Materiali

I nomi dei corsi e sottocorsi nei menu online e offline riprendono i colori del calendario. Su Mac gli alias dei syllabus vengono collegati al nome completo della lezione; su Windows vengono usate le famiglie viola/blu/verde del calendario, con testi adatti a Chiaro/Scuro. I docenti e le categorie generiche mantengono colori neutri. Anche iPhone/iPad 0.3.0 dispone già dei nomi colorati.

## Novità Mac 2.6.0 e iPhone/iPad 0.3.0

- Download dei materiali con barra e percentuale aggiornate dai byte ricevuti, su Mac e iOS. Se il server non comunica il totale, sono visibili i dati scaricati e un indicatore di attività. Anche gli aggiornamenti Mac mostrano l’avanzamento prima di verifica, installazione e riavvio automatici.
- Materiali Mac online e offline con etichette e icone PDF/PPT/PPTX nello stesso stile iOS.
- Anomalie Mac e iOS: conflitti tra A e B quando due lezioni sovrapposte usano la stessa aula o lo stesso docente. Sono mostrati entrambi i gruppi e l’intervallo effettivo; le lezioni consecutive non sono un conflitto.
- iOS: la ricerca mostra ✓ verde, orologio arancione o × rossa solo sulle lezioni concluse con presenza calcolata e con «Solo prossime lezioni» disattivato. Le presenze sconosciute non vengono considerate assenze.
- iOS: cronologia filtrabile per Gruppo A, Gruppo B o Tutti, con gruppo visibile in ciascuna modifica; un cambio di gruppo compare in entrambi i filtri.

**English:** live material download progress on Mac/iOS, Mac update download percentage, consistent file-format icons, and cross-group room/lecturer conflict warnings. Unknown-length transfers show bytes received. iOS search adds attendance indicators only for completed lessons with known attendance; history supports A/B/All filtering with explicit group labels. Windows remains unchanged.

## Slide e appunti su Mac

Dalla **Biblioteca offline** puoi visualizzare PDF, PowerPoint, Word e Keynote nel lettore integrato. **Solo i PDF permettono di prendere appunti** per singola slide, con salvataggio automatico sul Mac. PowerPoint, Word e Keynote hanno la sola anteprima, senza conversione e senza richiedere Keynote installato per annotare. Per prendere appunti serve il documento già in formato PDF.

I download e gli appunti sono organizzati in **Courses → corso → sottocorso → Documents / Notes**; il sottocorso viene omesso quando non serve. I documenti già salvati vengono riorganizzati preservando preferiti, segnalibri e appunti. **Mostra nel Finder** apre la loro cartella. **Esporta slide e appunti…** crea un PDF con slide a sinistra e testo a destra: l’utente sceglie sempre dove salvarlo. Le note lunghe continuano sulle pagine successive. Gli appunti restano legati alla versione del PDF.

**Aggiornamenti Mac:** dalla 2.4.0 usa normalmente il controllo aggiornamenti nell’app, con lo stesso feed `updates/macos-beta.json`. Dalla 2.3.6, installa lo ZIP una volta oppure imposta in **Fonte degli aggiornamenti** `https://raw.githubusercontent.com/lbzz98/uniattendance-beta/main/updates/macos-beta.json`, salva e controlla di nuovo. I vecchi feed ufficiali vengono migrati sul Mac dopo l’aggiornamento. Il feed precedente resta alla 2.3.6 per Windows, che non riceve modifiche in questa release.

**Mac slide notes:** actual PDFs support per-slide local autosave and side-by-side PDF export; the user always chooses the export destination. PowerPoint, Word and Keynote are preview-only, with no conversion. Downloads and notebooks are organized by course/module; existing files and notes are retained during migration. Long notes continue without truncation. The Mac update feed is unchanged; Windows stays at 2.3.6.

## Biblioteca e formati dei materiali

Il pulsante **Sposta nel Cestino** della biblioteca offline richiede conferma e usa il Cestino di macOS/Windows. Il file non viene eliminato definitivamente né reimportato al riavvio. I risultati online indicano il formato **PDF / PPT / PPTX** prima del download. La voce di tutti i docenti viene tradotta in **Tutti / All** in base alla lingua scelta.

Nella beta personale iPhone/iPad **0.3.0**, il documento viene spostato negli **Eliminati di recente** dell’app ed è ripristinabile dal pulsante Cestino della biblioteca. Online sono disponibili conteggio risultati e campo di ricerca accessibile con la tastiera anche a pagina tutta in alto.

## Syllabus aggiornati e sessione WebApp

I syllabus della coorte e dell’anno selezionati vengono controllati all’avvio e ogni ora durante l’esecuzione. I PDF sono disponibili offline e gli errori conservano l’ultima copia valida. I formati integrati supportati aggiornano moduli, docenti, email, CFU e sezioni nella lingua originale del PDF; un formato nuovo non riconosciuto rimane consultabile come PDF. Per il quarto anno, Internal Medicine include Veronese e Solimando (Geriatrics) e Capobianco (Physical Medicine and Rehabilitation). Allergology–Immunology: **1 CFU / 10 ore**, con anomalia crediti risolta.

Dopo **Disconnetti**, la sessione precedente viene azzerata prima di aprire il login ufficiale. Tornare a Materiali online durante questa operazione non riutilizza navigazioni o risultati precedenti. I punti elenco dei syllabus sono allineati al testo; le righe estratte dal PDF sono ricomposte senza perdere parole.

## Aspetto e gruppi

In **Impostazioni → Aspetto** scegli **Chiaro / Scuro**. La scelta rimane salvata sul dispositivo e si applica subito, anche al login WebApp integrato. Su Windows i pulsanti del gruppo nella barra laterale mostrano **A / B**, per evitare lettere tagliate.

Su Windows il pulsante **Disconnetti WebApp** mantiene un testo leggibile anche nel tema scuro e quando è disabilitato.

## Badgiate da controllare

In **Presenze da verificare** compaiono le giornate passate con UNI USCITA o UNI ENTRATA mancanti. Il giorno corrente (Europe/Rome) e i report vuoti sono esclusi. Si controllano solo i report scaricati dell’account attivo: aggiorna le badgiate dopo eventuali correzioni dell’università. Le percentuali dell’app restano stime dalle badgiate aula, separate dalla convalida ufficiale.

Official syllabi are checked on launch and hourly while running, with validated offline copies. Supported integrated-course PDFs update module credits, faculty, emails and sections in the document’s original language. Internal Medicine faculty are mapped to Materials; Allergology–Immunology is **1 ECTS / 10 hours**. Unknown formats remain accessible as the original PDF. Sign-out ignores stale session reads and opens a fresh login after cookie cleanup. Syllabus bullets and paragraphs are formatted for readability without dropping source text.

Offline documents can be moved to the system Trash/Recycle Bin after confirmation. Online results show PDF/PPT/PPTX file-format badges, and the lecturer selector uses the selected app language for All/Tutti. Personal iOS 0.3.0 uses an in-app Recently Deleted library with Restore; online document counts and the search-field keyboard fix are included.

Course and module names use calendar-related colors in online and offline Materials. macOS resolves syllabus aliases to the exact calendar lesson name; Windows uses its existing purple/blue/green calendar families with Light/Dark text contrast. Lecturer names and general categories stay neutral. Personal iOS 0.3.0 already includes colored names.

## English — installation

1. Open [Releases](https://github.com/lbzz98/uniattendance-beta/releases). On Mac download **UniAttendance-3.0.2-macOS-universal.zip**, or the macOS ZIP with beta.1 for the UniAttendance Beta edition. On Windows download **UniAttendance-2.3.6-beta.1-windows-x64.zip**. Do not download Source code.
2. **macOS:** quit the old copy, extract the ZIP and move the app to **Applications**, replacing the same edition. If blocked, first attempt to open it, then use **System Settings → Privacy & Security → Open Anyway** and confirm. Only allow the copy from this repository. [Apple instructions](https://support.apple.com/en-us/102445).
3. **Windows:** extract all files to a writable folder and run UniAttendance.exe. .NET is bundled; install Microsoft's WebView2 Runtime using the in-app official link if required.
4. Copy your activation request, send it to the organizer and import the .ualicense file you receive. Licenses are bound to the device and installation. Mac and Windows licenses are separate; existing valid Mac licenses survive updating.
5. Select your group and language, sign in to UniCamillus and complete the CAPTCHA yourself. Credential storage is optional and local.
6. License time remaining is visible in the sidebar. Updates are checked on launch and hourly while open; use **Settings → App updates** for download, verification, automatic replacement and restart, preserving local data.
7. **Attendance to verify** includes missing turnstile scans for past days. Today and empty reports are excluded. Only downloaded reports for the active account are checked; local percentages remain estimates rather than official validation.

Choose **Light / Dark** under **Settings → Appearance**; your choice is saved locally and applied immediately, including the embedded portal login. Windows group buttons display **A / B**. The WebApp sign-out button keeps readable text in dark mode, including its disabled state.

macOS 14+ Universal; Windows 11 x64. **Windows UI, real login, credential storage and self-update acceptance tests still need a Windows PC.** The personal **iPhone/iPad 0.3.0** beta installs through Xcode/Personal Team, not these desktop ZIPs.

Alla scadenza l’accesso all’app viene bloccato, conservando i dati. Il repository contiene solo pacchetti protetti e feed: gestore licenze, chiave privata e dati personali non sono distribuiti. UniAttendance non è un prodotto ufficiale UniCamillus.
