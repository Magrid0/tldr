# upgradepkg

> Aggiorna i pacchetti Slackware sostituendo i pacchetti esistenti con nuove versioni.
> Vedi anche: `installpkg`, `removepkg`, `makepkg`, `pkgtool`.
> Maggiori informazioni: <https://slackware.nl/slackware/slackware64-current/source/a/pkgtools/manpages/upgradepkg.8>.

- Aggiorna un pacchetto:

`sudo upgradepkg {{percorso/del/pacchetto.tgz}}`

- Aggiorna un pacchetto, installandolo se non è già presente:

`sudo upgradepkg --install-new {{percorso/del/pacchetto.tgz}}`

- Reinstalla un pacchetto (anche se la stessa versione è già installata):

`sudo upgradepkg --reinstall {{percorso/del/pacchetto.tgz}}`

- Anteprima di ciò che accadrebbe senza effettivamente aggiornare:

`upgradepkg --dry-run {{percorso/del/pacchetto.tgz}}`

- Aggiorna un pacchetto e mostra i dettagli dell'avanzamento:

`sudo upgradepkg --verbose {{percorso/del/pacchetto.tgz}}`
