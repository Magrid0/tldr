# schroot

> Esegue un comando o avvia una shell interattiva con una directory root diversa. Più personalizzabile di `chroot`.
> Maggiori informazioni: <https://wiki.debian.org/Schroot>.

- Elenca i chroot disponibili:

`schroot --list`

- Esegue un comando in un chroot specifico:

`schroot --chroot {{chroot}} {{comando}}`

- Esegue un comando con opzioni in un chroot specifico:

`schroot --chroot {{chroot}} {{comando}} -- {{opzioni_comando}}`

- Esegue un comando in tutti i chroot disponibili:

`schroot --all {{comando}}`

- Avvia una shell interattiva in un chroot specifico come utente specifico:

`schroot --chroot {{chroot}} --user {{utente}}`

- Inizia una nuova sessione (un ID sessione univoco viene restituito su `stdout`):

`schroot --begin-session --chroot {{chroot}}`

- Si connette a una sessione esistente:

`schroot --run-session --chroot {{id_sessione}}`

- Termina una sessione esistente:

`schroot --end-session --chroot {{id_sessione}}`
