# kpartx

> Crea device map da tabelle delle partizioni.
> Maggiori informazioni: <https://manned.org/kpartx>.

- Aggiunge mapping di partizioni e stampa i mapping creati:

`kpartx -av {{whole_disk.img}}`

- Elimina mapping di partizioni:

`kpartx -d {{whole_disk.img}}`

- Elenca i mapping di partizioni:

`kpartx -l {{whole_disk.img}}`
