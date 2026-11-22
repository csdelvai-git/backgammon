# Cassa Backgammon

Web-app per segnare i punti delle partite di backgammon, tenere lo storico delle giornate e la cassa per la cena.

- Ogni giornata è indipendente, con il proprio valore in € per punto; chi perde la giornata versa la differenza in cassa.
- I dati restano sul dispositivo (localStorage). "Invia giornata" condivide un file `giornata_AAAA-MM-GG.txt` (JSON) via WhatsApp/email, importabile nel registro.
- Installabile su Android: apri la pagina in Chrome → ⋮ → "Aggiungi a schermata Home".
