# swapon

> Abilita dispositivi e file per lo swapping.
> Nota: `percorso/del/file` può riferirsi a un file regolare o a una partizione di swap.
> Maggiori informazioni: <https://manned.org/swapon.8>.

- Mostra le informazioni sullo swap:

`swapon`

- Abilita una data area di swap:

`sudo swapon {{percorso/del/file}}`

- Abilita tutte le aree di swap specificate in `/etc/fstab` tranne quelle con l'opzione `noauto`:

`sudo swapon {{[-a|--all]}}`

- Abilita una partizione di swap tramite la sua etichetta:

`sudo swapon -L {{etichetta}}`
