# importctl

> Scarica, importa o esporta immagini disco.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/importctl.html>.

- Scarica un'immagine in formato tarball da un URL tramite pull:

`sudo importctl pull-tar {{URL}} {{path/to/directory}}`

- Esegue il pull o scarica da una sorgente remota che è un file raw o `.qcow2` e lo memorizza come file raw:

`sudo importctl pull-raw {{https://example.com/source.ext}} {{name}} --class={{machine|portable|sysext|confext}}`

- Importa un'immagine disco raw nella directory delle immagini, possibilmente compressa con `xz`, `gzip` o `bzip2`:

`importctl import-raw {{path/to/file.ext}} {{name}} --class={{machine|portable|sysext|confext}}`

- Esporta un'immagine contenitore come tarball nella directory di lavoro corrente:

`importctl export-tar --class={{machine|portable|sysext|confext}} {{name}} {{path/to/file.ext}}`
