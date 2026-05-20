# oma

> Un frontend di gestione pacchetti per distribuzioni Linux basate su dpkg.
> Maggiori informazioni: <https://github.com/AOSC-Dev/oma#usage>.

- Entra nell'interfaccia interattiva di gestione pacchetti:

`sudo oma`

- Installa un pacchetto:

`sudo oma install {{nome_pacchetto}}`

- Rimuove un pacchetto:

`sudo oma remove {{nome_pacchetto}}`

- Cerca un pacchetto:

`oma search {{parola_chiave}}`

- Mostra informazioni dettagliate per un pacchetto:

`oma show`

- Aggiorna tutti i pacchetti installati alle ultime versioni:

`sudo oma upgrade`

- Aggiorna l'elenco dei pacchetti e versioni disponibili (eseguito automaticamente prima di `oma install` e `oma upgrade`):

`sudo oma refresh`

- Mostra aiuto:

`oma help`
