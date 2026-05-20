# mocp

> Lettore audio Music on Console (MOC).
> Maggiori informazioni: <https://manned.org/mocp>.

- Avvia l'interfaccia utente terminale di MOC:

`mocp`

- Avvia l'interfaccia utente terminale di MOC in una directory specifica:

`mocp {{path/to/directory}}`

- Avvia il server MOC in background, senza lanciare l'interfaccia utente terminale:

`mocp {{[-S|--server]}}`

- Aggiunge una canzone specifica alla coda di riproduzione mentre MOC è in background:

`mocp {{[-q|--enqueue]}} {{path/to/audio_file}}`

- Aggiunge canzoni ricorsivamente alla coda di riproduzione mentre MOC è in background:

`mocp {{[-a|--append]}} {{path/to/directory}}`

- Pulisce la coda di riproduzione mentre MOC è in background:

`mocp {{[-c|--clear]}}`

- Riproduce o ferma la canzone attualmente in coda mentre MOC è in background:

`mocp --{{play|stop}}`

- Ferma il server MOC mentre è in background:

`mocp {{[-x|--exit]}}`
