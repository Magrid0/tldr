# znc

> Bouncer IRC.
> Maggiori informazioni: <https://manned.org/znc>.

- Esegui la configurazione iniziale:

`znc {{[-c|--makeconf]}}`

- Avvia il demone bouncer IRC:

`znc`

- Imposta `znc` per systemd:

`sudo {{[-u|--user]}} znc znc {{[-c|--makeconf]}} {{[-d|--datadir]}} /var/lib/znc`

- Abilita `znc` all'avvio e avvialo ora:

`systemctl enable znc --now`
