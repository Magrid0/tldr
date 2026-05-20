# top

> Mostra informazioni dinamiche in tempo reale sui processi in esecuzione.
> Vedi anche: `htop`, `atop`, `glances`, `btop`, `btm`.
> Maggiori informazioni: <https://manned.org/top>.

- Avvia `top`:

`top`

- Non mostrare processi idle o zombie:

`top {{[-i|--idle-toggle]}}`

- Mostra solo i processi posseduti da un dato utente:

`top {{[-u|--filter-only-euser]}} {{nome_utente}}`

- Ordina i processi per un campo:

`top {{[-o|--sort-override]}} {{nome_campo}}`

- Mostra i singoli thread di un dato processo:

`top {{[-Hp|--threads-show --pid]}} {{id_processo}}`

- Mostra solo i processi con i PID specificati, passati come lista separata da virgole. (Normalmente non si conoscono i PID a memoria. Questo esempio prende i PID dal nome del processo):

`top {{[-p|--pid]}} $(pgrep {{[-d|--delimiter]}} ',' {{nome_processo}})`

- Mostra l'aiuto sui comandi interattivi:

`<?>`
