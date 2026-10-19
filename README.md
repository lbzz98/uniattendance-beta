# UniAttendance — beta macOS e Windows

Calendario, syllabus, materiali e presenze UniCamillus. **Versione desktop: 2.3.1 beta**. Serve una licenza per il proprio dispositivo, rilasciata dall’organizzatore della beta.

## Installazione macOS

1. Apri [le release](https://github.com/lbzz98/uniattendance-beta/releases) e scarica **UniAttendance-2.3.1-macOS-universal.zip** dagli Assets. Per l’edizione UniAttendance Beta scarica **UniAttendance-2.3.1-beta.1-macOS-universal.zip**. Non scaricare Source code.
2. Chiudi la copia precedente, estrai lo ZIP e trascina l’app in **Applicazioni**, sostituendo la stessa edizione. Mantieni la stessa edizione per usare il medesimo archivio locale.
3. Apri da Applicazioni. Se macOS blocca questa beta non notarizzata, dopo il primo tentativo vai in **Impostazioni di Sistema → Privacy e sicurezza → Apri comunque** e conferma. Consenti solo la copia scaricata da questo repository. [Istruzioni Apple](https://support.apple.com/it-it/102445).
4. Al primo avvio premi **Copia richiesta di attivazione** e inviala all’organizzatore. Non servono password o credenziali UniCamillus per la licenza.
5. Importa il file **.ualicense** ricevuto con **Apri file licenza…**, oppure incolla il codice e premi **Attiva licenza**. La licenza è legata a quel Mac e installazione; le licenze valide restano utilizzabili dopo l’aggiornamento.
6. Scegli gruppo A/B e lingua. Il tempo rimanente è visibile nella barra laterale: cliccalo per scadenza e rinnovo.
7. Gli aggiornamenti si controllano all’avvio e ogni ora mentre l’app è aperta. Da **Impostazioni → Aggiornamenti dell’app** puoi scaricare, verificare, installare e riavviare automaticamente, conservando dati e licenza. Non serve un account GitHub.

Richiede **macOS 14 o successivo**, Apple Silicon o Intel.

## Installazione Windows

1. Scarica **UniAttendance-2.3.1-beta.1-windows-x64.zip** da [le release](https://github.com/lbzz98/uniattendance-beta/releases) ed estrai tutto in una cartella scrivibile.
2. Avvia **UniAttendance.exe**. .NET è incluso; se manca WebView2, usa il collegamento ufficiale Microsoft mostrato nell’app.
3. Invia la richiesta Windows all’organizzatore e importa la licenza per quel PC. Le licenze Mac non attivano Windows. La scadenza è visibile nella barra laterale.
4. Scegli gruppo e lingua e accedi a UniCamillus con il tuo CAPTCHA. Il salvataggio delle credenziali in Gestione credenziali Windows è facoltativo.
5. Per gli aggiornamenti usa **Impostazioni → Aggiornamenti dell’app**. Non eliminare la cartella dati locale quando sostituisci il programma. Leggi INSTALL.txt incluso nello ZIP.

Target: **Windows 11 x64**, beta non firmata Authenticode. **Il collaudo dell’interfaccia, del login reale, delle credenziali e dell’installazione automatica su PC Windows resta da completare.**

## Aspetto e gruppi

In **Impostazioni → Aspetto** scegli **Sistema / Chiaro / Scuro**. La scelta rimane salvata sul dispositivo e si applica subito, anche al login WebApp integrato. Su Windows i pulsanti del gruppo nella barra laterale mostrano **A / B**, per evitare lettere tagliate.

## Badgiate da controllare

In **Presenze da verificare** compaiono le giornate passate con UNI USCITA o UNI ENTRATA mancanti. Il giorno corrente (Europe/Rome) e i report vuoti sono esclusi. Si controllano solo i report scaricati dell’account attivo: aggiorna le badgiate dopo eventuali correzioni dell’università. Le percentuali dell’app restano stime dalle badgiate aula, separate dalla convalida ufficiale.

## English — installation

1. Open [Releases](https://github.com/lbzz98/uniattendance-beta/releases). On Mac download **UniAttendance-2.3.1-macOS-universal.zip**, or the macOS ZIP with beta.1 for the UniAttendance Beta edition. On Windows download **UniAttendance-2.3.1-beta.1-windows-x64.zip**. Do not download Source code.
2. **macOS:** quit the old copy, extract the ZIP and move the app to **Applications**, replacing the same edition. If blocked, first attempt to open it, then use **System Settings → Privacy & Security → Open Anyway** and confirm. Only allow the copy from this repository. [Apple instructions](https://support.apple.com/en-us/102445).
3. **Windows:** extract all files to a writable folder and run UniAttendance.exe. .NET is bundled; install Microsoft's WebView2 Runtime using the in-app official link if required.
4. Copy your activation request, send it to the organizer and import the .ualicense file you receive. Licenses are bound to the device and installation. Mac and Windows licenses are separate; existing valid Mac licenses survive updating.
5. Select your group and language, sign in to UniCamillus and complete the CAPTCHA yourself. Credential storage is optional and local.
6. License time remaining is visible in the sidebar. Updates are checked on launch and hourly while open; use **Settings → App updates** for download, verification, automatic replacement and restart, preserving local data.
7. **Attendance to verify** includes missing turnstile scans for past days. Today and empty reports are excluded. Only downloaded reports for the active account are checked; local percentages remain estimates rather than official validation.

Choose **System / Light / Dark** under **Settings → Appearance**; your choice is saved locally and applied immediately, including the embedded portal login. Windows group buttons display **A / B**.

macOS 14+ Universal; Windows 11 x64. **Windows UI, real login, credential storage and self-update acceptance tests still need a Windows PC.** The personal **iPhone/iPad 0.2.0** beta installs through Xcode/Personal Team, not these desktop ZIPs.

Alla scadenza l’accesso all’app viene bloccato, conservando i dati. Il repository contiene solo pacchetti protetti e feed: gestore licenze, chiave privata e dati personali non sono distribuiti. UniAttendance non è un prodotto ufficiale UniCamillus.
