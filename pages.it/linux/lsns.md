# lsns

> Elenca informazioni su tutti i namespace o sul namespace specificato.
> Maggiori informazioni: <https://manned.org/lsns>.

- Elenca tutti i namespace:

`lsns`

- Elenca i namespace in formato JSON:

`lsns {{[-J|--json]}}`

- Elenca i namespace associati al processo specificato:

`lsns {{[-p|--task]}} {{pid}}`

- Elenca solo il tipo di namespace specificato:

`lsns {{[-t|--type]}} {{mnt|net|ipc|user|pid|uts|cgroup|time}}`

- Elenca i namespace, mostrando solo l'ID del namespace, il tipo, il PID e il comando:

`lsns {{[-o|--output]}} {{NS,TYPE,PID,COMMAND}}`
