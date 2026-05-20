# fatrace

> Segnala eventi di accesso ai file.
> Vedi anche: `inotifywait`.
> Maggiori informazioni: <https://manned.org/fatrace>.

- Stampa su `stdout` gli eventi di accesso ai file in tutti i filesystem montati:

`sudo fatrace`

- Limita l'output a un programma con un nome specifico:

`sudo fatrace {{[-C|--command]}} {{program_name}}`

- Stampa su `stdout` gli eventi di accesso ai file sul mountpoint della directory corrente:

`sudo fatrace {{[-c|--current-mount]}}`

- Aggiunge timestamp all'output:

`sudo fatrace {{[-t|--timestamp]}}`
