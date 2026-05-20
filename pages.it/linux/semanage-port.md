# semanage port

> Gestisce le definizioni delle porte persistenti di SELinux.
> Vedi anche: `semanage`.
> Maggiori informazioni: <https://manned.org/semanage-port>.

- Elenca tutte le regole di etichettatura delle porte:

`sudo semanage port {{[-l|--list]}}`

- Elenca tutte le regole di etichettatura delle porte definite dall'utente senza intestazioni:

`sudo semanage port {{[-l|--list]}} {{[-C|--locallist]}} {{[-n|--noheading]}}`

- Aggiunge una regola definita dall'utente che assegna un'etichetta a una coppia protocollo-porta:

`sudo semanage port {{[-a|--add]}} {{[-t|--type]}} {{ssh_port_t}} {{[-p|--proto]}} {{tcp}} {{22000}}`

- Aggiunge una regola definita dall'utente che assegna un'etichetta a una coppia protocollo-intervallo di porte:

`sudo semanage port {{[-a|--add]}} {{[-t|--type]}} {{http_port_t}} {{[-p|--proto]}} {{tcp}} {{80-88}}`

- Elimina una regola definita dall'utente usando la sua coppia protocollo-porta:

`sudo semanage port {{[-d|--delete]}} {{[-p|--proto]}} {{udp}} {{11940}}`
