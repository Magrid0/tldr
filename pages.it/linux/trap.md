# trap

> Esegue un comando al verificarsi di un evento.
> Maggiori informazioni: <https://www.gnu.org/software/bash/manual/bash.html#index-trap>.

- Elenca i nomi degli eventi disponibili (es. `SIGWINCH`):

`trap -l`

- Elenca i comandi e i nomi degli eventi previsti:

`trap`

- Esegui un comando quando viene ricevuto un segnale:

`trap 'echo "Ricevuto segnale {{SIGHUP}}"' {{SIGHUP}}`

- Rimuovi i comandi:

`trap - {{SIGHUP}} {{SIGINT}}`

- Ignora un segnale:

`trap '' {{SIGINT}}`
