# bootc

> Avvia e aggiorna tramite immagini contenitore.
> Gestisce aggiornamenti transazionali del sistema operativo sul posto usando immagini OCI/Docker.
> Maggiori informazioni: <https://manned.org/bootc>.

- Mostra le distribuzioni nell'ordine in cui appariranno nel bootloader:

`bootc status`

- Controlla se sono disponibili aggiornamenti:

`bootc upgrade --check`

- Prepara un nuovo aggiornamento e riavvia per applicarlo:

`bootc upgrade --apply`

- Cambia la base del sistema operativo con una nuova immagine contenitore:

`bootc switch {{image}}`

- Riavvia nella precedente distribuzione ostree:

`bootc rollback`

- Applica modifiche transazionali alla configurazione di sistema:

`bootc edit`
