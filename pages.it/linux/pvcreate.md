# pvcreate

> Inizializza un disco o una partizione per l'uso come volume fisico.
> Vedi anche: `lvm`.
> Maggiori informazioni: <https://manned.org/pvcreate>.

- Inizializza il volume `/dev/sda1` per l'uso da parte di LVM:

`sudo pvcreate {{/dev/sdXY}}`

- Forza la creazione senza alcuna richiesta di conferma:

`sudo pvcreate {{[-f|--force]}} {{/dev/sdXY}}`
