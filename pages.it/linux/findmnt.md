# findmnt

> Trova il tuo filesystem.
> Maggiori informazioni: <https://manned.org/findmnt>.

- Elenca tutti i filesystem montati:

`findmnt`

- Cerca un dispositivo:

`findmnt {{/dev/sdb1}}`

- Cerca un punto di mount:

`findmnt {{/}}`

- Trova filesystem di un tipo specifico:

`findmnt {{[-t|--types]}} {{ext4,virtiofs,btrfs,...}}`

- Trova filesystem con una etichetta specifica:

`findmnt LABEL={{BigStorage}}`

- Controlla il contenuto della tabella di montaggio in dettaglio e verifica `/etc/fstab`:

`findmnt {{[-x|--verify]}} --verbose`
