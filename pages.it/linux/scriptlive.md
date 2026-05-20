# scriptlive

> Esegue un typescript creato dal comando `script` in tempo reale.
> Vedi anche: `script`.
> Maggiori informazioni: <https://manned.org/scriptlive>.

- Esegue un typescript in tempo reale:

`scriptlive {{percorso/del/file_timing}} {{percorso/del/typescript}}`

- Esegue un typescript al doppio della velocità originale:

`scriptlive {{percorso/del/file_timing}} {{percorso/del/typescript}} --divisor 2`

- Esegue un typescript creato usando l'opzione `--log-in` di `script`:

`scriptlive --log-in {{percorso/del/file_log_stdin}} {{percorso/del/typescript}}`

- Esegue un typescript aspettando al massimo 2 secondi tra un comando e l'altro:

`scriptlive {{percorso/del/file_timing}} {{percorso/del/typescript}} --maxdelay 2`
