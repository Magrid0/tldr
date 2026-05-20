# hd-idle

> Ferma la rotazione di dischi esterni dopo un periodo di inattività.
> Maggiori informazioni: <https://manned.org/hd-idle>.

- Avvia un servizio per gestire la rotazione del disco rigido. Di default i dischi rigidi smettono di ruotare dopo 10 minuti di inattività:

`systemctl start hd-idle`

- Ferma immediatamente la rotazione di un disco:

`hd-idle -t {{/dev/sdX}}`

- Impedisci ai dischi di fermare la rotazione, quindi imposta tempi di inattività espliciti (in secondi) per i dischi che hanno "sda" o "sdb" nel loro nome dispositivo:

`hd-idle -i 0 -a /dev/sda -i {{300}} -a /dev/sdb -i {{1200}}`
