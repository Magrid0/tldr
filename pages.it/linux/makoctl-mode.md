# makoctl mode

> Gestisce le modalità di notifica in `mako`.
> Le modalità possono essere usate per cambiare il comportamento delle notifiche (es. non-disturbare).
> Maggiori informazioni: <https://manned.org/makoctl>.

- Elenca tutte le modalità attualmente attive:

`makoctl mode`

- Aggiunge una modalità:

`makoctl mode -a {{do-not-disturb}}`

- Rimuove una modalità:

`makoctl mode -r {{do-not-disturb}}`

- Alterna una modalità (aggiunge se assente, rimuove se presente):

`makoctl mode -t {{do-not-disturb}}`

- Imposta modalità specifiche, sostituendo tutte le modalità correnti:

`makoctl mode -s {{mode1 mode2 ...}}`
