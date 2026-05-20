# pivot_root

> Cambia il filesystem root in una nuova directory e sposta la root corrente in una sottodirectory della nuova root.
> Comunemente usato durante l'inizializzazione del sistema (es. in `initramfs`) per passare da una root temporanea al filesystem root reale.
> Maggiori informazioni: <https://manned.org/pivot_root.8>.

- Rende `/new_root` la nuova root (`/`) e sposta la root corrente in una sua sottodirectory:

`sudo pivot_root {{percorso/nuova_root}} {{percorso/nuova_root/vecchia_root}}`

- Mostra aiuto:

`pivot_root {{[-h|--help]}}`
