# systemctl set-default

> Crea un symlink dell'alias `default.target` all'unità target data.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#set-default%20TARGET>.

- Imposta la modalità di avvio predefinita di `systemd`:

`systemctl set-default {{nome_target.target}}`

- Imposta `systemd` per avviarsi in modalità GUI per impostazione predefinita:

`systemctl set-default graphical.target`

- Imposta `systemd` per avviarsi in modalità CLI per impostazione predefinita:

`systemctl set-default multi-user.target`
