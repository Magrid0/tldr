# gdebi

> Installa facilmente file `.deb`.
> Maggiori informazioni: <https://manned.org/gdebi>.

- Installa pacchetti `.deb` locali risolvendo e installando le loro dipendenze:

`gdebi {{path/to/package.deb}}`

- Non mostrare informazioni di avanzamento:

`gdebi {{path/to/package.deb}} {{[-q|--quiet]}}`

- Imposta un'opzione di configurazione APT:

`gdebi {{path/to/package.deb}} {{[-o|--option]}} {{apt_options}}`

- Usa una directory root alternativa:

`gdebi {{path/to/package.deb}} --root {{path/to/root_directory}}`

- Mostra versione:

`gdebi --version`
