# script

> Registra tutto l'output del terminale in un file typescript.
> Maggiori informazioni: <https://manned.org/script>.

- Registra una nuova sessione in un file chiamato `typescript` nella directory corrente:

`script`

- Interrompe la registrazione:

`exit`

- Registra una nuova sessione in un percorso file personalizzato:

`script {{percorso/della/sessione.out}}`

- Aggiunge a un file esistente:

`script {{[-a|--append]}} {{file_log.log}}`

- Registra informazioni di temporizzazione (i dati vengono inviati a `stderr`):

`script {{[-t|--timing]}} 2> {{percorso/del/file_timing}}`

- Scrive i dati non appena accadono:

`script {{[-f|--flush]}} {{percorso/del/file}}`

- Esegue silenziosamente senza messaggi di inizio e fine:

`script {{[-q|--quiet]}} {{file_log.log}}`

- Mostra aiuto:

`script {{[-h|--help]}}`
