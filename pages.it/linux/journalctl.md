# journalctl

> Interroga il journal di systemd.
> Vedi anche: `dmesg`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/journalctl.html>.

- Mostra le ultime `n` righe e segue i nuovi messaggi (come `tail --follow` per il syslog tradizionale):

`journalctl {{[-n|--lines]}} {{n}} {{[-f|--follow]}}`

- Mostra tutti i messaggi con livello di priorità 3 (errori) dall'avvio precedente all'ultimo spegnimento:

`journalctl {{[-b|--boot]}} -1 {{[-p|--priority]}} 3`

- Mostra tutti i messaggi di una specifica unità:

`journalctl {{[-u|--unit]}} {{unit}}`

- Mostra i log per una data unità dall'ultimo avvio:

`journalctl _SYSTEMD_INVOCATION_ID=$(systemctl show --value --property=InvocationID {{unit}})`

- Filtra i messaggi entro un intervallo di tempo (timestamp o placeholder come "yesterday"):

`journalctl {{[-S|--since]}} {{now|today|yesterday|tomorrow|...}} {{[-U|--until]}} "{{YYYY-MM-DD HH:MM:SS}}"`

- Mostra tutti i messaggi di un processo specifico:

`journalctl _PID={{pid}}`

- Mostra tutti i messaggi di un eseguibile specifico:

`journalctl {{path/to/executable}}`

- Elimina i log del journal più vecchi di 2 giorni:

`journalctl --vacuum-time 2d`
