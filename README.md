# Cassa Backgammon

Web-app per segnare i punti delle partite di backgammon, tenere lo storico delle giornate e la cassa per la cena.

- Ogni giornata è indipendente, con il proprio valore in € per punto; chi perde la giornata versa la differenza in cassa.
- I dati restano sul dispositivo (localStorage) e, se collegato, si sincronizzano con un file JSON in un repo GitHub privato (token fine-grained, Contents read/write). Le modifiche da più dispositivi vengono unite.
- "Invia giornata" condivide un file `giornata_AAAA-MM-GG.txt` (JSON) via WhatsApp/email, importabile nel registro.
- Installabile su Android: apri la pagina in Chrome → ⋮ → "Aggiungi a schermata Home".
