# goaccess

> Analizzatore di log web in tempo reale open source.
> Maggiori informazioni: <https://goaccess.io/man>.

- Analizza uno o più file di log in modalità interattiva:

`goaccess {{path/to/logfile1 path/to/file2 ...}}`

- Usa un formato di log specifico (o formati predefiniti come "combined"):

`goaccess {{path/to/logfile}} --log-format={{format}}`

- Analizza un log da `stdin`:

`tail {{[-f|--follow]}} {{path/to/logfile}} | goaccess -`

- Analizza un log e lo scrive in un file HTML in tempo reale:

`goaccess {{path/to/logfile}} {{[-o|--output]}} {{path/to/file.html}} --real-time-html`
