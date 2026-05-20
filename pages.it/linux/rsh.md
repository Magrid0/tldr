# rsh

> Esegue comandi su un host remoto.
> Maggiori informazioni: <https://www.gnu.org/software/inetutils/manual/inetutils.html#rsh-invocation>.

- Esegue un comando su un host remoto:

`rsh {{remote_host}} {{ls -l}}`

- Esegue un comando su un host remoto con un nome utente specifico:

`rsh {{remote_host}} {{[-l|--user]}} {{username}} {{ls -l}}`

- Reindirizza `stdin` a `/dev/null` durante l'esecuzione di un comando su un host remoto:

`rsh {{remote_host}} --no-err {{ls -l}}`
