# Personal Portfolio

Questo repository ospita il codice sorgente del mio sito portfolio. Il progetto è stato sviluppato con l'obiettivo di creare una piattaforma leggera, manutenibile e accessibile.

## Stack Tecnologico
* **HTML5 Semantico**: per una struttura accessibile, navigabile da screen reader e chiara.
* **Bootstrap 5.3**: utilizzato per il sistema di grid a 12 colonne, utility e componentistica di base, personalizzato direttamente dai sorgenti SCSS.
* **SASS / SCSS**: architettura modulare (convenzione BEM con prefissi `c-` e `l-`), gestione dei token di design e override preventivo delle variabili prima della compilazione del framework.
* **Formspree**: integrazione nativa tramite form `method="POST"` per l'invio dei messaggi, eliminando la necessità di script lato client.
* **Zero JavaScript Custom**: piena conformità al vincolo del corso ("Solo HTML e CSS"); l'unico script caricato è il bundle ufficiale di Bootstrap per il supporto al toggle della navbar su mobile e allo ScrollSpy.

## Metodologia e Standard
Il progetto segue criteri rigorosi di sviluppo web:

1. **Accessibilità (A11y):** Particolare attenzione è stata dedicata alla semantica HTML e al contrasto cromatico. Il codice viene costantemente monitorato tramite l'estensione **WAVE (Web Accessibility Evaluation Tool)** per garantire l'accessibilità a tutti gli utenti.
2. **Mobile-First Design:** L'interfaccia è stata progettata per essere completamente responsiva, garantendo un'esperienza d'uso fluida su dispositivi mobile, tablet e desktop.
3. **Ottimizzazione:** Utilizzo di SASS per mantenere il CSS organizzato e scalabile, riducendo le ridondanze nel codice finale.

## Strumenti di Validazione
* WAVE Evaluation Tool (Accessibilità)
* W3C Validator (HTML/CSS)
* Lighthouse (Performance e Best Practices)

## Installazione

Questo repository non include i file sorgente di Bootstrap per mantenere il progetto leggero. Per compilare il codice SASS correttamente, segui questi passaggi:

1. Scarica il codice sorgente di **Bootstrap 5.3.x** dal [sito ufficiale](https://getbootstrap.com/docs/5.3/getting-started/download/#source-files).
2. Estrai il contenuto del pacchetto.
3. Rinomina la cartella estratta in `bootstrap-5.3.8` (o assicurati che il percorso corrisponda a quello importato in `assets/scss/style.scss`).
4. Posiziona la cartella dentro il percorso `assets/`.

Il percorso finale dovrebbe essere: `assets/bootstrap-5.3.8/`.
