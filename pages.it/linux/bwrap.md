# bwrap

> Esegue programmi in un sandbox leggero.
> Maggiori informazioni: <https://manned.org/bwrap>.

- Esegue un programma in un ambiente di sola lettura:

`bwrap --ro-bind / / {{/bin/bash}}`

- Concede all'ambiente l'accesso a dispositivi, informazioni sui processi e crea un `tmpfs` per esso:

`bwrap --dev-bind /dev /dev --proc /proc --ro-bind / / --tmpfs /tmp {{/bin/bash}}`
