# getsebool

> Ottiene il valore booleano di SELinux.
> Vedi anche: `semanage-boolean`, `setsebool`.
> Maggiori informazioni: <https://manned.org/getsebool>.

- Mostra l'impostazione corrente di un booleano:

`getsebool {{httpd_can_connect_ftp}}`

- Mostra l'impostazione corrente di [t]utti i booleani:

`getsebool -a`

- Mostra l'impostazione corrente di tutti i booleani con spiegazioni:

`sudo semanage boolean {{[-l|--list]}}`
