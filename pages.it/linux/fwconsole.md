# fwconsole

> Gestisce e configura il sistema FreePBX (server PBX).
> Maggiori informazioni: <https://sangomakb.atlassian.net/wiki/spaces/PG/pages/41779247/fwconsole+commands+13>.

- Ricarica le configurazioni di FreePBX:

`fwconsole reload`

- Avvia Asterisk e altri comandi necessari per FreePBX:

`fwconsole start`

- Arresta Asterisk e altri comandi necessari per FreePBX:

`fwconsole stop`

- Visualizza e aggiorna le impostazioni:

`fwconsole setting {{keyword}} {{new_value}}`

- Elenca i backup disponibili:

`fwconsole backup --list`

- Elenca i comandi FreePBX disponibili:

`fwconsole list`

- Cambia la proprietà di tutti i file e directory che FreePBX necessita siano di proprietà dell'utente apache:

`fwconsole chown`
