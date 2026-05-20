# systemd-tmpfiles

> Crea, elimina e pulisce file e directory volatili e temporanei.
> Questo comando viene invocato automaticamente all'avvio dai servizi systemd e di solito non è necessario eseguirlo manualmente.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-tmpfiles.html>.

- Crea file e directory come specificato nella configurazione:

`systemd-tmpfiles --create`

- Pulisce file e directory con parametri di età configurati:

`systemd-tmpfiles --clean`

- Rimuove file e directory come specificato nella configurazione:

`systemd-tmpfiles --remove`

- Applica le operazioni per le configurazioni specifiche dell'utente:

`systemd-tmpfiles --create --user`

- Esegue le righe contrassegnate per l'avvio iniziale:

`systemd-tmpfiles --create --boot`
