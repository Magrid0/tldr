# systemd-tty-ask-password-agent

> Elenca o elabora le richieste di password systemd in sospeso.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-tty-ask-password-agent.html>.

- Elenca tutte le richieste di password di sistema attualmente in sospeso:

`systemd-tty-ask-password-agent --list`

- Elabora continuamente le richieste di password:

`systemd-tty-ask-password-agent --watch`

- Elabora tutte le richieste di password di sistema attualmente in sospeso interrogando l'utente sul TTY chiamante:

`systemd-tty-ask-password-agent --query`

- Inoltra le richieste di password a wall invece di interrogare l'utente sul TTY chiamante:

`systemd-tty-ask-password-agent --wall`
