# swapoff

> Disabilita dispositivi e file per lo swapping.
> Nota: `percorso/del/file` può riferirsi a un file regolare o a una partizione di swap.
> Maggiori informazioni: <https://manned.org/swapoff.8>.

- Disabilita una data area di swap:

`sudo swapoff {{percorso/del/file}}`

- Disabilita tutte le aree di swap in `/proc/swaps`:

`sudo swapoff {{[-a|--all]}}`

- Disabilita una partizione di swap tramite la sua etichetta:

`sudo swapoff -L {{etichetta}}`
