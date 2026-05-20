# mmdebstrap

> Crea un chroot Debian.
> Alternativa a `debootstrap`.
> Maggiori informazioni: <https://gitlab.mister-muffin.de/josch/mmdebstrap/>.

- Crea un chroot Debian Stable in una directory:

`sudo mmdebstrap stable {{path/to/debian-root}}/`

- Crea un chroot Debian Bookworm in un tarball usando un mirror:

`mmdebstrap bookworm {{path/to/debian-bookworm.tar}} {{http://mirror.example.org/debian}}`

- Crea un chroot Debian Sid in un tarball con pacchetti aggiuntivi:

`mmdebstrap sid {{path/to/debian-sid.tar}} --include={{pkg1,pkg2}}`
