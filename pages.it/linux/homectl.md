# homectl

> Crea, rimuove, modifica o ispeziona le home directory usando il servizio systemd-homed.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/homectl.html>.

- Elenca gli account utente e le loro home directory associate:

`homectl list`

- Crea un account utente e la sua home directory associata:

`sudo homectl create {{username}}`

- Rimuove un utente specifico e la home directory associata:

`sudo homectl remove {{username}}`

- Cambia la password per un utente specifico:

`sudo homectl passwd {{username}}`

- Esegue una shell o un comando con accesso a una home directory specifica:

`sudo homectl with {{username}} -- {{command}} {{command_arguments}}`

- Blocca o sblocca una home directory specifica:

`sudo homectl {{lock|unlock}} {{username}}`

- Cambia lo spazio su disco assegnato a una home directory specifica a 100 GiB:

`sudo homectl resize {{username}} {{100G}}`

- Mostra aiuto:

`homectl {{[-h|--help]}}`
