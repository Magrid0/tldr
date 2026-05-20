# systemd-firstboot

> Inizializza le impostazioni di base del sistema prima o durante il primo avvio di un sistema.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-firstboot.html>.

- Opera sulla directory specificata invece della directory root del sistema host:

`sudo systemd-firstboot --root {{percorso/della/directory_root}}`

- Imposta il layout della tastiera di sistema:

`sudo systemd-firstboot --keymap {{layout_tastiera}}`

- Imposta il nome host del sistema:

`sudo systemd-firstboot --hostname {{nome_host}}`

- Imposta la password dell'utente root:

`sudo systemd-firstboot --root-password {{password}}`

- Chiede all'utente in modo interattivo un'impostazione di base specifica:

`sudo systemd-firstboot --prompt {{impostazione}}`

- Forza la scrittura della configurazione anche se i file pertinenti esistono già:

`sudo systemd-firstboot --force`

- Rimuove tutti i file esistenti configurati da `systemd-firstboot`:

`sudo systemd-firstboot --reset`

- Rimuove la password dell'utente root del sistema:

`sudo systemd-firstboot --delete-root-password`
