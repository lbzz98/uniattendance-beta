# UniAttendance — beta macOS e Windows

Calendario, syllabus, materiali e presenze UniCamillus. **Versione desktop: 2.3.6 beta**. Serve una licenza per il proprio dispositivo, rilasciata dall’organizzatore della beta.

## Installazione macOS

1. Apri [le release](https://github.com/lbzz98/uniattendance-beta/releases) e scarica **UniAttendance-2.3.6-macOS-universal.zip** dagli Assets. Per l’edizione UniAttendance Beta scarica **UniAttendance-2.3.6-beta.1-macOS-universal.zip**. Non scaricare Source code.
2. Chiudi la copia precedente, estrai lo ZIP e trascina l’app in **Applicazioni**, sostituendo la stessa edizione. Mantieni la stessa edizione per usare il medesimo archivio locale.
3. Apri da Applicazioni. Se macOS blocca questa beta non notarizzata, dopo il primo tentativo vai in **Impostazioni di Sistema → Privacy e sicurezza → Apri comunque** e conferma. Consenti solo la copia scaricata da questo repository. [Istruzioni Apple](https://support.apple.com/it-it/102445).
4. Al primo avvio premi **Copia richiesta di attivazione** e inviala all’organizzatore. Non servono password o credenziali UniCamillus per la licenza.
5. Importa il file **.ualicense** ricevuto con **Apri file licenza…**, oppure incolla il codice e premi **Attiva licenza**. La licenza è legata a quel Mac e installazione; le licenze valide restano utilizzabili dopo l’aggiornamento.
6. Scegli gruppo A/B e lingua. Il tempo rimanente è visibile nella barra laterale: cliccalo per scadenza e rinnovo.
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

I nomi dei corsi e sottocorsi nei menu online e offline riprendono i colori del calendario. Su Mac gli alias dei syllabus vengono collegati al nome completo della lezione; su Windows vengono usate le famiglie viola/blu/verde del calendario, con testi adatti a Chiaro/Scuro. I docenti e le categorie generiche mantengono colori neutri. Anche iPhone/iPad 0.2.10 dispone già dei nomi colorati.

## Biblioteca e formati dei materiali

Il pulsante **Sposta nel Cestino** della biblioteca offline richiede conferma e usa il Cestino di macOS/Windows. Il file non viene eliminato definitivamente né reimportato al riavvio. I risultati online indicano il formato **PDF / PPT / PPTX** prima del download. La voce di tutti i docenti viene tradotta in **Tutti / All** in base alla lingua scelta.

Nella beta personale iPhone/iPad **0.2.10**, il documento viene spostato negli **Eliminati di recente** dell’app ed è ripristinabile dal pulsante Cestino della biblioteca. Online sono disponibili conteggio risultati e campo di ricerca accessibile con la tastiera anche a pagina tutta in alto.

## Syllabus aggiornati e sessione WebApp

I tre syllabus ufficiali vengono controllati all’avvio e ogni ora durante l’esecuzione. I PDF sono disponibili offline e gli errori conservano l’ultima copia valida. I formati integrati supportati aggiornano moduli, docenti, email, CFU e sezioni nella lingua originale del PDF; un formato nuovo non riconosciuto rimane consultabile come PDF. Internal Medicine include Veronese e Solimando (Geriatrics) e Capobianco (Physical Medicine and Rehabilitation). Allergology–Immunology: **1 CFU / 10 ore**, con anomalia crediti risolta.

Dopo **Disconnetti**, la sessione precedente viene azzerata prima di aprire il login ufficiale. Tornare a Materiali online durante questa operazione non riutilizza navigazioni o risultati precedenti. I punti elenco dei syllabus sono allineati al testo; le righe estratte dal PDF sono ricomposte senza perdere parole.

## Aspetto e gruppi

In **Impostazioni → Aspetto** scegli **Chiaro / Scuro**. La scelta rimane salvata sul dispositivo e si applica subito, anche al login WebApp integrato. Su Windows i pulsanti del gruppo nella barra laterale mostrano **A / B**, per evitare lettere tagliate.

Su Windows il pulsante **Disconnetti WebApp** mantiene un testo leggibile anche nel tema scuro e quando è disabilitato.

## Badgiate da controllare

In **Presenze da verificare** compaiono le giornate passate con UNI USCITA o UNI ENTRATA mancanti. Il giorno corrente (Europe/Rome) e i report vuoti sono esclusi. Si controllano solo i report scaricati dell’account attivo: aggiorna le badgiate dopo eventuali correzioni dell’università. Le percentuali dell’app restano stime dalle badgiate aula, separate dalla convalida ufficiale.

Official syllabi are checked on launch and hourly while running, with validated offline copies. Supported integrated-course PDFs update module credits, faculty, emails and sections in the document’s original language. Internal Medicine faculty are mapped to Materials; Allergology–Immunology is **1 ECTS / 10 hours**. Unknown formats remain accessible as the original PDF. Sign-out ignores stale session reads and opens a fresh login after cookie cleanup. Syllabus bullets and paragraphs are formatted for readability without dropping source text.

Offline documents can be moved to the system Trash/Recycle Bin after confirmation. Online results show PDF/PPT/PPTX file-format badges, and the lecturer selector uses the selected app language for All/Tutti. Personal iOS 0.2.10 uses an in-app Recently Deleted library with Restore; online document counts and the search-field keyboard fix are included.

Course and module names use calendar-related colors in online and offline Materials. macOS resolves syllabus aliases to the exact calendar lesson name; Windows uses its existing purple/blue/green calendar families with Light/Dark text contrast. Lecturer names and general categories stay neutral. Personal iOS 0.2.10 already includes colored names.

## English — installation

1. Open [Releases](https://github.com/lbzz98/uniattendance-beta/releases). On Mac download **UniAttendance-2.3.6-macOS-universal.zip**, or the macOS ZIP with beta.1 for the UniAttendance Beta edition. On Windows download **UniAttendance-2.3.6-beta.1-windows-x64.zip**. Do not download Source code.
2. **macOS:** quit the old copy, extract the ZIP and move the app to **Applications**, replacing the same edition. If blocked, first attempt to open it, then use **System Settings → Privacy & Security → Open Anyway** and confirm. Only allow the copy from this repository. [Apple instructions](https://support.apple.com/en-us/102445).
3. **Windows:** extract all files to a writable folder and run UniAttendance.exe. .NET is bundled; install Microsoft's WebView2 Runtime using the in-app official link if required.
4. Copy your activation request, send it to the organizer and import the .ualicense file you receive. Licenses are bound to the device and installation. Mac and Windows licenses are separate; existing valid Mac licenses survive updating.
5. Select your group and language, sign in to UniCamillus and complete the CAPTCHA yourself. Credential storage is optional and local.
6. License time remaining is visible in the sidebar. Updates are checked on launch and hourly while open; use **Settings → App updates** for download, verification, automatic replacement and restart, preserving local data.
7. **Attendance to verify** includes missing turnstile scans for past days. Today and empty reports are excluded. Only downloaded reports for the active account are checked; local percentages remain estimates rather than official validation.

Choose **Light / Dark** under **Settings → Appearance**; your choice is saved locally and applied immediately, including the embedded portal login. Windows group buttons display **A / B**. The WebApp sign-out button keeps readable text in dark mode, including its disabled state.

macOS 14+ Universal; Windows 11 x64. **Windows UI, real login, credential storage and self-update acceptance tests still need a Windows PC.** The personal **iPhone/iPad 0.2.10** beta installs through Xcode/Personal Team, not these desktop ZIPs.

Alla scadenza l’accesso all’app viene bloccato, conservando i dati. Il repository contiene solo pacchetti protetti e feed: gestore licenze, chiave privata e dati personali non sono distribuiti. UniAttendance non è un prodotto ufficiale UniCamillus.
