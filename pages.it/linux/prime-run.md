# prime-run

> Esegue un programma usando una scheda grafica Nvidia alternativa.
> Maggiori informazioni: <https://wiki.archlinux.org/title/PRIME#PRIME_render_offload>.

- Esegue un programma usando una GPU Nvidia dedicata:

`prime-run {{comando}}`

- Valida se la scheda Nvidia viene utilizzata:

`prime-run glxinfo | grep "OpenGL renderer"`
