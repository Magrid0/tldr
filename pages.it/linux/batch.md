# batch

> Esegue comandi in un secondo momento quando i livelli di carico del sistema lo consentono.
> I risultati verranno inviati alla posta dell'utente.
> Vedi anche: `at`, `atq`, `atrm`, `mail`.
> Maggiori informazioni: <https://manned.org/batch>.

- Avvia il demone `atd`:

`systemctl start atd`

- Esegue comandi da `stdin` (premere `<Ctrl d>` quando si ha finito):

`batch`

- Esegue un comando da `stdin`:

`echo "{{./make_db_backup.sh}}" | batch`
