# swaplabel

> Stampa o cambia l'etichetta o UUID di un'area di swap.
> Nota: `percorso/del/file` può riferirsi a un file regolare o a una partizione di swap.
> Maggiori informazioni: <https://manned.org/swaplabel>.

- Mostra l'etichetta e l'UUID correnti di un'area di swap:

`swaplabel {{percorso/del/file}}`

- Imposta l'etichetta di un'area di swap:

`swaplabel {{[-L|--label]}} {{nuova_etichetta}} {{percorso/del/file}}`

- Imposta l'UUID di un'area di swap (puoi generare un UUID usando `uuidgen`):

`swaplabel {{[-U|--uuid]}} {{nuovo_uuid}} {{percorso/del/file}}`
