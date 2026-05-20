# debman

> Legge le pagine man da pacchetti non installati.
> Maggiori informazioni: <https://manned.org/debman>.

- Legge una pagina man per un comando fornito da un [p]acchetto specifico:

`debman -p {{package}} {{command}}`

- Specifica una versione di [p]acchetto da scaricare:

`debman -p {{package}}={{version}} {{command}}`

- Legge una pagina man in un [f]ile `.deb`:

`debman -f {{path/to/file.deb}} {{command}}`
