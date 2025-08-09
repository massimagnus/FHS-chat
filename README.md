========================================
P2P Chat - Istruzioni per l'uso
========================================

Questa è una chat privata peer-to-peer (P2P) che funziona direttamente
nel browser, senza installare nulla e senza account.

I messaggi viaggiano cifrati tra i due browser usando WebRTC.
Il server è usato solo per avviare la connessione (signaling).

----------------------------------------
COME USARE LA CHAT
----------------------------------------

1. Apri la pagina della chat (file index.html) da un indirizzo HTTPS.
   - Puoi caricare il file su un servizio gratuito come Netlify Drop o GitHub Pages.
   - Se sei in locale, funziona anche su http://localhost.

2. Due modalità di utilizzo:
   - **Utente A (crea la chat)**:
     Clicca "Crea chat".
     Verrà mostrato un CODICE (es. P2P-AB123).
     Comunica questo codice all'altra persona.
   - **Utente B (entra in chat)**:
     Inserisci il codice ricevuto nel campo di testo e clicca "Entra".

3. Dopo pochi secondi, la connessione sarà attiva e potete scambiarvi messaggi.

----------------------------------------
NOTE IMPORTANTI
----------------------------------------

- Funziona anche su smartphone e tablet (serve HTTPS).
- I messaggi non passano da un server centrale: il flusso è diretto tra i due dispositivi.
- In alcune reti aziendali o pubbliche, la connessione P2P potrebbe non riuscire per blocchi firewall/NAT.
- Non inviare informazioni sensibili a persone che non conosci.

----------------------------------------
SUGGERIMENTI
----------------------------------------

- Per chattare tra due dispositivi diversi, basta che entrambi abbiano accesso a Internet.
- Se vuoi testarla in locale:
  - Apri il file index.html con "Apri con..." nel browser (alcuni
