# semanage permissive

> Gestisce i domini permissivi persistenti di SELinux.
> Nota: questo rende effettivamente il processo non confinato. Per un uso a lungo termine, si consiglia di configurare SELinux correttamente.
> Vedi anche: `semanage`, `getenforce`, `setenforce`.
> Maggiori informazioni: <https://manned.org/semanage-permissive>.

- Elenca tutti i tipi di processo (noti anche come domini) che sono in modalità permissiva:

`sudo semanage permissive {{[-l|--list]}}`

- Imposta la modalità permissiva per un dominio:

`sudo semanage permissive {{[-a|--add]}} {{httpd_t}}`

- Deseleziona la modalità permissiva per un dominio:

`sudo semanage permissive {{[-d|--delete]}} {{httpd_t}}`
