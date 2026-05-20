# systemctl switch-root

> Passa a un nuovo filesystem root ed esegue un nuovo gestore di sistema.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#switch-root%20ROOT%20INIT>.

- Passa a un nuovo filesystem root ed esegue il suo sistema init predefinito:

`systemctl switch-root {{percorso/della/nuova_root}}`

- Passa a un nuovo filesystem root ed esegue un binario init specifico:

`systemctl switch-root {{percorso/della/nuova_root}} {{/sbin/init}}`

- Passa a un nuovo filesystem root con output verboso:

`systemctl switch-root {{percorso/della/nuova_root}} {{[-v|--verbose]}}`
