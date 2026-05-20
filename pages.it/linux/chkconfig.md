# chkconfig

> Gestisce i runlevel dei servizi su CentOS 6.
> Maggiori informazioni: <https://manned.org/chkconfig>.

- Elenca i servizi con runlevel:

`chkconfig --list`

- Mostra il runlevel di un servizio:

`chkconfig --list {{ntpd}}`

- Abilita il servizio all'avvio:

`chkconfig {{sshd}} on`

- Abilita il servizio all'avvio per i runlevel 2, 3, 4 e 5:

`chkconfig --level {{2345}} {{sshd}} on`

- Disabilita il servizio all'avvio:

`chkconfig {{ntpd}} off`

- Disabilita il servizio all'avvio per il runlevel 3:

`chkconfig --level {{3}} {{ntpd}} off`
