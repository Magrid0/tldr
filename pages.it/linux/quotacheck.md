# quotacheck

> Scansiona un filesystem per l'utilizzo del disco; crea, controlla e ripara i file di quota.
> È meglio eseguire il controllo delle quote con le quote disattivate per prevenire danni o perdite ai file di quota.
> Maggiori informazioni: <https://manned.org/quotacheck>.

- Controlla le quote su tutti i filesystem montati non NFS:

`sudo quotacheck --all`

- Forza il controllo anche se le quote sono abilitate (può causare danni o perdita ai file di quota):

`sudo quotacheck --force {{mountpoint}}`

- Controlla le quote su un filesystem specificato in modalità debug:

`sudo quotacheck --debug {{mountpoint}}`

- Controlla le quote su un filesystem specificato, mostrando il progresso:

`sudo quotacheck --verbose {{mountpoint}}`

- Controlla le quote utente:

`sudo quotacheck --user {{user}} {{mountpoint}}`

- Controlla le quote di gruppo:

`sudo quotacheck --group {{group}} {{mountpoint}}`
