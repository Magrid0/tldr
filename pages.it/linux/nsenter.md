# nsenter

> Esegue un nuovo comando nello spazio dei nomi di un processo in esecuzione.
> Particolarmente utile per immagini Docker o chroot jail.
> Maggiori informazioni: <https://manned.org/nsenter>.

- Esegue un comando specifico usando gli stessi spazi dei nomi di un processo esistente:

`nsenter {{[-t|--target]}} {{pid}} {{[-a|--all]}} {{comando}} {{argomenti_comando}}`

- Esegue un comando specifico nello spazio dei nomi mount|UTS|IPC|network|PID|user|cgroup|time di un processo esistente:

`nsenter {{[-t|--target]}} {{pid}} --{{mount|uts|ipc|net|pid|user|cgroup}} {{comando}} {{argomenti_comando}}`

- Esegue un comando specifico negli spazi dei nomi UTS, time e IPC di un processo esistente:

`nsenter {{[-t|--target]}} {{pid}} {{[-u|--uts]}} {{[-T|--time]}} {{[-i|--ipc]}} -- {{comando}} {{argomenti_comando}}`

- Esegue un comando specifico nello spazio dei nomi di un processo esistente referenziando procfs:

`nsenter {{[-p|--pid=]}}/proc/{{pid}}/pid/net -- {{comando}} {{argomenti_comando}}`
