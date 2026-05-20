# extundelete

> Recupera file eliminati da partizioni ext3 o ext4 analizzando il journal.
> Vedi anche: `date`, `umount`.
> Maggiori informazioni: <https://extundelete.sourceforge.net/options.html>.

- Ripristina tutti i file eliminati all'interno della partizione `N` sul dispositivo `X`:

`sudo extundelete {{/dev/sdXN}} --restore-all`

- Ripristina un file da un percorso relativo alla radice (non iniziare il percorso con `/`):

`extundelete {{/dev/sdXN}} --restore-file {{path/to/file}}`

- Ripristina una directory da un percorso relativo alla radice (non iniziare il percorso con `/`):

`extundelete {{/dev/sdXN}} --restore-directory {{path/to/directory}}`

- Ripristina tutti i file eliminati dopo il 1° gennaio 2020 (in tempo Unix):

`extundelete {{/dev/sdXN}} --restore-all --after {{1577840400}}`
