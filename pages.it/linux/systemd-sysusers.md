# systemd-sysusers

> Crea utenti e gruppi di sistema.
> Se il file di configurazione non è specificato, vengono utilizzati i file nelle directory `sysusers.d`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-sysusers.html>.

- Crea utenti e gruppi da un file di configurazione specifico:

`systemd-sysusers {{percorso/del/file}}`

- Elabora i file di configurazione e stampa cosa verrebbe fatto senza effettivamente fare nulla:

`systemd-sysusers --dry-run {{percorso/del/file}}`

- Stampa il contenuto di tutti i file di configurazione (prima di ogni file, il suo nome viene stampato come commento):

`systemd-sysusers --cat-config`

- Crea utenti in base ai file elencati nel comando precedente:

`systemd-sysusers`
