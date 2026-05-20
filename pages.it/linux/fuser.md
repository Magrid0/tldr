# fuser

> Mostra gli ID dei processi che stanno attualmente utilizzando file o socket.
> Maggiori informazioni: <https://manned.org/fuser>.

- Trova quali processi stanno accedendo a un file o directory:

`fuser {{path/to/file_or_directory}}`

- Mostra più campi (`USER`, `PID`, `ACCESS` e `COMMAND`):

`fuser {{[-v|--verbose]}} {{path/to/file_or_directory}}`

- Identifica i processi che utilizzano un socket TCP:

`fuser {{port}}/tcp`

- Uccide tutti i processi che accedono a un file o directory (invia il segnale `SIGKILL`):

`fuser {{[-k|--kill]}} {{path/to/file_or_directory}}`

- Trova quali processi stanno accedendo al filesystem contenente un file o directory specifico:

`fuser {{[-m|--mount]}} {{path/to/file_or_directory}}`

- Uccide tutti i processi con una connessione TCP su una porta specifica:

`fuser {{[-k|--kill]}} {{port}}/tcp`
