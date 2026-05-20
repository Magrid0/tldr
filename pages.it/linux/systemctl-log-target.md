# systemctl log-target

> Ottiene o imposta la destinazione di log per il gestore systemd.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#log-target%20%5BTARGET%5D>.

- Mostra la destinazione di log corrente del gestore systemd:

`systemctl log-target`

- Imposta la destinazione di log del gestore:

`systemctl log-target {{journal-or-kmsg|journal|kmsg|console|syslog|null|auto}}`
