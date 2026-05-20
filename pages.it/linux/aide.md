# aide

> Advanced Intrusion Detection Environment per convalidare l'integrità dei file.
> Maggiori informazioni: <https://manned.org/aide>.

- Inizializza il database:

`sudo aide {{[-i|--init]}}`

- Controlla il database per incongruenze:

`sudo aide {{[-C|--check]}}`

- Confronta due database secondo le definizioni nel file di configurazione:

`sudo aide {{[-E|--compare]}}`

- Controlla e aggiorna il database in modo non interattivo:

`sudo aide {{[-u|--update]}}`

- Definisce un file di configurazione per sovrascrivere il `aide.conf` predefinito:

`sudo aide {{[-c|--config]}} {{path/to/config_file}}`

- Utilizza `regex` per limitare AIDE a una stringa specifica:

`sudo aide {{[-l|--limit]}} {{regex}}`

- Invia i risultati del reporter a un URL:

`sudo aide {{[-r|--report]}} {{reporterurl}}`
