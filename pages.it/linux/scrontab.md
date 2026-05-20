# scrontab

> Gestisce i file crontab di Slurm.
> Maggiori informazioni: <https://slurm.schedmd.com/scrontab.html>.

- Installa un nuovo crontab dal file specificato:

`scrontab {{percorso/del/file}}`

- [e]dita il crontab dell'utente corrente:

`scrontab -e`

- [e]dita il crontab dell'utente specificato:

`scrontab --user={{id_utente}} -e`

- [r]imuove il crontab corrente:

`scrontab -r`

- Stamp[a] il crontab dell'utente corrente su `stdout`:

`scrontab -l`
