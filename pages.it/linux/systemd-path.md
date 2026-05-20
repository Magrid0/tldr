# systemd-path

> Elenca e interroga i percorsi di sistema e utente.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-path.html>.

- Mostra un elenco di percorsi noti e i loro valori correnti:

`systemd-path`

- Interroga il percorso specificato e mostra il suo valore:

`systemd-path "{{nome_percorso}}"`

- Aggiunge il suffisso ai percorsi stampati:

`systemd-path --suffix {{stringa_suffisso}}`

- Stampa una breve stringa di versione e poi esce:

`systemd-path --version`
