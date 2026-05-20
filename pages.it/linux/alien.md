# alien

> Converte diversi pacchetti di installazione in altri formati.
> Vedi anche: `debtap`.
> Maggiori informazioni: <https://manned.org/alien>.

- Converte un file di installazione specifico nel formato Debian (estensione `.deb`):

`sudo alien {{[-d|--to-deb]}} {{path/to/file}}`

- Converte un file di installazione specifico nel formato Red Hat (estensione `.rpm`):

`sudo alien {{[-r|--to-rpm]}} {{path/to/file}}`

- Converte un file di installazione specifico in un file di installazione Slackware (estensione `.tgz`):

`sudo alien {{[-t|--to-tgz]}} {{path/to/file}}`

- Converte un file di installazione specifico nel formato Debian e lo installa sul sistema:

`sudo alien {{[-d|--to-deb]}} {{[-i|--install]}} {{path/to/file}}`
