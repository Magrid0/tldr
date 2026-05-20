# semanage boolean

> Gestisce le impostazioni booleane persistenti di SELinux.
> Vedi anche: `semanage`, `getsebool`, `setsebool`.
> Maggiori informazioni: <https://manned.org/semanage-boolean>.

- Elenca tutte le impostazioni booleane:

`sudo semanage boolean {{[-l|--list]}}`

- Elenca tutte le impostazioni booleane definite dall'utente senza intestazioni:

`sudo semanage boolean {{[-l|--list]}} {{[-C|--locallist]}} {{[-n|--noheading]}}`

- Imposta o deseleziona un booleano in modo persistente:

`sudo semanage boolean {{[-m|--modify]}} {{-1|--on|-0|--off}} {{haproxy_connect_any}}`
