# systemd-repart

> Ingrandisce e aggiunge automaticamente partizioni.
> Ingrandisce e aggiunge partizioni in base ai file di configurazione descritti in repart.d.
> Non ridimensiona automaticamente il filesystem sulla partizione. Vedere systemd-growfs per estendere il filesystem.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-repart.html>.

- Ingrandisce la partizione di root (/) a tutto lo spazio disco disponibile:

`systemd-repart`

- Visualizza le modifiche senza applicarle:

`systemd-repart --dry-run yes`

- Ingrandisce la dimensione della partizione di root a 10 gigabyte:

`systemd-repart --size 10G --root /`
