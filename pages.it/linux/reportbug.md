# reportbug

> Strumento di segnalazione bug della distribuzione Debian.
> Maggiori informazioni: <https://manned.org/reportbug>.

- Genera un rapporto di bug su un pacchetto specifico, poi lo invia per e-mail:

`reportbug {{package}}`

- Segnala un bug che non riguarda un pacchetto specifico (problema generale, infrastruttura, ecc.):

`reportbug other`

- Scrive il rapporto di bug in un file invece di inviarlo per e-mail:

`reportbug {{[-o|--output]}} {{filename}} {{package}}`
