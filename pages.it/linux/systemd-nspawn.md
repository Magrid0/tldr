# systemd-nspawn

> Esegue un comando o un sistema operativo in un contenitore leggero.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-nspawn.html>.

- Esegue un comando in un contenitore:

`systemd-nspawn {{[-D|--directory]}} {{percorso/della/root_del_contenitore}}`

- Esegue un sistema operativo Linux completo in un contenitore:

`systemd-nspawn {{[-b|--boot]}} {{[-D|--directory]}} {{percorso/della/root_del_contenitore}}`

- Esegue il comando specificato come PID 2 nel contenitore (invece che come PID 1) utilizzando un processo init stub:

`systemd-nspawn {{[-D|--directory]}} {{percorso/della/root_del_contenitore}} {{[-a|--as-pid2]}}`

- Specifica il nome macchina e il nome host:

`systemd-nspawn {{[-M|--machine]}} {{nome_contenitore}} --hostname {{host_contenitore}} {{[-D|--directory]}} {{percorso/della/root_del_contenitore}}`
