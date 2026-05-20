# systemd-ask-password

> Interroga l'utente per una password di sistema.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-ask-password.html>.

- Interroga una password di sistema con un prompt specifico:

`systemd-ask-password "{{prompt}}"`

- Specifica un identificatore per la richiesta di password:

`systemd-ask-password --id {{identificatore}} "{{prompt}}"`

- Utilizza un nome di chiave del kernel keyring come cache per la password:

`systemd-ask-password --keyname {{nome_chiave}} "{{prompt}}"`

- Imposta un timeout personalizzato per la richiesta di password:

`systemd-ask-password --timeout {{secondi}} "{{prompt}}"`

- Forza l'uso di un sistema agente e non chiede mai sul TTY corrente:

`systemd-ask-password --no-tty "{{prompt}}"`

- Memorizza una password nel kernel keyring senza visualizzarla:

`systemd-ask-password --no-output --keyname {{nome_chiave}} "{{prompt}}"`

- Invia una password a un comando, rimuovendo il carattere di newline finale:

`systemd-ask-password -n | {{comando}}`

- Mostra aiuto:

`systemd-ask-password {{[-h|--help]}}`
