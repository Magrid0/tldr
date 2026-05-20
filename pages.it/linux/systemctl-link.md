# systemctl link

> Collega un file di unità situato al di fuori del percorso di ricerca dei file di unità nel percorso di ricerca.
> Vedi anche: `systemctl disable`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#link%20PATH%E2%80%A6>.

- Collega un file di unità per renderlo disponibile ai comandi systemd:

`systemctl link {{percorso/del/servizio}}`

- Collega più file di unità contemporaneamente:

`systemctl link {{percorso/del/servizio1 percorso/del/servizio2 ...}}`
