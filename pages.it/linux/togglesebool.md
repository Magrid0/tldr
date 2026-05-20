# togglesebool

> Inverte i valori correnti (non persistenti) dei booleani SELinux.
> Nota: Questo strumento è stato deprecato e spesso rimosso in favore di `setsebool`.
> Maggiori informazioni: <https://manned.org/togglesebool>.

- Inverte i valori correnti (non persistenti) dei booleani specificati:

`sudo togglesebool {{virt_use_samba|virt_use_usb|...}}`

- Inverte più booleani:

`sudo togglesebool {{chiave1 chiave2 ...}}`
