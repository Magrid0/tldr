# rexec

> Esegue un comando su un host remoto.
> Nota: usa `rexec` con cautela, poiché trasmette dati in chiaro. Considera alternative sicure come SSH per la comunicazione cifrata.
> Maggiori informazioni: <https://www.gnu.org/software/inetutils/manual/inetutils.html#rexec-invocation>.

- Esegue un comando su un host remoto:

`rexec {{[-h|--host]}} {{remote_host}} {{ls -l}}`

- Specifica il nome utente remoto su un host remoto:

`rexec {{[-u|--username]}} {{username}} {{[-h|--host]}} {{remote_host}} {{ps aux}}`

- Reindirizza `stdin` da `/dev/null` su un host remoto:

`rexec {{[-n|--noerr]}} {{[-h|--host]}} {{remote_host}} {{ls -l}}`

- Specifica la porta remota su un host remoto:

`rexec {{[-P|--port]}} {{1234}} {{[-h|--host]}} {{remote_host}} {{ls -l}}`
