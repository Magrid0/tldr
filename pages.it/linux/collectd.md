# collectd

> Demone di raccolta statistiche di sistema.
> Maggiori informazioni: <https://manned.org/collectd>.

- Verifica il file di configurazione e poi esce:

`collectd -t`

- Verifica la funzionalità di raccolta dati del plugin e poi esce:

`collectd -T`

- Avvia `collectd`:

`collectd`

- Specifica una posizione personalizzata per il file di configurazione:

`collectd -C {{path/to/file}}`

- Specifica una posizione personalizzata per il file PID:

`collectd -P {{path/to/file}}`

- Non esegue il fork in background:

`collectd -f`

- Mostra aiuto e versione:

`collectd -h`
