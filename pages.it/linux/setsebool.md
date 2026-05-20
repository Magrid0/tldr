# setsebool

> Imposta il valore booleano SELinux.
> Vedi anche: `semanage-boolean`, `getsebool`.
> Maggiori informazioni: <https://manned.org/setsebool>.

- Mostra l'impostazione corrente di [t]utti i booleani:

`getsebool -a`

- Imposta o deseleziona un booleano temporaneamente (non persistente dopo il riavvio):

`sudo setsebool {{httpd_can_network_connect}} {{1|true|on|0|false|off}}`

- Imposta o deseleziona un booleano in modo [P]ersistente:

`sudo setsebool -P {{container_use_devices}} {{1|true|on|0|false|off}}`

- Imposta o deseleziona più booleani contemporaneamente in modo [P]ersistente:

`sudo setsebool -P {{chiave1 1 chiave2 0 ...}}`

- Imposta o deseleziona un booleano persistentemente (metodo alternativo usando `semanage-boolean`):

`sudo semanage boolean {{[-m|--modify]}} {{-1|--on|-0|--off}} {{haproxy_connect_any}}`
