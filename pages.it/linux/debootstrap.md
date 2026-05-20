# debootstrap

> Crea un sistema Debian di base.
> Maggiori informazioni: <https://wiki.debian.org/Debootstrap>.

- Crea un sistema Debian stable all'interno della directory `debian-root`:

`sudo debootstrap stable {{path/to/debian-root}}/ http://deb.debian.org/debian`

- Crea un sistema minimale includendo solo i pacchetti richiesti:

`sudo debootstrap --variant=minbase stable {{path/to/debian-root}}/`

- Crea un sistema Debian Unstable all'interno della directory `sid-root` con un mirror locale:

`sudo debootstrap sid {{path/to/sid-root}}/ {{file:///path/to/mirror}}/`

- Passa a un sistema bootstrap:

`sudo chroot {{path/to/root}}`

- Elenca le release disponibili:

`ls /usr/share/debootstrap/scripts/`
